<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inscrição para Formação</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; }
        form { max-width: 600px; margin: auto; }
        label { display: block; margin: 10px 0 5px; }
        input, textarea, select { width: 100%; padding: 10px; margin: 5px 0 15px; }
        button { padding: 10px 20px; background-color: #28a745; color: white; border: none; cursor: pointer; }
        button:hover { background-color: #218838; }
    </style>
</head>
<body>

    <h1>Inscrição para Formação em [Tema da Formação]</h1>
    <p>Preencha o formulário abaixo para se inscrever na formação.</p>

    <form>
        <label for="nome">Nome Completo</label>
        <input type="text" id="nome" name="nome" required>

        <label for="email">E-mail</label>
        <input type="email" id="email" name="email" required>

        <label for="telefone">Telefone</label>
        <input type="tel" id="telefone" name="telefone">

        <label for="endereco">Endereço</label>
        <input type="text" id="endereco" name="endereco">

        <label for="empresa">Empresa/Organização</label>
        <input type="text" id="empresa" name="empresa">

        <label for="cargo">Cargo/Profissão</label>
        <input type="text" id="cargo" name="cargo">

        <label for="num_pessoas">Número de Pessoas da Empresa Participantes</label>
        <select id="num_pessoas" name="num_pessoas" required>
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
            <option value="5">5</option>
            <option value="6">6</option>
            <option value="7">7</option>
            <option value="8">8</option>
            <option value="9">9</option>
            <option value="10">10</option>
            <option value="mais_de_15">Mais de 15</option>
        </select>

        <label for="motivacao">Motivação para Participar</label>
        <textarea id="motivacao" name="motivacao"></textarea>

        <button type="submit">Inscreva-se Agora</button>
    </form>

</body>
</html>

