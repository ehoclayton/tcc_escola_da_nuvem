# tcc_escola_da_nuvem

<p align="center">
  <img src="https://o.remove.bg/downloads/07be0ad6-7c62-43da-b7f4-76712c8e05ef/SIMPLEFLOW_LOGO-removebg-preview.png" alt="Logo" width="200" height="200" />
</p>

<h1 align="center"> Trabalho de Conclusão de Curso em Fundamentos de AWS - Promovido pela Escola da Nuvem </h1>

<a id="Sumário"></a>

<p align="center">
  <b> Criando um site Estatico na Nuvem </b></br>
  <sub> Este projeto visa construir um site estatico na nuvem utilizando Amazon S3, CloudFront, Route 53 e AWS Certificate.
  <sub>
</p>


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)

<p align="center">
  <a href="#Introdução"> 🧩 Introdução </a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Resultados"> 🚀 Resultados</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Dependências"> 🧪 Dependências</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Ideias">💡 Possíveis Melhorias </a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Creditos"> 🏆 Créditos </a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>
 
<br/>


### 🚧 PROJETO EM ANDAMENTO 🚧

<br/>

<a id="Introdução"></a>
## 🧩 Introdução 

  ***⠀⠀⠀⠀Bem-vindo a introdução do meu projeto de TCC para Escola da Nuvem - Criando um site Estatico na Nuvem
<br/>


<a id="Resultados"></a>
## 🚀 Resultados 
  > Espero consegui mostrar um pouco do meu conhecimento em nuvem.

<br/> 

## Front-end

<br />   

  ### ***⠀⠀⠀⠀⭐ Ao Executar o programa o usuario vera os campos de seleção e preenchimento, para fazer seu registro de entrada ou saida, e escolher também um categoria, sendo também possivel o registro de novas categorias.

<br />   


⭐ Home Page | ⭐ Agradecimentos | ⭐ Pagina Error | ⭐ Pagina Não Encontrado |
|---|---|---|---|
![image](https://github.com/ehoclayton/tcc_escola_da_nuvem/assets/93559228/dc1a49b0-9c62-40f6-a6fa-d8f6dd03caf5) | ![image](https://github.com/ehoclayton/tcc_escola_da_nuvem/assets/93559228/d710f9b9-79a8-416b-b3b1-477e5485fb0a) | ![image](https://github.com/ehoclayton/tcc_escola_da_nuvem/assets/93559228/ba8aa349-1339-423d-a310-6ddcd7aab516) | ![image](https://github.com/ehoclayton/tcc_escola_da_nuvem/assets/93559228/10c42100-b50d-4815-abad-c4bb3675f1db)
![image](https://github.com/ehoclayton/tcc_escola_da_nuvem/assets/93559228/219c6fb2-39fd-4d0a-9b06-ff67335a2f38)


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)


### 💻 Desktop 
  
 ⭐ Login | ⭐ Registro | ⭐ Feed |
|---|---|---|
![HomePage]() | ![Detalhes]() | ![Detalhes]()


<br/>

## Back-end
>
  
<br/>

### ***⠀⠀⠀⠀⭐ Veja toda a construção do código em detalhes***

  
### 🎯 <head> 
  
### ```Html``` 
```
<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TCC Escola da Nuvem</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css"
    integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
</head>
```
### ```<header>``` 
```<body>
  <header class="header__container">
    <button class="menu-toggle" aria-label="Toggle Menu" onclick="toggleMenu()">&#9776;</button>

        <div class="header__logo">
          <h4>Escola da Nuvem TCC - Grupo 04</h4>
        </div>
        <nav class="header__nav">
            <ul>
                <li><a href="#inicio">Início</a></li>
                <li><a href="#especialistas">Nossos Especialistas</a></li>
                <li><a href="agradecimentos.html">Agradecimentos</a></li>
              </ul>
            </nav>
        </header>
```
### ```<section>``` 
```
        <section id="inicio" class="main__container">
        <main class="main__container">
            <div class="main__content">
                <h2 class="main__title">Conheça o poder da nuvem<br> Faça seu negócio decolar!</h2>
                <p class="main__p">Encontre profissionais qualificados com apenas alguns cliques. Confira nossos currículos
                e monte seu time de sucesso.</p>
            </div>
            <img src="img/gokunuvem.png" alt="Nuvem" class="main__img" width="1200">
        </main>
    </section>
```
### ```<section>``` 
```
     <section id="especialistas" class="section__division__container">
    <h3 class="division__title"> Nossos Especialistas</h3>
    <div class="section__image__container">
      <img class="cv-image" id="cv1-image" src="img/Alexandre_SF.png" alt="alexandre_sf">
      <img class="cv-image" id="cv4-image" src="img/clayton_sf.png" alt="Clayton" style="max-width: 100%;">
      <img class="cv-image" id="cv2-image" src="img/gabriel_sf.png" alt="Gabriel">
      <img class="cv-image" id="cv3-image" src="img/leivy_sf.png" alt="Leivy">
      <img class="cv-image" id="cv5-image" src="img/jorge_sf.png" alt="Jorge">
      <img class="cv-image" id="cv6-image" src="img/thalia_sf.png" alt="Thalia">
      <img class="cv-image" id="cv7-image" src="img/marcos_sf.png" alt="Marcos">

    </div>
    <div class="profile">
        <a href="https://www.linkedin.com/in/alexandre-da-silva-souza-69699924/" target="_blank">
        <p>Alexandre</p></a>
        <a href="https://www.linkedin.com/in/clayton-oliveira-108787143/" target="_blank">
        <p>Clayton</p></a>
        <a href="https://www.linkedin.com/in/gabriel-leonardo-68329919a/" target="_blank">
        <p>Gabriel</p></a>
        <a href="https://www.linkedin.com/in/leivy-bispo-4224b5142/" target="_blank">
        <p>Leivy</p></a>
        <a href="https://www.linkedin.com/in/jorge-costa-04687983/" target="_blank">
        <p>Jorge</p></a>
        <a href="https://www.linkedin.com/in/thalia-oliveira-de-sousa-16a7b0289/" target="_blank">
        <p>Thalia</p></a>
        <a href="#inicio" target="_blank">
        <p>Marcos</p></a>
    </div>

  </section>
```
### ```<section>``` 
```
    <section id="agradecimentos" class="section__container">
    <div class="section__select__container">
      <label for="section__select__text">Visualize o curriculo de cada Especialista:</label>
      <select id="curriculos">
        <option value="curriculos/CV-Alexandre.Souza.pdf">Alexandre Souza</option>
        <option value="curriculos/CV-Clayton.Oliveira.pdf">Clayton Oliveira</option>
        <option value="curriculos/CV-Gabriel.Leonardo.pdf">Gabriel Leonardo</option>
        <option value="curriculos/CV-Leivy.Bispo.pdf">Leivy Bispo</option>
        <option value="curriculos/CV-Jorge.Costa.pdf">Jorge Costa</option>
        <option value="curriculos/CV-Thalia.Sousa.pdf">Thalia Sousa</option>
        <option value="curriculos/CV-Marcos.Andre.pdf">Marcos André</option>
      </select>
      <button id="section__btn" class="pdf-view-button">Visualizar</button>
    </div>

  </section>
```
### ```<footer>``` 
```
    <footer>
    <section id="contato" class="footer">
    <div class="container-footer">
      <div class="row-footer">
        
        <div class="footer-col">
          <h4></h4>
          <ul>
            <li><a target=_blank href="https://escoladanuvem.org/">Escola da Nuvem</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/cursos">Cursos</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/doe">Doe</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/voluntario">Volunatário</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/parcerias">Parcerias</a></li>

            </li>
          </ul>
        </div>
       
        <div class="footer-col">
          <h4></h4>
          <ul>
            <li><a target=_blank href="https://escoladanuvem.org/depoimentos/">Cases</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/sobre-nos/">Sobre</a>
            <li><a target=_blank href="https://escoladanuvem.org/na-midia/">Midia</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/blog/">Blog</a></li>
            <li><a target=_blank href="https://escoladanuvem.org/transparencia/">Transparência</a></li>
          </ul>
        </div>
        
      <div class="footer-col">
        <h4></h4>
        <ul>
          <li><a target=_blank href="https://www.udemy.com/terms/">Termos</a></li>
          <li><a target=_blank href="https://www.udemy.com/terms/privacy/">Política de privacidade</a></li>
          <li><a target=_blank href="https://www.udemy.com/pt/sitemap/">Mapa do Site</a></li>
          <li><a target=_blank href="https://about.udemy.com/pt-br/declaracao-de-acessibilidade-da-udemy/">Declaração de acessibilidade</a></li>
        </ul>
      </div>

      <div class="footer-col">
        <h4>Redes Sociais</h4>
        <div class="medias-socias">
          <a target=_blank href="https://web.facebook.com/EscolaDaNuvemOficial?_rdc=1&_rdr"> <i
              class="fa-brands fa-facebook-f"></i> </a>
          <a target=_blank href="https://www.instagram.com/escola_da_nuvem/"> <i class="fa-brands fa-instagram"></i>
          </a>
          <a target=_blank href="https://www.linkedin.com/company/escola-da-nuvem/"> <i
              class="fa-brands fa-linkedin-in"></i> </a>
          <a target=_blank href="https://escoladanuvem.org/"> <i class="fa-regular fa-at"></i> </a>
        </div>   
    </div>
    </section>
<script src="script.js"></script>
<!-- Adicione este script no seu HTML -->
<script>
    function toggleMenu() {
      var nav = document.querySelector('.header__nav');
      nav.classList.toggle('active');
    }
  
    document.addEventListener("DOMContentLoaded", function () {
      // ... (seu código JavaScript existente)
    });
  </script>
  
</body>
</html>
```
### ```CSS``` 
```
   @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;600&display=swap');

:root {
  --primary-color: #06204250; /* Vermelho */
  --secondary-color: #4CAF50; /* Verde */
  --text-color: #333; /* Preto */
  --text-color2: #fffdfd; /* Preto */
  --background-color: #f4f4f4; /* Cinza claro */
  --hover-color: #FFCE45; /* Amarelo (cor de destaque ao passar o mouse) */
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
    background-image: url('img/aws_dc.jpg');
    background-size: cover; /* Para cobrir todo o elemento body */
    background-repeat: no-repeat;
    background-attachment: fixed; /* Para fixar a imagem no lugar */
    color: #fff; /* Cor do texto */
    height: 100%;
    width: 100%;
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;
}

.header__container {
  background-color: var(--primary-color);
  color: #fff;
  padding: 20px 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.2); /* Sombra suave */
}

.header__logo img {
  width: 100px; /* Ajuste o tamanho conforme necessário */
}

.header__nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
}

.header__nav li {
  margin-right: 20px;
}

.header__nav a {
  text-decoration: none;
  color: #fff;
  font-weight: bold;
  font-size: 16px;
  transition: color 0.3s, background-color 0.3s; /* Transições suaves */
}

.header__nav a:hover {
  color: var(--hover-color); /* Cor de destaque ao passar o mouse */
  background-color: #fff; /* Fundo branco ao passar o mouse */
}

.main__container {
  display: grid;
  grid-auto-flow: column;
  padding: 2rem;
  gap: 5rem;
  align-items: center;
  justify-content: center;
  text-align: justify;
}

.main__img {
  width: 80%;
}

.main__title {
  font-size: 2.5rem;
  color: var(--text-color2);
}

.main__p {
  color: var(--text-color2);
  justify-content: center;
  text-align: justify;
  inline-size: 30rem;
  overflow-wrap: break-word;
  font-size: 1.2rem;
  font-weight: 300;
}

.section__image__container {
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
  margin-top: 1rem;
}

.section__image__container img {
  width: 10%;
  transition: transform 0.3s, filter 0.3s, opacity 0.3s; /* Efeitos suaves */
}

.section__image__container img:hover {
  transform: scale(1.2); /* Aumentar o tamanho ao passar o mouse */
  filter: brightness(120%); /* Aumentar o brilho ao passar o mouse */
  opacity: 0.8; /* Reduzir a opacidade ao passar o mouse */
}
  

.profile a {
    text-decoration: none; /* Remover sublinhado */
    color: #fff; /* Definir a cor do texto como branco */
  }
  
  .profile {
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-wrap: wrap;
    font-size: 1rem;
    text-transform: none;
    font-weight: bold;
    font-weight: 300;
    margin-top: 1rem;
    font-family: 'SuaNovaFonte', sans-serif;
  }
  
  
  
  

.section__division__container {
  background-color: var(--primary-color);
  padding: 1rem;
  text-align: center;
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2); /* Sombra suave */
}

.section__division__container h3 {
  color: #fff;
  font-size: 2rem;
  text-transform: uppercase;
}

.section__container {
  padding: 2rem;
  margin: 2rem;
  display: flex;
  align-items: center;
  justify-content: center;
}

.section__select__container {
  background-color: #0000009d;
  display: flex;
  flex-direction: column;
  align-items: justify;
  gap: 0.5rem;
  width: 50%;
  padding: 2rem;
  border: solid 0.1rem var(--primary-color);
  border-radius: 0.2rem;
  box-shadow: -10px 12px 0px var(--primary-color);
}

#curriculos {
  background-color: var(--white);
  padding: 0.2rem;
  border: solid 0.02rem var(--primary-color);
  border-radius: 0.2rem;
}

#section__btn {
  background-color: var(--primary-color);
  padding: 0.5rem;
  color: #ffffff;
  font-family: 'Poppins', sans-serif;
  font-weight: 300;
  font-size: 1rem;
  border: none;
  border-radius: 0.2rem;
  cursor: pointer;
}

#curriculos {
  font-family: 'Poppins', sans-serif;
  font-size: 1rem;
  font-weight: 300;
  color: #e45757;
}

#section__btn:hover {
  background-color: #FF5252; /* Cor de destaque ao passar o mouse */
  transition: all ease-in-out 0.2s;
}

footer {
  background-color: var(--primary-color);
  padding: 50px 0;
}

.container-footer {
  max-width: 1400px;
  padding: 0 4%;
  margin: auto;
}

.row-footer {
  display: flex;
  flex-wrap: wrap;
}

.footer-col {
  width: 25%;
  padding: 0 15px;
}

.footer-col h4 {
  font-size: 22px;
  color: #fff;
  margin-bottom: 20px;
  font-weight: 600;
  position: relative;
  text-transform: capitalize;
}

.footer-col ul {
  list-style: none;
}

.footer-col ul li {
  margin: 10px 0;
}

.footer-col ul li a {
  font-size: 16px;
  text-transform: capitalize;
  color: #fff;
  text-decoration: none;
  font-weight: 300;
  display: block;
  transition: all 0.3s ease;
}

.footer-col ul li a:hover {
  color: var(--hover-color); /* Cor de destaque ao passar o mouse */
  padding-left: 10px;
}

.footer-col .medias-socias {
  margin-top: 30px;
}

.footer-col .medias-socias a {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  height: 40px;
  width: 40px;
  margin: 0 10px 10px 0;
  text-decoration: none;
  border-radius: 50%;
  color: #fff;
  border: 1px solid #fff;
  transition: all 0.5s ease;
}

.footer-col .medias-socias a i {
  font-size: 20px;
}

.footer-col .medias-socias a:hover {
  color: var(--hover-color); /* Cor de destaque ao passar o mouse */
  background-color: #fff;
}

.footer-col .form-sub input {
  width: 100%;
  padding: 10px;
  font-size: 15px;
  outline: none;
  border: 1px solid #fff;
  color: #fff;
  background-color: var(--background-color);
}

.footer-col .form-sub input::placeholder {
  color: var(--white);
}

.footer-col .form-sub button {
  width: 100%;
  margin-top: 10px;
  padding: 10px;
  font-size: 17px;
  outline: none;
  border: none;
  cursor: pointer;
  color: var(--secondary-color);
  border-radius: 3px;
  font-weight: bold;
  background-color: #fff;
}

.error {
  text-align: center;
}

.cv-image {
    width: 150px; /* Defina a largura desejada */
    height: 150px; /* Defina a altura desejada */
  }

/* Responsivo (você pode ajustar as cores responsivas conforme necessário) */
@media (max-width: 768px) {
  /* Estilos para dispositivos menores */

  .main__container {
    max-width: 90%; /* Reduza a largura máxima para uma melhor legibilidade */
    margin: 0 auto; /* Centralize a seção principal */
  }

  .section__image__container img {
    max-width: 150px; /* Defina a largura máxima desejada */
    height: auto; /* Altura automática para manter proporções originais */
    transition: transform 0.3s, filter 0.3s, opacity 0.3s;
  }
  
  

  .footer-col {
    width: 50%; /* Reduza a largura das colunas no rodapé */
    text-align: center; /* Centralize o conteúdo no rodapé */
  }

  /* Mostre o botão de menu em telas menores */
  .menu-toggle {
    display: block;
  }

  .main__title {
    font-size: 24px; /* Reduza o tamanho da fonte para telas menores */
  }
  
  .main__p {
    font-size: 16px; /* Reduza o tamanho da fonte para telas menores */
    margin-top: 10px; /* Aumente o espaçamento entre o título e o parágrafo */
  }
  
  .main__img {
    width: 100%; /* Faça a imagem ocupar a largura total do contêiner */
    height: auto; /* Mantenha a proporção original da imagem */
  }


/* Estilos para dispositivos de tela menor, como smartphones */
@media (max-width: 768px) {
    /* Estilos para o botão de menu */
    .menu-toggle {
      display: block; /* Mostrar o botão em telas menores */
    }
  
    .header__nav {
      display: none;
      flex-direction: column;
      background-color: #333;
      position: absolute;
      top: 60px;
      left: 0;
      right: 0;
    }
  
    .header__nav.active {
      display: flex;
    }
  
    .header__nav ul {
      padding: 0;
      list-style: none;
    }
  
    .header__nav li {
      padding: 10px;
      text-align: center;
    }
  
    .header__nav a {
      color: #fff;
      text-decoration: none;
    }
  }
  }
  
```
### ```java script``` 
```
    document.addEventListener("DOMContentLoaded", function () {
    // Seleciona o botão, a caixa de seleção e o ícone do menu
    var botao = document.getElementById('section__btn');
    var select = document.getElementById('curriculos');
    var menuIcon = document.querySelector('.menu-icon');
    var headerNav = document.querySelector(".header__nav");

    botao.addEventListener('click', function () {
        console.log('Botão "Visualizar" clicado.'); // Adicione esta linha
        var curriculo = select.value;
    
        // Cria um link para o arquivo correspondente
        var link = document.createElement('a');
        link.href = curriculo;
        link.target = '_blank';
    
        // Clica no link para abrir o currículo em uma nova aba
        link.click();
      });
    // Função para verificar o tamanho da tela e exibir/ocultar o ícone do menu
    function checkScreenWidth() {
      if (window.innerWidth <= 768) {
        menuIcon.style.display = 'block';
      } else {
        menuIcon.style.display = 'none';
        // Se a largura da tela for maior que 768px, oculte o menu responsivo
        headerNav.classList.remove("active");
      }
    }
  
    // Verifique o tamanho da tela quando a página é carregada
    checkScreenWidth();
    });
  
    // Adiciona um ouvinte de redimensionamento para verificar quando a tela muda de tamanho
    window.addEventListener('resize', checkScreenWidth);
  
    // Seletor para todas as imagens com a classe "cv-image"
    var images = document.querySelectorAll(".cv-image");
  
    // Adiciona um manipulador de erro para cada imagem
    images.forEach(function (image) {
      image.addEventListener("error", function () {
        // Redireciona para a página de erro (error.html)
        window.location.href = "error.html";
      });
    });
  
    // Seletor para todos os links com a classe "pdf-link"
    var pdfLinks = document.querySelectorAll(".pdf-link");
  
    // Adiciona um manipulador de clique para cada link
    pdfLinks.forEach(function (link) {
      link.addEventListener("click", function (event) {
        // Verifica se o arquivo PDF não está disponível (erro 404)
        var url = link.getAttribute("href");
        var xhr = new XMLHttpRequest();
        xhr.open("HEAD", url, true);
  
        xhr.onload = function () {
          if (xhr.status === 404) {
            // O arquivo PDF não foi encontrado, redireciona para a página de erro (error.html)
            window.location.href = "error.html";
          } else {
            // O arquivo PDF está disponível, permite que o link continue funcionando
            window.location.href = url;
          }
        };
  
        xhr.send();
  
        // Impede o comportamento padrão do link
        event.preventDefault();
      });
    });
  
    const menuToggle = document.querySelector(".menu-toggle");
    
    menuToggle.addEventListener("click", function () {
      headerNav.classList.toggle("active");
    });
    
    window.addEventListener("resize", function () {
      if (window.innerWidth > 768) { // Altere 768 para a largura desejada para desktop
        headerNav.classList.remove("active");
      }
    });
```

<a href="#Sumário"> 📖 Volta ao Sumário </a>

<br /> 

<a id="Dependências"></a>
## 🧪 Dependências
> Requisitos para rodar o codigo...

<br/>

## `📖 Instalação` 
  
 <br /> 

> Caso tenha Git basta da git clone, caso não tenha baixe o projeto completo em dowlon

```BASH
git clone https://github.com/ehoclayton/FluxoDeCaixa_Control
```

<br /> 

> Caso já tenha o Node em sua maquina basta instalar o projeto com npm i

```BASH
npm i 
```

<br /> 


<a href="#Sumário"> 📖 Volta ao Sumário </a>

<br /> 

<a id="Ideias"></a>
## 💡 Possíveis Melhoras
> Possíveis melhorias no código e no projeto, caso queira voltar e melhorá lo.

<br /> 

- [ ] ***- Testa todo o código.*** 
- [ ] ***- Pesquisar o perfil com nome*** 
- [ ] ***- *** 
- [x] ***- *** 

<br/>

<a href="#Sumário"> 📖 Volta ao Sumário </a>

<br /> 

<a id="Creditos"></a>
## 🏆 Créditos
> Todo o projeto foi feito por...
  
<br /> 

<div > 

| [<img src="" width=300><br><sub> Clayton Oliveira </sub>](https://www.linkedin.com/in/clayton-fausto-oliveira-108787143/) | ***Hello 😃 Se você chegou até aqui, acredito que gostou do meu projeto, nesse caso temos algo em comum, sendo assim que tal conversamos um pouco? Meu chama no linkedin 😁*** | 
|---|---|

</div> 
  
<br /> 
