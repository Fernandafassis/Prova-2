<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prova 2</title>
</head>
<body>
    <h1>Cadastros</h1>
    <h2>Complete suas informações</h2>
    <form action="#" method="post">
        <div>
            <label> Nome Completo</label>
            <input type="text" name="nome" id="nome">
        </div>

        <div>
            <label for="senhas">Senhas</label>
            <input type="password" name="senhas" id="senhas">
        </div>

<div>
    <label for="Email">E-mail</label>
    <input type="email" name="email" id="email">
</div>

<div>
    <h2>Quais qualidades te definem mais?</h2>
    
    <label for="check">Afetuoso</label>
    <input type="checkbox" name="check" id="check">
    <label for="check1">Impaciente</label>
    <input type="checkbox" name="check1" id="check1">
    <label for="check2">Dedicado</label>
    <input type="checkbox" name="check2" id="check2">
    <label for="check3">Resolutivo</label>
    <input type="checkbox" name="check3" id="check3">
    <label for="check4">Amigável</label>
    <input type="checkbox" name="check4" id="check4">
</div>

<div>
    <h2>Você tem disponibilidade para trabalhar home office?</h2>
    <label for="sim"><input type="radio" name="sim" value="sim">Sim</label>
    
    <label for="não"><input type="radio" name="não" value="não">Não</label>
</div>

<br>
    <div>
        <label for="Enviar">Anexe seu currículo</label>
        <input type="submit" value="Enviar">
    </div>
</br>
<br>
<div>
    <button type="reset">Limpar</button>
</div>
    </form>
</body>
</html>
