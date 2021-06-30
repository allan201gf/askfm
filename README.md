# AskME - Perguntas e Respostas

Sistema desenvolvido utilizando HTML, CSS MySQL e node.js utilizando os seguintes pacotes:

- Express;
- Body-Parser;
- EJS;
- MySQL12;
- Nodemon;
- Sequelize.



Para utilizar o sistema é necessário criar um arquivo chamado database/database.js com o seguinte código para configurar a conexão com o banco de dados MySQL:

`const Sequelize = require("sequelize");`

`const connection = **new** Sequelize('guiaperguntas','nome-de-usuario','senha',{`

  `host: 'localhost',`

  `dialect: 'mysql'`

`});`

`*module*.*exports* = connection;`

