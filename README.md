
<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/joseaugustodardengo/Ecoleta">

  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/joseaugustodardengo/Ecoleta">  
 
</p>
<h1 align="center">
    <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/banner.png" />
</h1>

<h4 align="center"> 
	🚧  Ecoleta ♻️ Concluído 🚀 🚧
</h4>

<p align="center">
 <a href="#funcionalidades">Funcionalidades</a> •
 <a href="#-layout">Layout</a> • 
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#autor">Autor</a>  
</p>


## 💻 Sobre o projeto

♻️ Ecoleta - é uma forma de conectar empresas e entidades de coleta de resíduos orgânicos e inorgânicos as pessoas que precisam descartar seus resíduos de maneira ecológica.


Projeto desenvolvido durante a **NLW - Next Level Week** oferecida pela [Rocketseat](https://blog.rocketseat.com.br/primeira-next-level-week/).
---

## ⚙️ Funcionalidades

- [x] Empresas ou entidades podem se cadastrar na plataforma web enviando:
  - [x] uma imagem do ponto de coleta
  - [x] nome da entidade, email e whatsapp
  - [x] e o endereço para que ele possa aparecer no mapa
  - [x] além de selecionar um ou mais ítens de coleta: 
    - lâmpadas
    - pilhas e baterias
    - papéis e papelão
    - resíduos eletrônicos
    - resíduos orgânicos
    - óleo de cozinha

- [x] Os usuários tem acesso ao aplicativo móvel, onde podem:
  - [x] navegar pelo mapa para ver as instituições cadastradas
  - [x] entrar em contato com a entidade através do E-mail ou do WhatsApp

---

## 🎨 Layout

### Mobile

<p align="center">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/home-mobile.png" width="200px">

  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/detalhes-mobile.svg" width="200px">
</p>

### Web

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/web.svg" width="400px">  
</p>
<a href="https://www.loom.com/share/be19d7224e24445788b29e07812a9cc1">Link do vídeo da parte web </a>

---

## 🚀 Como executar o projeto

Este projeto é divido em três partes:
1. Backend (pasta server) 
2. Frontend (pasta web)
3. Mobile (pasta mobile)

💡Tanto o Frontend quanto o Mobile precisam que o Backend esteja sendo executado para funcionar.


### Pré Requisitos
Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/) <br/>
Após ter feito a configuração de instalação na máquina é necessário fazer o download do repostiório [aqui](https://github.com/joseaugustodardengo/Ecoleta/archive/master.zip)
ou realizar o clone do repositório.
```
git clone https://github.com/joseaugustodardengo/Ecoleta
```
Após feito o download, só seguir os passos a seguir no terminal do seu sistema operacional, para conseguir executar os serviços da aplicação.

#### 🎲 Rodando o Backend (servidor)

```bash

# Acesse a pasta do projeto no terminal/cmd
$ cd Ecoleta

# Vá para a pasta server
$ cd backend

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run dev

# Criar o Banco de dados
$ npm knex:migrate

# O servidor inciará na porta:3333 - acesse http://localhost:3333 

```

#### 🧭 Rodando a aplicação web (Frontend)
OBS: para realizar os seguintes comandos, o servidor tem que estar em execução

```bash

# Acesse a pasta do projeto no seu terminal/cmd
$ cd Ecoleta

# Vá para a pasta da aplicação Front End
$ cd web

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000
```

### 🧭 Aplicação mobile (Mobile)
Caso deseja executar o mobile, é necessário ter instalado o [expo](https://expo.io/) em um sua máquina.
OBS 1: para realizar os seguintes comandos, o servidor tem que estar em execução

```bash
# Acesse a pasta do projeto no seu terminal/cmd
$ cd Ecoleta

# Vá para a pasta da aplicação Mobile
$ cd mobile

# Instale as dependências
$ npm install

# Alterando a configuração do arquivo api.ts, dentro do caminho: <src/services>. Será necessário colocar na linha a seguir o IP do seu computador
$ baseURL: 'http://ip-do-computador:3333'

# Execute a aplicação em modo de desenvolvimento
$ npm run start
```

---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

#### **Website**  ([React](https://reactjs.org/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[React Router Dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)**
-   **[React Icons](https://react-icons.github.io/react-icons/)**
-   **[Axios](https://github.com/axios/axios)**
-   **[Leaflet](https://react-leaflet.js.org/en/)**
-   **[React Leaflet](https://react-leaflet.js.org/)**
-   **[React Dropzone](https://github.com/react-dropzone/react-dropzone)**

> Veja o arquivo  [package.json](https://github.com/joseaugustodardengo/Ecoleta/blob/master/web/package.json)

#### **Backend**  ([NodeJS](https://nodejs.org/en/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Express](https://expressjs.com/)**
-   **[CORS](https://expressjs.com/en/resources/middleware/cors.html)**
-   **[KnexJS](http://knexjs.org/)**
-   **[SQLite](https://github.com/mapbox/node-sqlite3)**
-   **[ts-node](https://github.com/TypeStrong/ts-node)**
-   **[dotENV](https://github.com/motdotla/dotenv)**
-   **[Multer](https://github.com/expressjs/multer)**
-   **[Celebrate](https://github.com/arb/celebrate)**
-   **[Joi](https://github.com/hapijs/joi)**

> Veja o arquivo  [package.json](https://github.com/joseaugustodardengo/Ecoleta/blob/master/backend/package.json)

#### **Mobile**  ([React Native](http://www.reactnative.com/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Expo](https://expo.io/)**
-   **[Expo Google Fonts](https://github.com/expo/google-fonts)**
-   **[React Navigation](https://reactnavigation.org/)**
-   **[React Native Maps](https://github.com/react-native-community/react-native-maps)**
-   **[Expo Constants](https://docs.expo.io/versions/latest/sdk/constants/)**
-   **[React Native SVG](https://github.com/react-native-community/react-native-svg)**
-   **[Axios](https://github.com/axios/axios)**
-   **[Expo Location](https://docs.expo.io/versions/latest/sdk/location/)**
-   **[Expo Mail Composer](https://docs.expo.io/versions/latest/sdk/mail-composer/)**

> Veja o arquivo  [package.json](https://github.com/joseaugustodardengo/Ecoleta/blob/master/mobile/package.json)

### Autor
<img style="border-radius: 50%;" src="https://avatars1.githubusercontent.com/u/60450451?s=460&u=b5f6c306e7760f9d0b89839c5e0b6b105db684a0&v=4" width="100px;" alt=""/>

Feito por **José Augusto Franco Dardengo** <br/>
👋🏽 Entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-José-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/jose-augusto-franco-dardengo/)](https://www.linkedin.com/in/jose-augusto-franco-dardengo/) 
[![Gmail Badge](https://img.shields.io/badge/-jfrancodardengo@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:jfrancodardengo@gmail.com)](mailto:jfrancodardengo@gmail.com)
