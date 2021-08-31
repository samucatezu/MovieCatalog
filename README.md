# Catálogo de filmes 

Esse curso foi feito para a plataforma [Digital Innovation One](https://digitalinnovation.one/)

O curso consiste em um sistema de filmes, com a possibilidade de cadastros, edições, listagem e visualização dos filmes.

## Screenshots

<img src="https://user-images.githubusercontent.com/86020448/131425234-81290d69-6dc1-4605-b21a-70bc99c987c9.png" width="400"/> 
<img src="https://user-images.githubusercontent.com/86020448/131425387-b16bb594-4634-4044-b51c-c71d1d1342db.png" width="400"/>
<img src="https://user-images.githubusercontent.com/86020448/131426651-1f15be6b-09d0-4b48-8d43-e5042faba9e2.png" width="400"/>


## Recursos e linguagens utilizadas

 - principíos [S.O.L.I.D](https://www.bmc.com/blogs/solid-design-principles/#:~:text=SOLID%20is%20a%20popular%20set,principle%2C%20and%20dependency%20inversion%20principle.)

 - Clean Code

 - JSON Server

 - Angular

 - HTML & CSS

<p align="left"> <a href="https://angular.io" target="_blank"> <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="angular" width="40" height="40"/>  </a> <a href="https://www.w3schools.com/css/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/>

## Vídeos e imagens da aplicação

![Retorno da realização do cadastro](/AngularAdvanced\ReadMe\RetornoModal.png?raw=true)

## Instalação

1. clone o repositório 
2. Entre no projeto e instale as dependencias `npm install`

## Ambiente Local

Execute `ng serve` para que o projeto suba localmente. Acesse a url `http://localhost:4200/`. O projeto já está com reload automático conforme as alterações que você realizar no código

## Simulando o Back-end

Execute `npm install -g json-server` para instalar globalmente o servidor json. Após a instalação entre na pasta do projeto e execute `json-server --watch db.json`, com isso um servidor será inicializado na url `http://localhost:3000/`, após a inicialização sera possível realizar requisições http.

## Gerendo componente

Execute `ng generate component nome-do-componente` para criar um novo componente. Você também pode usuar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Execute `ng build` para gerar o compilado do projeto. O projeto vai ser criado dentro do diretório `dist/`. Adicionar `--prod` junto comando de build para gerar minificado e pronto para o ambiente de produção.

