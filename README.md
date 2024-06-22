<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
html, body {
    margin: 0;
    padding: 0;
    width: 100%;
    height: 100%;
}
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background: linear-gradient(to right, #444444 360px, #fff 360px, #fff calc(100% - 360px), #444444 calc(100% - 360px));
    padding: 0;
    flex-direction: column;
}
.container {
    max-width: 1200px;
    margin: 0 auto;
    background-color: #fff;
    padding: 20px;
    position: relative;
}
header {
    background-color: #444444;
    color: white;
    text-align: center;
    padding: 2em 1em;
    width: 100%;
}
header h1 {
    margin: 0;
    font-size: 2.5em;
}
nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    margin: 1em 0 0 0;
}
nav ul li {
    margin: 0 1em;
}
nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 1.2em;
}
main {
    padding: 2em;
    font-size: 1.2em;
    line-height: 1.5;
}
.foto table {
    width: 100%;
    border-collapse: collapse;
    margin: 2em 0;
}
.foto img {
    max-width: 100%;
    height: auto;
    display: block;
}
.foto td {
    padding: 1em;
    vertical-align: top;
}
.texto {
    font-size: 1.2em;
}
.space1,
.space2 {
    text-align: center;
    padding: 1em;
}
.img-large {
    width: 2000px;
    height: auto;
}
footer {
    background-color: #444444;
    text-align: center;
    padding: 1em 0;
    font-size: 0.9em;
    color: #ffffff;
}
.carousel {
    width: 80%; 
    margin-left: 150%; 
    overflow: hidden;
}
.carousel-slide {
    display: none;
    height: 1000%;
    width: 100%;
    justify-content: center;
    align-items: center; 
}
.carousel-slide img {
    object-fit: cover;
    height: 100%;
    width: 100%;
    justify-content: center;
    align-items: center; 
}
.media {
    margin: 20px 0;
    display: flex;
    justify-content: center;
    align-items: center; 
}
  </style>
</head> 
<body>
    <div class="container">
        <header>
            <h1>João Marquezini (Jão)</h1>
            <nav>
                <ul>
                    <li><a href="https://kauakaw.github.io/friend/inicio.html">Início</a></li>
                    <li><a href="https://jvkij0.github.io/trabalho-do-amigo/amigo.html">Palhaçõ</a></li>
                    <li><a href="https://jvkij0.github.io/trabalho-do-amigo/sala.html">Sala</a></li>
                </ul>
            </nav>
        </header>
            <main>
            <div class="foto">
                <table>
                    <tr>
                        <td><img src="foto boa.PNG" alt="Foto de João Marquezine" class="img-large"></td>
                        <td class="texto">
                            João Marquezine é um adolescente de 15 anos que estuda desenvolvimento de sistemas na Etec Ermelinda. Se destaca pelo seu carisma juntamente com senso de humor questionável.
                        </td>
                    </tr>
                    <br>
                    <br>
                    <br>
                    <br>
                    <tr>
                        <td class="space1"><img src="Coração.jpg" alt="Imagem de coração" class="img-large"></td>
                        <td> João Marqezini se destaca por ser um otimo amigo com diversas qualidades, apesar de seu gosto peculiar e preferencias estranhasa é um amigo que pode ser contado e um otimo ser humano</td>
                        <td class="space2"><img src="amigo.jpg" alt="Imagem de download" class="img-large"></td>
                    </tr>
                    <tr>
                        <td>
                            <div class="carousel">
                                <div class="carousel-slide">
                                  <img src="espreeguiçando.jpg" alt="Imagem 1">
                                </div>
                                <div class="carousel-slide">
                                  <img src="ruga.jpg" alt="Imagem 2">
                                </div>
                                <div class="carousel-slide">
                                  <img src="capuz.jpg" alt="Imagem 3">
                                </div>
                              </div>
                              <br>                                                              
                        </td>
                    </tr>
                </table>
            </div>
            <div class="media">
                <video controls>
                   <source src="Download (1).mp4" type="video/mp4">
               </video>
        </main>
        <footer>
            <p>© 2024. Todos os direitos reservados.</p>
        </footer>
    </div>
<script>
let slideIndex = 0;
showSlides();
function showSlides() {
  let slides = document.getElementsByClassName("carousel-slide");
  for (let i = 0; i < slides.length; i++) {
    slides[i].style.display = "none"; }
    slideIndex++;
  if (slideIndex > slides.length) {
    slideIndex = 1;  }    
    slides[slideIndex - 1].style.display = "block";  
  setTimeout(showSlides, 2000);}
</script>
</body>
</html>
