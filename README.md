<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para mi niña 💖</title>
    <style>
        body {
            background-color: #fff0f5;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        h1 {
            color: #ff4d6d;
            margin-top: 40px;
            font-size: 2.5em;
        }
        .container {
            margin-top: 50px;
        }
        .heart {
            width: 150px;
            height: 150px;
            background-color: #ff4d6d;
            position: relative;
            display: inline-block;
            transform: rotate(-45deg);
            animation: beat 1s infinite;
        }
        .heart::before,
        .heart::after {
            content: "";
            width: 150px;
            height: 150px;
            background-color: #ff4d6d;
            border-radius: 50%;
            position: absolute;
        }
        .heart::before {
            top: -75px;
            left: 0;
        }
        .heart::after {
            top: 0;
            left: 75px;
        }
        @keyframes beat {
            0%, 100% { transform: rotate(-45deg) scale(1); }
            50% { transform: rotate(-45deg) scale(1.1); }
        }
        p {
            font-size: 1.5em;
            color: #ff4d6d;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <h1>TE AMO ❤️</h1>
    <div class="container">
        <div class="heart"></div>
    </div>
    <p>Lo estás haciendo muy bien mi niña 💕</p>
</body>
</html>
