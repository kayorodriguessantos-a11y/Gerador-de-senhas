
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Gerador de Senhas</title>
</head>
<body>

    <h1>Gerador de Senhas</h1>

    <label for="tamanhoSenha">
        Quantidade de caracteres:
    </label>

    <input type="number" id="tamanhoSenha"
           min="4" max="32" value="12">

    <br><br>

    <input type="checkbox" id="maiusculas" checked>
    <label for="maiusculas">Letras maiúsculas</label>

    <br>

    <input type="checkbox" id="minusculas" checked>
    <label for="minusculas">Letras minúsculas</label>

    <br>

    <input type="checkbox" id="numeros" checked>
    <label for="numeros">Números</label>

    <br>

    <input type="checkbox" id="simbolos">
    <label for="simbolos">Símbolos</label>

    <br><br>

    <button id="botaoGerar">Gerar senha</button>

    <p id="senhaGerada">Sua senha aparecerá aqui.</p>

    <script src="script.js"></script>

</body>
</html>
