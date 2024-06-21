<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Você decide o futuro da IA</title>
</head>
<body>
    <div class="caixa-principal">
        <h1>Você decide o futuro do IA</h1>
        <div class="caixa-perguntas">
            Você já sabe quais são as perguntas que irão nortear sua missão ?
        </div>
        <div class="caixa-alternativas">
            <button>Sim, eu já sei</button>
            <button>Não, estou ajustando algumas coias</button>
        </div>
        <div class="caixa-resultado">
            <p class="texto-resultado">
                E o seu texto final, já está pronto ?
            </p>
        </div>
    </div>
</body>
</html>
:root{
    --cor-fundo: #01080E;
    --cor-principal: #0B0D20 ;
    --cor-secundaria: #212333;
    --cor-destaque: #2BDEFD;
    --cor-texto: #D7F9FF;
}

body{
    background-color: var(--cor-fundo);
    color: var(--cor-texto);
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.caixa-principal{
    background-color: var(--cor-principal);
    width: 90%;
    max-width: 600px;
    text-align: center;
    padding: 20px;
}

h1{
    color: var(--cor-destaque);
}

.caixa-perguntas{
    padding-bottom: 10px;
}
:root{
    --cor-fundo: #01080E;
    --cor-principal: #0B0D20 ;
    --cor-secundaria: #212333;
    --cor-destaque: #2BDEFD;
    --cor-texto: #D7F9FF;
}

button{
    background-color: var(--cor-secundaria);
    color: var(--cor-texto);
    border: none;
    border-radius: 15px;
    padding: 15px;
    transition: background-color 0.3s;
}

button:hover{
    background-color: var(--cor-destaque);
    color: var(--cor-principal);
}
