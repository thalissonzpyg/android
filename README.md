<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Como surgiu o mascote do Android</title>
    <link rel="shortcut icon" href="imagens/favicon.ico" type="image/x-icon">
    <style>
        @font-face {
            font-family: idroid;
            src: url(fontes/idroid.otf);
        }

        body {
            font-family: 'Arial Narrow Bold', sans-serif;
            background-color: rgb(111, 207, 151);
            margin: 0;
            font-size: 22px;
        }

        span {
            color: #195a32;
            font-weight: bold;
        }

        span > a {
            text-decoration: none;
            color: #195a32;
            font-weight: bold;
        }

        header {
            color: white;
            background: linear-gradient(to bottom, #2ba85b 50%, rgba(0, 0, 0, 0.5) 100%);
            height: 300px;
            box-shadow: 1px 1px 10px black;
        }

        header > nav {
            padding: 3px;
            display: block;
            margin-left: 15px;
            margin-top: 60px;
        }

        header > nav > a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            margin-right: 30px;
        }

        header > nav > a:hover {
            text-decoration: underline;
        }

        #tituloprincipal {
            text-align: center;
            margin: 0;
            padding-top: 50px;
            text-shadow: 1px 1px 1px black;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        .tituloprincipal {
            text-align: center;
            padding-top: 25px;
            text-shadow: 1px 1px 1px black;
        }

        main {
            background-color: white;
            width: 60%;
            margin: auto;
            margin-top: 2.4px;
            text-align: justify;
            box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.562);
            border-bottom-left-radius: 20px;
            border-bottom-right-radius: 20px;
        }

        main > section > article > p {
            padding-left: 20px;
            padding-right: 20px;
        }

        main > section > article > h1 {
            padding-left: 20px;
            padding-right: 20px;
        }

        main > section > article > h2 {
            padding-left: 20px;
            padding-right: 20px;
        }

        h1 {
            margin: 0;
        }

        h2 {
            margin: 0;
        }

        main > section > article > h1 {
            font-family: 'idroid';
            font-size: 35px;
            color: #207c43;
            text-shadow: 1px 1px 1px rgb(0, 0, 0);
        }

        main > section > article > h2 {
            font-family: 'idroid';
            font-size: 25px;
            color: #207c43;
            text-shadow: 1px 1px 1px rgb(0, 0, 0);
            background: linear-gradient(to right, #2ba85b50 5%, rgba(255, 255, 255, 0.5) 100%);
        }

        main > section > article > p {
            text-indent: 20px;
        }

        img {
            display: block;
            margin: auto;
        }

        .video {
            margin: 0;
            display: inline-block;
        }

        main > iframe {
            height: 400px;
            width: 900px;
            display: block;
            border-style: solid;
            border-width: 25px;
            border-color: #207c43;
        }

        #aprendamais {
            background-color: rgb(111, 207, 151);
            margin: 30px;
            border-radius: 20px;
            padding-bottom: 20px;
            box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.384);
        }

        div {
            margin-left: 20px;
            display: inline-block;
            width: 400px;
            height: 200px;
            font-size: 20px;
        }

        div > p {
            margin: 0;
        }

        div > p > span {
            color: black;
            text-decoration: underline;
        }

        .aprendamaistitulo {
            color: white;
            background-color: #2ba85b;
            border-top-left-radius: 20px;
            border-top-right-radius: 20px;
            padding: 20px;
            padding-left: 0px;
            font-weight: bold;
        }

        #final {
            padding-bottom: 20px;
        }

        footer {
            background-color: #195a32;
            margin: 0;
            width: 100%;
            height: 50px;
            text-align: center;
            color: white;
        }

        footer > p > span {
            font-weight: 550;
            color: white;
            font-size: 25px;
        }

        footer > p {
            padding-top: 10px;
        }

    </style>
</head>
<body>
    <header>
        <h1 id="tituloprincipal"><strong>CURIOSIDADES DE TECNOLOGIA</strong></h1>
        <p class="tituloprincipal">Tudo aquilo que você sempre quis saber sobre o mundo<br> Tech, em um único lugar.</p>
        <nav>
            <a href="#">Home</a>
            <a href="#">Notícias</a>
            <a href="#">Curiosidades</a>
            <a href="#">Fale Conosco</a>
        </nav>
    </header>
    <main>
        <section id="introducao">
            <article>
                <h1>História do Mascote do Android</h1>
                <p>Provavelmente você sabe que o sistema operacional <span>Android</span>, mantido pelo <span>Google</span> é um dos mais utilizados para dispositivos móveis em todo o mundo. Mas tavez você não saiba que o seu simpático mascote tem um nome e uma história muito curiosa? Pois acompanhe esse artigo para aprender muita coisa sobre esse robozinho.</p>
            </article>
        </section>
        <section id="primeiraversao">
            <article>
                <h2>A primeira versão</h2>
                <p>A primeira tentativa de criar um mascote surgiu em 2007 e veio de um desenvolvedor chamado <span><a href="#">Dan Morrill 🔗</a></span>. Ele conta que abriu o <span><a href="#">Inkscape 🔗</a></span> (software livre para vetorização de imagens) e criou sua própria versão de robô. O objetivo era apenas personificar o sistema apenas para a a sua equipe, não existia nenhuma solicitação da empresa para a criação de um mascote.</p>
                <img src="imagens/dan-droids.png" alt="Primeia versão dos androids chamado Dandroids">
                <p>Essa primeira versão bizarra até foi batizada em homenagem ao seu criador: seriam os <span>Dandroids</span>.</p>
            </article>
        </section>
        <section id="novomascote">
            <article>
                <h2>Surge um novo mascote</h2>
                <p>A ideia de ter um mascote foi amadurecendo e a missão foi passada para uma profissional da área. A ilustradora Russa <span><a href="#">Irina Blok 🔗</a></span>, também funcionária do Google, ficou com a missão de representar o pequeno robô de uma maneira mais agradável.</p>
                <img src="imagens/irina-blok.jpg" alt="Foto da ilustradora Russa Irina Blok">
                <p>A ideia principal da Irina era representar tudo graficamente com poucos traços e de forma mais chapada. O desenho também deveria gerar identificação rápida com quem o olha. Surgiu então o <span>Bugdroid</span>, o novo mascote do Android.</p>
                <img src="imagens/bugdroid.png" alt="Ilustração do Bugdroid">
                <p>A principal inspiração para os traços do novo Bugdroid veio daqueles bonequinhos que ilustram portas de banheiro para indicar o gênero de cada porta. Conta a lenda que a artista estava criando em sua mesa no escritório do Google e olhou para o lado dos banheiros e a identificação foi imediata: simples, limpo, objetivo.</p>
            </article>
        </section>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/l2UDgpLz20M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <section id="aprendamais">
            <article>
                <p class="aprendamaistitulo">Quer aprender mais?</p>
                <p>Outro assunto curioso em relação ao Android é que cada versão sempre foi nomeada em homenagem a um doce, em ordem alfabética a partir da versão 1.5 até a 9.0.</p>

                    <div>
                        <p>✔️ 1.5 - <span>Cupcake</span></p>
                        <p>✔️ 1.6 - <span>Donut</span></p>
                        <p>✔️ 3.0 - <span>Eclair</span></p>
                        <p>✔️ 2.2 - <span>Froyo</span></p>
                        <p>✔️ 2.3 - <span>Gingerbread</span></p>
                        <p>✔️ 3.0 - <span>Honeycomb</span></p>
                        <p>✔️ 4.0 - <span>Ice Cream Sandwich</span></p>
                    </div>
                    <div>
                        <p>✔️ 4.1 - <span>Jelly Bean</span></p>
                        <p>✔️ 4.4 - <span>KitKat</span></p>
                        <p>✔️ 5.0 - <span>Lolipop</span></p>
                        <p>✔️ 6.0 - <span>Marshmallow</span></p>
                        <p>✔️ 7.0 - <span>Nougat</span></p>
                        <p>✔️ 8.0 - <span>Oreo</span></p>
                        <p>✔️ 9.0 - <span>Pie</span></p>
                    </div>
                </ul>
                    <p>Infelizmente, o Android Q não existiu, pois o Google resolveu pôr fim a essa divertida prática e começou a usar numerações, o que deu origem ao Android 10.</p>
                    <p>Acesse aqui o site <span><a href="#">Android History 🔗</a></span> para conhecer a sequência das versões "adocicadas" e o que cada uma trouxe para o sistema Android.</p>
            </article>
        </section>
        <section id="final">
            <article>
                <p>Então é isso! Espero que você tenha gostado do nosso artigo com essa curiosidade sobre o sistema <span>Android</span> e seu simpático mascote.</p>
            </article>
        </section>
    </main>
    <footer>
        <p>Site criado por <span>Thalisson G.</span> para o <span>CursoEmVideo</span></p>
    </footer>
</body>
</html>
