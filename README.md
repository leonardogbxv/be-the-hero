## Be The Hero Project 🦸‍♂️

<h4 align="center">
<img src="mobile/src/assets/logo@3x.png" width="250px" />
</h4>

> An Application that will connect people who want to help NGOs in a monetary way, raising funds for their causes.

Aplicação que conectará pessoas que tem vontade de ajudar, de uma forma monetária, ONGs em necessidade.

Esse foi o tema do projeto da Semana Omnistack 11.0

## Tecnologias 💻
- [Node.js](https://nodejs.org/en/) / [Express](https://expressjs.com/) - Back-end
- [React](https://reactjs.org/) - Front-end
- [React Native](https://reactnative.dev/) - Mobile

## Instalação 🔧
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

Abrirá uma página web no ```localhost:19002``` com o QRCode da aplicação.

Tenha instalado o Expo no seu celular para poder acessa-lo via QRCode gerado.

_______
📍*Nota: Necessário colocar seu endereço de IP em ```...\be-the-hero\mobile\src\services\api.js``` como mostra no código abaixo:*
```javascript
const api = axios.create({
    //baseURL: 'COLOCAR ENDEREÇO DE IP AQUI'
});
```
(Isto somente para o mobile).
_______

## Progresso 🎢

- [x] Back-end
- [x] Front-end
- [x] Mobile

Algumas [anotações](https://www.notion.so/Semana-Omnistack-11-0-5cf854fa329348b0a7ab59c82550adef) que fiz durante o projeto < 📃 

**&copy; [Rocketseat](https://rocketseat.com.br/)** 🚀

**Instructor: [Diego Fernandes](https://github.com/diego3g)** 
