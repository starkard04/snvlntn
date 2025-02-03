<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Serás mi San Valentín?</title>
    <style>
        body {
            background-color: #3B2F2F;
            color: #E0D8B0;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
        }
        .container {
            background-color: #6B8E23;
            padding: 20px;
            border-radius: 15px;
            display: inline-block;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.5);
        }
        .button {
            background-color: #8B4513;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 10px;
            font-size: 20px;
            cursor: pointer;
            margin: 10px;
        }
        .button:hover {
            background-color: #A0522D;
        }
        img {
            width: 200px;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>¿Serás mi San Valentín?</h1>
        <img src="https://upload.wikimedia.org/wikipedia/en/9/96/Tarzan_%281999_film%29_poster.jpg" alt="Tarzán">
        <p>Como Tarzán en la selva, mi corazón grita tu nombre.</p>
        <p>¿Quieres ser mi Jane este San Valentín?</p>
        <button class="button" onclick="alert('¡Sabía que dirías que sí! 🥰')">Sí</button>
        <button class="button" onclick="alert('¡No puedes decir que no! 😜')">No</button>
    </div>
</body>
</html>
