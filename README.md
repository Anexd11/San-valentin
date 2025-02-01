<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>San Valentín 💖</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background-color: #ffe6e6;
            padding: 50px;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
            display: inline-block;
        }
        h1 {
            color: #ff4d6d;
        }
        button {
            background: #ff4d6d;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 20px;
        }
        button:hover {
            background: #ff1f4d;
        }
        #mensaje {
            font-size: 24px;
            color: #ff4d6d;
            margin-top: 20px;
            display: none;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>¿Quieres ser mi San Valentín? 💘</h1>
        <button onclick="mostrarMensaje()">Sí 💖</button>
        <p id="mensaje">¡Te amo mucho! 💕</p>
    </div>

    <script>
        function mostrarMensaje() {
            document.getElementById("mensaje").style.display = "block";
        }
    </script>

</body>
</html>
