# Projeto-BandFlix
Criei um clone da interface da netflix para colocar sua banda favorita, uma descrição sobre a banda e seus melhores albuns
<!DOCTYPE html>
<html lang="pt_BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style/style.css">
    <link rel="stylesheet" href="/style/owl/owl.carousel.min.css">
    <link rel="stylesheet" href="/style/owl/owl.theme.default.min.css">
    <title>BandFlix</title>
</head>
<body>
    <header>
        <h2 id="cabeçalho-titulo">BandFlix</h2>
        <nav id="nav">
            <ul class="cabeçalho-menu">
                <li class="item-menu"><a href="#">Inicio</a></li>
                <li class="item-menu"><a href="#">Albuns</a></li>
                <li class="item-menu"><a href="#">Discografia</a></li>
                <li class="item-menu"><a href="#">Sobre</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <div class="div-container">
            <div class="descricao-banda">
                <h1 id="nome-banda"><span>Pink Floyd</span></h1>
                <p id="texto-banda"> Pink Floyd foi uma banda britânica de rock formada em Londres em 1965. 
                    Ganhando seguidores como um grupo de rock psicodélico, eles se destacaram 
                    por suas composições longas, pela experimentação sonora, pelas letras filosóficas
                    e pelas apresentações ao vivo criativas, o que levou a se tornarem uma banda líder
                    do gênero do rock progressivo. Eles são um dos grupos mais bem-sucedidos comercialmente 
                    e influentes da história da música popular.
                </p>
                <div class="butoes-container">
                    <button class="botao">Ouvir</button>
                    <button class="botao">Saiba mais</button>
                </div>
            </div>
        </div>
        <div class="carrosel-filmes">
            <div class="owl-carousel owl-theme">
                <div class="item">
                    <img class="box-filme" src="/img/PF_animals.03.jpg" alt="" >
                </div>
                <div class="item">
                    <img class="box-filme" src="/img/PF_Delicate Sound of Thunder.07.jpg" alt="" >
                </div>
                <div class="item">
                    <img class="box-filme" src="/img/PF_medle.06.jpg" alt="" >
                </div>
                <div class="item">
                    <img class="box-filme" src="/img/PF_pulse.02.jpg" alt="" >
                </div>
                <div class="item">
                    <img class="box-filme" src="/img/PF_the dark side.04.jpg" alt="" >
                </div>
                <div class="item">
                    <img class="box-filme" src="/img/PF_the division bell.05.jpg" alt="" >
                </div>
                <div class="item">
                    <img class="box-filme" src="/img/PF_The Piper at the Gates of Dawn.08.jpg" alt="" >
                </div>
                <div class="item">
                    <img class="box-filme" src="/img/PF_the wall.01.jpg" alt="" >
                </div>
            </div>
        </div>
    </main>
    <script src="/js/owl/jquery.min.js"></script>
    <script src="/js/owl/owl.carousel.min.js"></script>
    <script src="/js/owl/setup.js"></script>

</body>
<footer>
    <div class="container-footer">
        <ul class="lista-footer">
            <li class="item-footer"><img class="social-footer" src="/img/PF_assinatura.png" alt="isntagran"></li>
        </ul>
    </div>
</footer>
</html>
