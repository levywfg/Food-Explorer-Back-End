<h1 align="center" style="text-align: center;">
  <img alt="Logo do Food Explorer" src="./src/assets/favicon.svg" style="vertical-align: middle; margin-right: 10px;">
  Food Explorer
</h1>

> Cardápio para um restaurante digital

<p align="center">
  <a href="#project">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#structure">Estrutura</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologies">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#usage">Utilização</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<h2 id="project"> Projeto</h2>

O projeto Food Explorer consiste no desafio final do programa Explorer da Rocketseat. Trata-se de uma aplicação de cardápio digital para um restaurante fictício.

O back-end do projeto, que lida com a lógica e o armazenamento dos dados, está disponível neste repositório. Já o front-end, responsável pela interface do usuário, está disponível [aqui](https://github.com/madalena-rocha/food-explorer-frontend).

<h2 id="structure">Estrutura</h2>

Neste projeto obtém as tabelas de:

- Usuários
- Favoritos
- Ingredientes dos pratos
- Pratos
- Carrinhos
- Pedidos
- Itens dos carrinhos
- Itens dos pedidos

<h2 id="technologies">Tecnologias usadas</h2>

Este projeto foi desenvolvido com as seguintes tecnologias:
- Node.js
- CORS
- Bcrypt.js
- Dotenv
- JSON Web Token
- Knex.js
- SQLite
- SQLite3
- Multer
- PM2
- Express.js
- express-async-errors

<h2 id="usage">Como usar?</h2>

O back-end do projeto está hospedado no endereço https://food-explorer-backend-oxwh.onrender.com. A aplicação Food Explorer está disponível para uso [aqui](https://food-explorer-frontend-80e47f.netlify.app/).


Você também pode executá-lo em sua máquina localmente. Certifique-se de ter o ``Node.js`` e o ``npm`` instalados antes de prosseguir com as etapas abaixo:

1. Clone o projeto:

```
$ git clone https://github.com/levywfg/Food-Explorer-Back-End
```

2. Acesse a pasta do projeto:

```
$ cd Food-Explorer-Back-End
```

3. Instale as dependências:

```
$ npm install
```

4. Execute as migrações:

```
$ npm run migrate
```

5. Inicie o servidor:

```
$ npm start
```


<h2 id="license">📝 Licença</h2>

Este projeto está sob a licença MIT.

