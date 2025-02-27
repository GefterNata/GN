<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <!-- Adicionando fontes do Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@900&family=Playfair+Display&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Playfair Display', serif; /* Fonte Playfair Display para o texto */
            background-color: #1c1c1c; /* Fundo cinza ainda mais escuro */
            color: #dcdcdc; /* Texto cinza clarinho */
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        h1 {
            font-family: 'Lato', sans-serif; /* Fonte Lato ExtraBold para o título */
            font-weight: 900;
            color: #dcdcdc; /* Cor do título */
        }

        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        .gallery img {
            width: 280px;
            height: auto;
            border-radius: 20px; /* Moldura arredondada */
            box-shadow: 2px 2px 15px rgba(0,0,0,0.2);
            transition: transform 0.3s ease-in-out;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <h1>Gefter Natã</h1>
    <p>Aqui estão alguns dos meus trabalhos:</p>
    
    <div class="gallery">
        <img src="https://via.placeholder.com/300" alt="Projeto 1">
        <img src="https://via.placeholder.com/300" alt="Projeto 2">
        <img src="https://via.placeholder.com/300" alt="Projeto 3">
    </div>
</body>
</html>
