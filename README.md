<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Teu jeito singular</title>
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
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 15px;
            margin-top: 20px;
        }
    </style>
    <script>
        function pedirSenha() {
            var senha = prompt("Digite a senha para acessar o site:");
            if (senha !== "1808") { // Defina a senha aqui
                alert("Senha incorreta! Acesso negado.");
                document.body.innerHTML = ""; // Limpa o conteúdo da página
            }
        }
    </script>
</head>
<body onload="pedirSenha()">
    <h1>É tão particular o meu encontro quando é com você</h1>
    <p>Essa foto é só pra lembrar o quanto amo você! Você é minha luz, meu sorriso e meu tudo. 💕</p>
    <img src="WK.jpg" alt="Uma foto nossa">
    <video controls>
      <source src="https://drive.google.com/file/d/1Jo9x_7R-lP6sJUEUKYNl-boxeeid0JBe/view?usp=drivesdk" type="video/mp4">
</body>
</html>
