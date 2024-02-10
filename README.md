<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Cumple Steph</title>
    <style>
        body {
            background-color: black;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
            position: relative;
        }
        #fireworksCanvas {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        #textContainer {
            z-index: 1;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: white;
            font-style: italic;
            font-size: 58px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div id="textContainer">Feliz Cumple Steph</div>

    <canvas id="fireworksCanvas"></canvas>

    <script src="cumple.js"></script>
</body>
</html> 
