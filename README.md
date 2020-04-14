# Semana OmniStack 11.0

## Be The Hero Project 

> An Application that will connect people who want to help NGOs in a monetary way, raising funds for their causes.

Esse foi o tema do projeto da Semana Omnistack 11.0

## Tecnologias 
- [Node.js](https://nodejs.org/en/) / [Express](https://expressjs.com/) - Back-end
- [React](https://reactjs.org/) - Front-end
- [React Native](https://reactnative.dev/) - Mobile

## Instalação
Primeiramente, clone o projeto e instale suas dependências:

```
$ git clone https://github.com/leonardogbxv/be-the-hero
$ cd be-the-hero
$ npm install
```

### Rodando o back-end:

```
$ cd backend
$ npm install
$ npm start
```

Iniciará servidor node no ```localhost/3333```.

### Rodando o front-end:

```
$ cd front-end
$ npm install
$ npm start
```

Iniciará o projeto no ```localhost/3000```.

### Rodando mobile:

```
$ cd mobile
$ npm install
$ npm start
```

Abrirá uma página web no ```localhost:19002``` com o QRCode da aplicação

Tenha instalado o Expo no seu celular para poder acessa-lo via QRCode gerado.

> Nota: Coloque seu endereço de IP no arquivo api.js (...\be-the-hero\mobile\src\services\api.js) como mostra no código abaixo:
```javascript
const api = axios.create({
    //baseURL: 'COLOCAR ENDEREÇO DE IP AQUI'
});
```

## Progresso 

- [x] Back-end
- [x] Front-end
- [x] Mobile

**&copy; [Rocketseat](https://rocketseat.com.br/)**

**Instructor: [Diego Fernandes](https://github.com/diego3g)**