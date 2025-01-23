<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>O início da jornada</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
        }
        h1 {
            color: #4CAF50;
        }
        p {
            font-size: 18px;
            color: #333;
            margin-bottom: 20px;
        }
        video {
            max-width: 100%;
            border-radius: 15px;
            margin-bottom: 20px;
        }
        .proxima-pista {
            display: none;
            margin-top: 20px;
            padding: 15px;
            background-color: #e0ffe0;
            border: 2px solid #4CAF50;
            border-radius: 10px;
            font-size: 18px;
            color: #333;
        }
        .senha-container {
            margin-top: 20px;
        }
        input[type="text"] {
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ccc;
            border-radius: 5px;
            margin-right: 10px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #4CAF50;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
    <script>
        function verificarSenha() {
            const senhaCorreta = "1808";
            const senhaDigitada = document.getElementById("senha").value;
            const mensagem = document.getElementById("proximaPista");

            if (senhaDigitada === senhaCorreta) {
                mensagem.style.display = "block";
            } else {
                alert("Senha incorreta! Tente novamente.");
            }
        }
    </script>
</head>
<body>
    <h1>O início da sua jornada 💌</h1>
    <p>Pequerrucha, hoje começa uma aventura especial: sua jornada até uma surpresa de aniversário única, feita com todo meu amor. ❤️</p>
    <p>Antes de continuar, clica no vídeo aqui embaixo pra assistir minha mensagem especial pra você. 😉</p>
    <video controls>
        <source src="[video1.mp4](https://drive.google.com/file/d/1Jo9x_7R-lP6sJUEUKYNl-boxeeid0JBe/view?usp=drive_link)" type="video/mp4">
        Seu navegador não suporta vídeos.
    </video>
    <div class="senha-container">
        <p>Insira a senha para revelar a próxima pista:</p>
        <input type="text" id="senha" placeholder="Digite a senha aqui">
        <button onclick="verificarSenha()">Verificar</button>
    </div>
    <div id="proximaPista" class="proxima-pista">
        <p>Parabéns! Você desbloqueou a próxima pista. Vá até o banco onde nos sentamos no nosso primeiro encontro e procure pelo próximo QR Code. Boa sorte! 💕</p>
    </div>
</body>
</html>
