# Projeto @Devquest - Landing Page usando Grid e Flexbox


#### Projeto de Landing Page utilizando Grid e Flexbox.

## Índice

- [Capturas de telas](#capturas-de-telas)
- [Links](#links)
- [Construído com](#construído-com)
- [O que aprendi](#o-que-aprendi)
- [Desenvolvimento contínuo](#desenvolvimento-contínuo)
- [Recursos úteis](#recursos-úteis)
- [Luis Fernando Guimaraes](#autor)

### Capturas de telas

#### Tela Desktop

<img src="./src/images/desktop.gif" alt="Tela desktop exibindo funcionalidades">

#### Tela Ipad

<img src="./src/images/ipad.gif" alt="Tela tablet exibindo funcionalidades">

#### Tela Mobile

<img src="./src/images/mobile.gif" alt="Exibindo responsividade no mobile">

### Links

- Site URL: https://luis92guimaraes.github.io/landing-page-grid-flex/

### Construído com

<div style="display: inline_block"><br>
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">     
</div>

### O que aprendi

Esse projeto foi proposto dentro do curso Desenvolvedor Fullstack Devquest da @Devemdobro, projeto do modulo avançado de CSS. É um exemplo de site Landing Page onde tive oportunidade de estar aprimorando os conhecimentos que adquiri até aqui. Foi um ótimo projeto para estar ampliando meus conhecimentos para deixar o meu código cada vez mais limpo e completo. 

## Trechos de códigos

```
.hero {
    grid-area: hero;
    height: 89vh;
    background: url('../images/lemons.jpg') center center no-repeat;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
}

.hero h2 {
    font-weight: 500;
    text-transform: uppercase;
    font-size: 4rem;
}

.hero:after {
    content: url(../images/seta_preta.png);
    position: absolute;
    height: 35px;
    bottom: 40px;
    animation: downarrow 0.6s infinite alternate ease-in-out;
}

@-webkit-keyframes downarrow {
    0% { -webkit-transform: translateY(0); opacity: 0.4;}
    100% { -webkit-transform: translateY(0.4em); opacity: 0.9;}
}

```

### Desenvolvimento contínuo

Pretendo continuar buscando  conhecimento e evolução sobre as ferramentas utilizadas nesse projeto, ainda tem muita coisa pra ser absorvida mas sigo aprendendo e feliz em estar conseguindo realizar projetos como esse com mais clareza e confiança a cada dia de estudos.

### Recursos úteis

- [Mdn](https://developer.mozilla.org/en-US/) - O Mozilla Developer Network (MDN) desempenha um papel crucial ao fornecer recursos abrangentes e atualizados para desenvolvedores web em todo o mundo.
- [W3School](https://www.w3schools.com/css/default.asp) - Esse site sempre me ajuda a resolver qualquer problema relacionados a códigos de uma maneira fácil e muito rápida.
- [Dev em Dobro](https://www.youtube.com/@DevemDobro) - Este é um canal onde encontro muito material. Tem muito conteúdo relacionado ao desenvolvimento. Recomendo a todos que querem aprender sobre esse e outros conceitos relacionados.

## Autor

[Luis Fernando Guimarães](https://www.linkedin.com/in/luisfguimaraes/)