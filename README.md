<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Inicial</title>
    <style>
        body {
            background-color: #f8c8dc; /* Fondo pastel */
            font-family: 'Times New Roman', serif;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            flex-direction: column;
        }
        .container {
            max-width: 600px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .flower {
            width: 150px; /* Ajusta el tamaño de las flores según lo necesites */
            height: auto;
            margin: 0 60px; /* Espacio entre las flores y el texto */
        }
        h1 {
            font-size: 2.5em;
            color: #333;
        }
        .button {
            padding: 20px 25px;
            font-size: 1em;
            background-color: #d4a5a5;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #b27f7f;
        }
        .link {
            font-size: 15px;
            color: #000;
            text-decoration: none;
            margin-top: 20px;
            transition: color 0.3s ease;
        }
        .link:hover {
            color: #0000ff; /* Cambia a azul cuando el cursor pasa por encima */
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="Rosa1.png" alt="Flor Roja" class="flower">
        <h1>¿Quieres saber por qué me haces feliz?💖</h1>
        <img src="Rosa1.png" alt="Flor Roja" class="flower">
    </div>
    
    <a href="ForMyLove2.html">
        <button class="button">¡Click aquí mi reina!</button>
    </a>

    <p>
        <a href="https://www.facebook.com/leandro.xilot" class="link">
            De tu novio y futuro esposo
        </a>
    </p>

</body>
</html>
