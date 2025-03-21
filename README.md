# Código Feminino : Era Digital
css 

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

 body {
    background: linear-gradient(to top, #9c3573, #b3558d);

    color: #ffffff;
    text-align: center;
    overflow-x: hidden;
}

header{
    background: #9c3573;
}

.navbar {
    display: flex;
    justify-content: space-between;
    padding: 20px 50px;
    background: transparent;
}

.navbar ul {
    list-style: none;
    display: flex;
}

.navbar ul li {
    margin: 0 15px;
}

.navbar ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

/* Faz as imagens do carrossel ocuparem toda a área do carrossel */
.carousel-item img {
    width: 100%;
    height: auto;
    object-fit: cover; /* Garante que a imagem ocupe toda a área sem distorção */
}

/* Estiliza a legenda do carrossel */
.carousel-caption {
    background-color: rgba(0, 0, 0, 0.5); /* Fundo escuro semitransparente para legibilidade */
    color: #fff;
    bottom: 20px; /* Ajusta a posição vertical da legenda */
    padding: 10px;
    border-radius: 8px;
}

.hero-section {
    background-image: url('landing page/Imagens/capa.png'); /* Substitua pelo caminho correto da sua imagem */
    background-size: cover; /* Faz com que a imagem cubra toda a área */
    background-position: center; /* Centraliza a imagem */
    height: 50vh; /* Define a altura da seção */
    padding: 100px 20px; /* Espaçamento interno */
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white; /* Ajusta a cor do texto, se necessário */
}

.hero-section h1 {
    font-size: 50px;
    margin-bottom: 20px;
    line-height: 1.5;
}

.cta-container {
    display: flex;
    justify-content: center; /* Centraliza os botões na página */
    gap: 30px; /* Espaço entre os botões */
}

.cta-btn {
    background-color: #9c3573;
    color: #ffffff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 30px;
    font-size: 20px;
    display: inline-block; /* Garante que os botões sejam exibidos corretamente */
}

.advantages {
    padding: 50px 0;
    background-color: #9c3573;
}

.advantages h2 {
    font-size: 36px;
    margin-bottom: 40px;
}

.advantage-grid {
    display: flex;
    justify-content: center;
    gap: 50px;
}

.advantage-item {
    width: 200px;
    text-align: center;
}

.advantage-item img {
    width: 60px;
    margin-bottom: 20px;
}

.advantage-item h3 {
    font-size: 22px;
    margin-bottom: 10px;
}

.advantage-item p {
    font-size: 16px;
}

.analysis {
    background: #9c3573;
    padding: 100px 20px;

}

.analysis h2 {
    font-size: 36px;
    margin-bottom: 20px;
}

.analysis p {
    font-size: 30px;
    margin-bottom: 20px;
}
.content{
    background: #9c3573;
}
.video-container{
    background: #9c3573;

}

.footer {
    padding: 20px;
    background-color: #b3558d;
}

.footer p {
    font-size: 20px;
    color: #000000;
}
