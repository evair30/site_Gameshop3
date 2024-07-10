<DOCTYPEHTML>
    <html lang="pt-br">
    <head>
        <meta charsed ="UTF-8">
        <meta http.equiv="X-UA-compatible"content="IE-edge">
        <meta name ="viewport"content="width-device-width,initial-scale=1.0">
        <link rel="stylessheet" href="./main.css">
        <title>Games shop a sua loja de games</title>
        <style>
            *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
h1{
    padding: 16px 0;
    background-color: blue;
    color: white;
}
header  li{
    display: inline;
    margin-left: 16px;
}
header nav li a{
    color:rgb(31, 30, 30) ;
    text-decoration: none;
}
.container{
    max-width: 1280;
    width: 100%;
    margin: 0 auto;
}
header.container,
.section.container{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.brands-list{
    height: 24px;
}
.bands-list li{
    display: inline
    margin right 8px;
}
section.container{
    align-items: flex-start;
}
section{
    padding: 24 0;
}
section h2{
    margin-bottom: 8px;
}
section{
    color: blue;
}
.star-front{
    margin-right: 32px;
}
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,100..700;1,100..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
.boogaloo-regular {
    font-family: "Boogaloo", sans-serif;
    font-weight: 400;
    font-style: normal;
}
header h1,
section h2,
section h3,
.form.butoon,body,input,textarea{
    font-family: "Boogaloo", sans-serif;
}
#ul{
    height: 24px;
}
.container.contact{
    display: block;
}
.contact-metods{
    display: flex;
    justify-content: space-between;
}
.form.input,
form.textarea,
form.button{
    display: block;
    width: 320px;
    margin-bottom: 8px;
    padding: 8px;
}
.form.textarea{
    resize: none;
    height: 180px;
}
.social-links{
    display: inline;
    margin-right: 8px;
}
.social-links li a{
    text-decoration: none;
    
}
section h3{
    margin-bottom: 160x;
}
.form.butoon{
    background-color: blue;
    color:white;
    border:none;
    cursor: pointer;
}
.form.butoon.hover{
    outline-color: rgb(54, 54, 150);
}
input:focus.textarea:focus{
    outline-color: blue;
}
footer{
    background-color: blue;
    color: white;
    padding: 16px;
}
        </style>
    </head>
        <body>
            <header>
                <div class="container">
                <h1>Games shop</h1>
                <nav>
                    <ul>
                        <li>
                            <a href="about">sobre a loja</a>
                        </li>
                    </ul>
                    <ul>
                        <li>
                            <a href="contact">contato</a>
                        </li>
                    </ul>
                </nav></div>
            </header>
            <section id="about">
                <div class="container">
                    <img class="star front" src="./loja.jfif"alt ="faixada da loja"/>
                    <div>
                        <h2>Sobre a loja</h2>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Porro rem fugiat praesentium rerum at, error similique dolorem reprehenderit atque maiores deleniti minima iure dolores corporis molestias ab repudiandae cum. Distinctio.
                        </p>
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut eaque dolorum hic adipisci natus, eligendi harum molestias debitis ex odio est porro excepturi totam quidem sed, expedita magnam perferendis? Quae?
                        </p>
                    </div>
                    <ul class="brands list">
                        <li><img src="./nitendo.jfif" alt="logo nitendo"></li>
                        <li><img src="./xbox.jfif" alt="logo xbox"></li>
                
                <div class="container">
                    <h2>contato</h2>
                    <div class="contact metods">
                        <div>
                            <h3>fale conosco</h3>
                            <form>
                                <input type="text"placeholder="seu nome"required/>
                                <input type="email"placeholder="seu email"required/>
                                <input type="tel"placeholder="seu telefone opicional"/>
                                <textarea placeholder="sua menssagem"required></textarea>
                            </form>
                        </div>
                        <div>
                            <h3>nos acompanhe</h3>
                            <ul class="social links">
                                <li>
                                    <a href="#"title="siga-nos instagram">
                                        <img src="./image/instagram.png" alt="logo instagram">
                                    </a>
                                </li>
                                <li>
                                    <a href="#"title="siga-nos facebook">
                                        <img src="./image/facebook.png" alt="logo facebook">
                                    </a>
                                </li>
                                <li>
                                    <a href="#"title="visite nosso canal no youtube">
                                        <img src="./image/youtube.png" alt="logo youtube">
                                    </a>
                                </li>
                            </ul>
                        </div>
                        <div>
                            <h3>venha até nós</h3>
                            Rua almirente tamandaré n:140 RJ
                        </div>
                    </div>
                </div>
            </section>
            <footer>
                <div class="container">
                    &copy; Game-shop todos os direitos reservados /2024
                </div>
            </footer>
        </body>
    </hltml>
