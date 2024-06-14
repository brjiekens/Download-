<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Links de Download</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Meus Links de Download</h1>
        <ul id="download-links">
            <!-- Links serão adicionados aqui -->
        </ul>
        <div class="add-link-form">
            <input type="text" id="link-name" placeholder="Nome do arquivo">
            <input type="text" id="link-url" placeholder="URL do download">
            <button onclick="addLink()">Adicionar Link</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
