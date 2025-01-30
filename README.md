<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            font-family: 'Courier New', Courier, monospace;
            color: #0ff;
            overflow: hidden;
        }

        h1 {
            font-size: 4rem;
            text-shadow: 0 0 10px #0ff, 0 0 20px #0ff, 0 0 30px #ff0080, 0 0 40px #ff0080;
            animation: glow 2s infinite alternate;
        }

        @keyframes glow {
            0% {
                text-shadow: 0 0 10px #0ff, 0 0 20px #0ff, 0 0 30px #ff0080, 0 0 40px #ff0080;
            }
            100% {
                text-shadow: 0 0 20px #0ff, 0 0 30px #0ff, 0 0 40px #ff0080, 0 0 50px #ff0080;
            }
        }
    </style>
</head>
<body>
    <h1>Bandhan Munjal</h1>
</body>
</html>
