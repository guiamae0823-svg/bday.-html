<!DOCTYPE html>
<html>
<head>
    <title>Birthday.exe</title>

    <!-- Pixel font -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            height: 100vh;
            background: #080b10;
            color: #00ff88;
            font-family: "Press Start 2P", monospace;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }

        /* Background code */
        .code {
            position: absolute;
            color: rgba(0, 255, 136, 0.08);
            font-size: 12px;
            line-height: 2;
            white-space: pre;
            pointer-events: none;
        }

        .code1 {
            top: 5%;
            left: 3%;
        }

        .code2 {
            bottom: 5%;
            right: 3%;
        }

        /* Main terminal */
        .terminal {
            width: 90%;
            max-width: 850px;
            background: #0d1117;
            border: 2px solid #00ff88;
            border-radius: 8px;
            box-shadow: 0 0 30px rgba(0, 255, 136, 0.2);
            overflow: hidden;
            position: relative;
            z-index: 2;
        }

        .top-bar {
            background: #151b23;
            padding: 12px 18px;
            border-bottom: 1px solid #26303b;
            color: #777;
            font-size: 11px;
        }

        .dots {
            color: #00ff88;
            margin-right: 10px;
        }

        .content {
            padding: 45px;
        }

        .line {
            color: #7d8590;
            font-size: 12px;
            margin-bottom: 20px;
        }

        .keyword {
            color: #ff79c6;
        }

        .blue {
            color: #58a6ff;
        }

        .green {
            color: #00ff88;
        }

        .yellow {
            color: #ffd866;
        }

        h1 {
            font-size: 38px;
            line-height: 1.5;
            color: #00ff88;
            text-shadow: 0 0 12px rgba(0, 255, 136, 0.5);
            margin: 20px 0;
        }

        .message {
            color: #c9d1d9;
            font-size: 13px;
            line-height: 2.2;
            max-width: 700px;
        }

        .cursor {
            display: inline-block;
            width: 10px;
            height: 18px;
            background: #00ff88;
            animation: blink 0.8s infinite;
            vertical-align: middle;
        }

        button {
            margin-top: 30px;
            padding: 15px 22px;
            background: transparent;
            border: 2px solid #00ff88;
            color: #00ff88;
            font-family: "Press Start 2P", monospace;
            font-size: 11px;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #00ff88;
            color: #080b10;
            box-shadow: 0 0 20px rgba(0, 255, 136, 0.5);
        }

        #surprise {
            margin-top: 25px;
            color: #ffd866;
            font-size: 12px;
            line-height: 2;
            display: none;
        }

        .footer {
            margin-top: 35px;
            color: #555;
            font-size: 9px;
        }

        @keyframes blink {
            50% {
                opacity: 0;
            }
        }

        @media (max-width: 600px) {
            .content {
                padding: 25px;
            }

            h1 {
                font-size: 25px;
            }

            .message {
                font-size: 10px;
            }
        }
    </style>
</head>

<body>

    <div class="code code1">
        01010101 01010011 01000101 01010010
        function birthday() {
            return happiness;
        }

        if (today == specialDay) {
            celebrate();
        }
    </div>

    <div class="code code2">
        > initializing...
        > loading memories...
        > compiling happiness...
        > SUCCESS
    </div>


    <div class="terminal">

        <div class="top-bar">
            <span class="dots">● ● ●</span>
            birthday.exe — terminal
        </div>

        <div class="content">

            <div class="line">
                <span class="green">LUIGI@birthday</span>:~$ ./celebrate
            </div>

            <div class="line">
                <span class="keyword">const</span>
                <span class="blue">birthday</span> =
                <span class="yellow">true</span>;
            </div>

            <h1>HAPPY BIRTHDAY <br>KUYA!🎂</h1>

            <div class="message">
                <span class="green">></span>
                System message detected...
                <br><br>

                <span class="blue">Age:</span> +1 unlocked
                <br>

                <span class="blue">Status:</span>
                <span class="green"> LEVEL UP! ✓</span>
                <br>

                <span class="blue">Mission:</span>
                Have an awesome year.
                <br><br>

                May this new chapter bring you
                more good memories, success,
                happiness, and plenty of reasons
                to smile.
                <br><br>

                Keep going. Keep growing.
                And don't forget to enjoy the journey!
                <span class="cursor"></span>
            </div>

            <button onclick="showSurprise()">
                &gt; OPEN
            </button>

            <div id="surprise">
                [SYSTEM] 🎉 SURPRISE UNLOCKED! 🎉
                <br><br>
                Happy Birthday, kuya!
                <br>
                Wishing you a great year ahead!
                <br>

            <div class="footer">
                // program completed successfully
            </div>

        </div>
    </div>


    <script>
        function showSurprise() {
            document.getElementById("surprise").style.display = "block";
        }
    </script>

</body>
</html>
