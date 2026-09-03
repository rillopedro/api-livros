# 📚 Library API

Uma API RESTful desenvolvida para gerenciamento de uma biblioteca, permitindo controlar **livros, usuários, empréstimos e devoluções** de forma simples, organizada e eficiente.

O projeto foi criado com foco em praticar conceitos de **desenvolvimento Back-end, APIs REST, banco de dados e organização de código**.

---

## ✨ Funcionalidades

A API permite realizar operações como:

* 📖 Cadastrar livros
* 🔎 Consultar livros disponíveis
* ✏️ Atualizar informações dos livros
* 🗑️ Remover livros
* 👤 Cadastrar usuários
* 📋 Consultar usuários
* 📤 Registrar empréstimos
* 📥 Registrar devoluções
* 📅 Controlar datas de empréstimo e devolução
* ✅ Verificar disponibilidade dos livros

---

## 🛠️ Tecnologias utilizadas

Este projeto utiliza tecnologias voltadas ao desenvolvimento Back-end:

* **API REST**
* **JSON**
* **Banco de Dados Relacional**
* **HTTP**
* **Git**
* **GitHub**

---

## 📂 Estrutura do projeto

```bash
library-api/
│
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── services/
│   └── database/
│
├── config/
├── public/
├── README.md
└── .gitignore
```

---

# 🚀 Como executar

## 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/library-api.git
```

## 2. Acesse a pasta

```bash
cd library-api
```

## 3. Configure o banco de dados

Configure as informações necessárias para conexão com o banco de dados utilizado pelo projeto.

## 4. Execute o projeto

Inicie o servidor utilizando o comando correspondente à tecnologia utilizada no projeto.

---

# 🌐 Endpoints

## 📚 Livros

| Método   | Endpoint       | Descrição              |
| -------- | -------------- | ---------------------- |
| `GET`    | `/livros`      | Lista todos os livros  |
| `GET`    | `/livros/{id}` | Busca um livro pelo ID |
| `POST`   | `/livros`      | Cadastra um novo livro |
| `PUT`    | `/livros/{id}` | Atualiza um livro      |
| `DELETE` | `/livros/{id}` | Remove um livro        |

---

## 👤 Usuários

| Método   | Endpoint         | Descrição               |
| -------- | ---------------- | ----------------------- |
| `GET`    | `/usuarios`      | Lista todos os usuários |
| `GET`    | `/usuarios/{id}` | Busca um usuário        |
| `POST`   | `/usuarios`      | Cadastra um usuário     |
| `PUT`    | `/usuarios/{id}` | Atualiza um usuário     |
| `DELETE` | `/usuarios/{id}` | Remove um usuário       |

---

## 🔄 Empréstimos

| Método   | Endpoint            | Descrição                   |
| -------- | ------------------- | --------------------------- |
| `GET`    | `/emprestimos`      | Lista os empréstimos        |
| `GET`    | `/emprestimos/{id}` | Busca um empréstimo         |
| `POST`   | `/emprestimos`      | Registra um novo empréstimo |
| `PUT`    | `/emprestimos/{id}` | Atualiza um empréstimo      |
| `DELETE` | `/emprestimos/{id}` | Remove um empréstimo        |

---

# 📊 Fluxo da API

```text
Usuário
   │
   ▼
Requisição HTTP
   │
   ▼
Rotas da API
   │
   ▼
Controller
   │
   ▼
Regras de negócio
   │
   ▼
Banco de Dados
   │
   ▼
Resposta JSON
```

---

# 🧠 Objetivo do projeto

Este projeto foi desenvolvido com o objetivo de colocar em prática conhecimentos relacionados a:

* Desenvolvimento Back-end
* Criação de APIs REST
* Métodos HTTP
* Manipulação de JSON
* Integração com banco de dados
* Operações CRUD
* Organização e arquitetura de projetos
* Versionamento com Git e GitHub

---

# 📌 Status

> 🚧 Projeto em desenvolvimento.

---

# 👨‍💻 Autor

Desenvolvido por **Pedro Henrique Rillo**.

🔗 GitHub: [github.com/rillopedro](https://github.com/rillopedro)

---

<div align="center">

### 📚 Library API

**Uma API simples, organizada e eficiente para gerenciamento de bibliotecas.**

⭐ Se este projeto foi útil, considere deixar uma estrela no repositório.

</div>
