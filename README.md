[style.css](https://github.com/user-attachments/files/33385095/style.css)# Apollo-Ciencias-com-astronomia-e-tecnologia
[index.html](https://github.com/user-attachments/files/33385092/index.html)
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>APOLLO: Astronomia & Ciências com Tecnologia</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header class="MEUCABEÇALHO">

        <div class="logo">

            <div class="simbolo"></div>

            <div>
                <h1>APOLLO</h1>
                <p>Astronomia & Ciências com Tecnologia</p>
            </div>

        </div>

        <nav>
            <a href="#inicio">Inicio</a>
            <a href="#sobre">Sobre</a>
            <a href="#areas">Áreas</a>
            <a href="#video">Vídeo</a>
            <a href="#contato">Contato</a>
        </nav>

        <div class="icones">
            <span>⌕</span>
            <span>♙</span>
        </div>

    </header>


    <section class="hero" id="inicio">

        <div class="text-hero">

            <p class="subtitulo-hero">
                Explorando o universo
            </p>

            <h1>
                Apollo: Astronomia &
                <br>
                <span>Ciências com Tecnologia</span>
            </h1>

            <h3>
                Informação, descobertas e conhecimento em um só lugar
            </h3>

            <p>
                A astronomia une ciência e tecnologia para explorar o universo
                além da visão humana, utilizando telescópios espaciais,
                supercomputadores e inteligência artificial.
            </p>

            <button>
                Comece a explorar ➝
            </button>

        </div>

    </section>


    <img class="astronauta"
         src="astronauta jpg.jpeg"
         alt="Astronauta no espaço">


    <section id="sobre" class="conteudo">

        <h2>Sobre a Astronomia</h2>

        <p>
        A astronomia é a ciência que investiga o cosmos, decifrando a vida das estrelas, a dança dos planetas e a origem do próprio universo. Hoje, essa busca pelo desconhecido é totalmente impulsionada pela tecnologia avançada. Supercomputadores processam volumes gigantescos de dados cósmicos e utilizam inteligência artificial para descobrir novos exoplanetas em segundos, enquanto telescópios espaciais de última geração, como o James Webb, capturam a luz de galáxias formadas há bilhões de anos através de sensores infravermelhos. Ao mesmo tempo, robôs autônomos exploram o solo de Marte enviando análises químicas em tempo real. Mais do que entender o céu, essa parceria entre ciência e inovação transforma a nossa vida na Terra, gerando tecnologias que usamos diariamente, desde os sensores das câmeras dos nossos smartphones e sistemas complexos de navegação por GPS, até melhorias em painéis de energia solar e purificadores de água. Essa evolução constante na fronteira do conhecimento abre portas para o desenvolvimento da computação quântica e da criptografia moderna, impulsionadas pela necessidade de proteger e transmitir dados entre planetas. Além disso, os algoritmos criados para limpar o ruído visual das imagens de galáxias distantes já são aplicados na medicina para identificar tumores em exames de tomografia com muito mais precisão, provando que decifrar o espaço não apenas expande as fronteiras da mente humana, mas salva vidas e molda o futuro da humanidade.


    </p>

    </section>

    <section id="areas" class="conteudo">

        <h2>Áreas da Astronomia</h2>

        <ul>
            <li>Exploração espacial</li>
            <li>Estudo dos planetas</li>
            <li>Observação das estrelas</li>
            <li>Pesquisa sobre galáxias</li>
            <li>Tecnologia espacial</li>
        </ul>

        <p>
            Para conhecer mais sobre astronomia, acesse:

            <a href="https://science.nasa.gov/" target="_blank">
                NASA Science
            </a>
        </p>

    </section>


    <section class="tabela">

        <h2>Objetos do Espaço</h2>

        <table>

            <tr>
                <th>Objeto</th>
                <th>Descrição</th>
                <th>Exemplo</th>
            </tr>

            <tr>
                <td>Planeta</td>
                <td>Corpo que orbita uma estrela</td>
                <td>Terra</td>
            </tr>

            <tr>
                <td>Estrela</td>
                <td>Corpo que produz luz e calor</td>
                <td>Sol</td>
            </tr>

            <tr>
                <td>Galáxia</td>
                <td>Conjunto de estrelas, gases e poeira</td>
                <td>Via Láctea</td>
            </tr>

            <tr>
                <td>Lua</td>
                <td>Satélite natural de um planeta</td>
                <td>Lua da Terra</td>
            </tr>

        </table>

    </section>


    <section id="video" class="video">

        <h2>Vídeo sobre o Universo</h2>

        <iframe
            src="https://www.youtube.com/embed/86YLFOog4GM"
            title="Vídeo sobre o universo"
            allowfullscreen>
        </iframe>

        <p>
            Vídeo relacionado ao tema do projeto, apresentando informações
            e imagens sobre o espaço e o universo.
        </p>

    </section>


    <section id="contato" class="formulario">

        <h2>Entre em Contato</h2>

        <form>

            <label>Nome:</label>
            <input type="text" placeholder="Digite seu nome">

            <label>E-mail:</label>
            <input type="email" placeholder="Digite seu e-mail">

            <label>Número de telefone:</label>
            <input  type="numero de telefone"placeholder="(99)99999-9999">

            <label>Assunto:</label>
            <input type="text" placeholder="Digite o assunto">
          
            <textarea rows="5"
                placeholder="Digite sua mensagem"></textarea>
            



            <button type="submit">
                Enviar
            </button>

        </form>

    </section>


    <footer>

        <p>
            Projeto APOLLO - Astronomia & Ciências com Tecnologia
        </p>

        <p>
            Desenvolvido por Camili - Projeto acadêmico
        </p>

    </footer>

</body>

</html>



[Uploading style.body {
    margin: 0;
    background-color: #020817;
    color: white;
    font-family: Arial, sans-serif;
}

.MEUCABEÇALHO {
    background-color: #011649;
    height: 80px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 40px;
}

.logo {
    display: flex;
    align-items: center;
}

.simbolo {
    width: 30px;
    height: 30px;
    border: 2px solid white;
    border-radius: 50%;
    margin-right: 10px;
}

.logo h1 {
    color: white;
    margin: 0;
}

.logo p {
    color: gray;
    margin: 0;
    font-size: 12px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 10px;
}

nav a:hover {
    color: purple;
}

.icones span {
    color: #9183ff;
    font-size: 20px;
    margin: 5px;
}

.hero {
    padding: 60px;
    height: 400px;
}

.text-hero {
    width: 500px;
    margin-left: 20px;
}

.subtitulo-hero {
    color: #9183ff;
    font-size: 18px;
}

.text-hero h1 {
    color: white;
    font-size: 38px;
}

.text-hero h1 span {
    color: #5353ee;
}

.text-hero h3 {
    color: white;
}

.text-hero p {
    color: white;
    line-height: 1.5;
}

button {
    background-color: purple;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 20px;
}

button:hover {
    background-color: #9183ff;
}

.astronauta {
    width: 45%;
    height: 450px;
    object-fit: cover;
    position: absolute;
    right: 0;
    top: 81px;
     mask-image: linear-gradient(TO right, transparent, black 25%);

}

.img{
    mask-image: linear-gradient(to right, transparent, black 30%);
}

.conteudo {
    padding: 30px 60px;
}

h2 {
    color: #9183ff;
}

ul {
    line-height: 2;
}

a {
    color: #9183ff;
}

.tabela {
    padding: 30px 60px;
}

table {
    width: 100%;
    border-collapse: collapse;
}

th, td {
    border: 1px solid white;
    padding: 10px;
}

th {
    background-color: #171c45;
}

.video {
    padding: 30px 60px;
}

.video iframe {
    width: 600px;
    height: 350px;
}

.formulario {
    padding: 30px 60px;

}

.formulario input{
    display: block;
    width: 400px;
    padding: 10px;
    margin: 5px 0 15px;}

.formulario input {
    display: block;
    width: 400px;
    padding: 10px;
    margin: 5px 0 15px;
}



.formulario textarea {
    display: block;
    width: 400px;
    padding: 10px;
    margin: 5px 0 15px;
}

footer {
    background-color: #011649;
    text-align: center;
    padding: 20px;
    margin-top: 30px;
}css…]()

[settings.json](https://github.com/user-attachments/files/33385504/settings.json)
{
    "liveServer.settings.port": 5501
}
