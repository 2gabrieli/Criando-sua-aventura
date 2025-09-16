<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Mistério no Castelo Assombrado</title>
</head>
<body>
    <main>
        <div class="passo ativo" id="passo-0">
            <img src="img/castelo-inicio.png" alt="Castelo sombrio visto ao longe">
            <p>Em uma noite de lua cheia, você decide explorar um antigo castelo abandonado que dizem ser assombrado. Assim que entra, duas portas misteriosas aparecem diante de você.</p>
            <button class="btn-proximo" data-proximo="1">Entrar pela porta da esquerda</button>
            <button class="btn-proximo" data-proximo="2">Entrar pela porta da direita</button>
        </div>

        <div class="passo" id="passo-1">
            <p>A porta da esquerda leva a uma biblioteca antiga cheia de livros empoeirados. Um dos livros parece brilhar...</p>
            <button class="btn-proximo" data-proximo="3">Abrir o livro brilhante</button>
            <button class="btn-proximo" data-proximo="4">Ignorar o livro e procurar em outro lugar</button>
        </div>

        <div class="passo" id="passo-2">
            <p>A porta da direita leva a um salão escuro onde você ouve passos ecoando. No fundo, há uma escada que sobe e uma que desce.</p>
            <button class="btn-proximo" data-proximo="5">Subir a escada</button>
            <button class="btn-proximo" data-proximo="6">Descer a escada</button>
        </div>

        <div class="passo" id="passo-3">
            <p>Ao abrir o livro, um mapa cai revelando que existe uma passagem secreta no porão do castelo.</p>
            <button class="btn-proximo" data-proximo="6">Seguir para o porão</button>
        </div>

        <div class="passo" id="passo-4">
            <img src="img/fim-voltar.png" alt="Saindo do castelo assustado">
            <p>Você sente um arrepio na espinha e decide que é melhor não continuar. Sai correndo do castelo e nunca mais volta.</p>
        </div>

        <div class="passo" id="passo-5">
            <p>Subindo as escadas, você encontra uma sala iluminada por velas. No centro há um espelho antigo.</p>
            <button class="btn-proximo" data-proximo="7">Olhar no espelho</button>
            <button class="btn-proximo" data-proximo="4">Ignorar o espelho e sair</button>
        </div>

        <div class="passo" id="passo-6">
            <p>No porão escuro, você encontra uma porta secreta trancada com símbolos estranhos.</p>
            <button class="btn-proximo" data-proximo="8">Tentar decifrar os símbolos</button>
            <button class="btn-proximo" data-proximo="4">Desistir e sair do castelo</button>
        </div>

        <div class="passo" id="passo-7">
            <p>Ao olhar no espelho, você vê a sombra de uma figura misteriosa atrás de você, que indica o caminho para a porta secreta no porão.</p>
            <button class="btn-proximo" data-proximo="6">Ir para o porão</button>
        </div>

        <div class="passo" id="passo-8">
            <img src="img/tesouro-castelo.png" alt="Tesouro escondido no castelo">
            <p>Você decifra os símbolos e a porta se abre, revelando uma sala secreta com tesouros e segredos antigos do castelo. Você resolveu o mistério!</p>
        </div>
    </main>
    <script src="script.js"></script>
</body>
</html>