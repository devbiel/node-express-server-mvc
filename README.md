# 🚀 Servidor Node.js + Express & MongoDB

Este repositório contém uma aplicação Backend desenvolvida em **Node.js** utilizando o framework **Express** e o ORM **Mongoose** para integração e persistência de dados no banco **MongoDB Atlas**. Servindo também como um boilerplate para os próximos projetos.

O projeto foi estruturado seguindo o padrão de arquitetura **MVC (Model-View-Controller)**, utilizando o motor de renderização **EJS** para renderizar as visões dinâmicas no lado do servidor.

---

## 🛠️ Tecnologias Utilizadas

- **[Node.js](https://nodejs.org/):** Ambiente de execução JavaScript no servidor.
- **[Express](https://expressjs.com/):** Framework web para gerenciamento de rotas e middlewares.
- **[MongoDB Atlas](https://www.mongodb.com/cloud/atlas):** Banco de dados NoSQL hospedado em nuvem.
- **[Mongoose](https://mongoosejs.com/):** Biblioteca para modelagem de dados do MongoDB.
- **[EJS (Embedded JavaScript templates)](https://ejs.co/):** Engine para renderização de páginas HTML dinâmicas.

---

## 📁 Estrutura do Projeto

```text
.
├── src/
│   ├── controllers/   # Lógica de controle das rotas (HomeController, etc.)
│   ├── models/        # Schemas e regras de negócios (Mongoose)
│   └── views/         # Arquivos de interface renderizados pelo EJS
├── public/            # Arquivos estáticos acessíveis publicamente (CSS, JS, imagens)
├── routes.js          # Definição e mapeamento de rotas HTTP
├── server.js          # Arquivo principal de inicialização do servidor Express
└── package.json       # Dependências e scripts do projeto