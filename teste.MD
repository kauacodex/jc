<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página Interativa</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #f0f0f0;
        }
        .container {
            text-align: center;
        }
        .animated-button {
            padding: 15px 30px;
            font-size: 16px;
            border: none;
            border-radius: 5px;
            background: #3498db;
            color: #fff;
            cursor: pointer;
            transition: background 0.3s, transform 0.3s;
        }
        .animated-button:hover {
            background: #2980b9;
            transform: scale(1.05);
        }
        .animated-button:active {
            background: #1c598a;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Bem-vindo à Minha Página Interativa!</h1>
        <button class="animated-button">Clique Aqui</button>
    </div>
</body>
</html>
