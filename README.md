

<h1 align="center">
    <a href="#" alt="">Bandersnatch</a>
</h1>



<h4 align="center">
	🚧   Concluído🚀 🚧
</h4>

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre o projeto](#-sobre-o-projeto)
   * [Funcionalidades](#-funcionalidades)
   * [Layout](#-layout)
     * [Web](#web)
   * [Como executar o projeto](#-como-executar-o-projeto)
     * [Pré-requisitos](#pré-requisitos)
     * [Rodando o Projeto](#user-content--rodando-o-projeto)
   * [Tecnologias](#-tecnologias)
   
<!--te-->


## 💻 Sobre o projeto

Projeto desenvolvido durante a semana [js-expert](https://javascriptexpert.com.br/) do [Erick Wendel](https://cursos.erickwendel.com.br/), com o proposta de recriar a tecnologia usada no [bandersnatch](https://pt.wikipedia.org/wiki/Black_Mirror:_Bandersnatch) da netflix com node e javascript

---

## ⚙️ Funcionalidades

- [x] Entender como a Netflix desenvolveu o filme Black Mirror: Bandersnatch.
- [x] Como criar um player de vídeo moderno e customizado usando video.js com base no Layout da Netflix.
- [x] Como ler pedaços de vídeo sob demanda de acordo com a escolha do usuário.
- [x] Como usar codecs compatíveis com a maioria dos browsers.
- [x] Como funciona um arquivo MP4, entendendo durações e resoluções.
- [x] Como conceitos e práticas avançadas sobre a linguagem Javascript.
- [x] Como armazenar vídeos de forma inteligente com Content Delivery Networks (CDNs).
- [x] Vai conhecer as APIs do browser para manipulação de vídeo como Media Source.
- [x] Vai conhecer as principais limitações do Browser para streaming de video adaptativo.
- [x] Vai entender como é a troca de informações entre cliente e servidor para entrega de arquivos pesados.

---

## 🎨 Layout

O layout da aplicação:

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="js-bandersnatch" title="#js-bandersnatch" src="./aula03/assets/prints/titulos.png" width="400px">
</p>

##### Créditos

- Layout da lista foi baseada no  codepen do [Carlos Avila
](https://codepen.io/cb2307/pen/XYxyeY)
- Layout do video foi baseado no codepen do [Benjamin Pott](https://codepen.io/benjipott/pen/JELELN)
---

## 🚀 Como executar o projeto

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node ver:^10](https://nodejs.org/en/), [FFMPEG & FFProbe](https://ffmpeg.org/ffmpeg.html), [MP4Box](https://github.com/gpac/gpac/wiki/MP4Box)
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

#### 🎲 Rodando o projeto

```bash
# Clone este repositório
$ git clone git@github.com:leandrojsantos/js-bandersnatch.git

# Acesse a pasta do projeto no terminal/cmd
$ cd js-bandersnatch

# Vá para a pasta server
$ cd js-bandersnatch/aula03

# Instale as dependências
$ npm install

# Em um terminal, execute a aplicação em modo de desenvolvimento
$ npm run dev

# Em outro terminal
$ npm run assets

# O servidor inciará na porta:8080
# http://localhost:8080

```
---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

* [Node.js](https://nodejs.org/)
* [FFMPEG & FFProbe](https://ffmpeg.org/ffmpeg.html)
* [MP4Box](https://github.com/gpac/gpac/wiki/MP4Box)

✅  LINKS

* Netflix JavaScript Talks - Making Bandersnatch: http://bit.ly/netflix-bandersnatch-talk
* Netflix Open Connect: https://openconnect.netflix.com/
* Youtube Streaming best practices: https://support.google.com/youtube/an...
* Browser Codec Compatibility: https://gist.github.com/Vestride/278e...
* W3C Media Source Extensions™: https://www.w3.org/TR/media-source/
* Media Source Compatibility: https://caniuse.com/mediasource
* MP4 Fragments: https://stackoverflow.com/questions/3...
* Shaka Player: https://v1-6-2.shaka-player-demo.apps... 
* Video Demo Shaka Player: https://www.youtube.com/watch?v=CPFE3...
* Serverless components: https://www.serverless.com/components/
