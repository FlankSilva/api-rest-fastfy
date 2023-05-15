## 💻 Sobre o projeto

API-REST contruida a partir do framework Fastify Node, exemplificando um projeto backend com requisições HTTP.

A plicação foi criada usando o typeScript e SQLite3, permitindo o teste com banco de dados local.

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Node.js] [https://nodejs.org/en/]
- [Fastify] [https://www.fastify.io/]
- [TypeScript] [https://www.typescriptlang.org/]
- [KnexJS] [https://knexjs.org/]


## 🚀 Como executar o projeto

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js][nodejs]. 
Além disto é bom ter um editor para trabalhar com o código como [VSCode][vscode]


### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone https://github.com/FlankSilva/api-rest-fastfy

# Instale as dependências
$ node install

# Criando as tabelas do banco
$ npm run knex -- migrate:latest

# Execute a aplicação em modo de desenvolvimento
$ node run dev

# O servidor inciará na porta:3333 - acesse http://localhost:3333 
```

### 🎲 Executar os testes
```bash
$ npm test

```