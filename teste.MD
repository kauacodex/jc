<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Efeitos Visuais</title>
    <style>
        .gradient-background {
            width: 100%;
            height: 100vh;
            background: linear-gradient(45deg, #ff0000, #0000ff);
            background-size: 400% 400%;
            animation: gradient 10s ease infinite;
        }
        @keyframes gradient {
            0% { background-position: 0% 0%; }
            50% { background-position: 100% 100%; }
            100% { background-position: 0% 0%; }
        }
    </style>
</head>
<body>
    <div class="gradient-background"></div>
</body>
</html>
