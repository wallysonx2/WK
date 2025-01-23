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
        iframe {
            width: 100%;
            max-width: 720px;
            height: 405px;
            border: none;
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
            if (senhaDigitada === senhaCorreta) {
                document.querySelector('.proxima-pista').style.display = 'block';
            } else {
                alert("Senha incorreta! Tente novamente.");
            }
        }
    </script>
</head>
<body>
    <h1>O início da jornada</h1>
    <p>Bem-vinda ao início da sua grande surpresa! Clique no vídeo abaixo para assistir à mensagem especial.</p>
    <iframe src="https://www.youtube.com/embed/mF64Njl0zYg" allowfullscreen></iframe>

    <div class="senha-container">
        <p>Digite a senha para desbloquear a próxima pista:</p>
        <input type="text" id="senha" placeholder="Digite a senha aqui">
        <button onclick="verificarSenha()">Verificar</button>
    </div>

    <div class="proxima-pista">
        <h2>Próxima pista</h2>
        <p>Agora vá até a **[DESCREVA A LOCALIZAÇÃO DA PRÓXIMA PISTA AQUI]** para continuar sua jornada!</p>
    </div>
</body>
</html>
