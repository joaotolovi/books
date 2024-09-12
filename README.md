# 📚 API de Livros

Esta é uma API simples para gerenciamento de livros. Ela permite a criação, leitura, atualização e exclusão (CRUD) de livros.

## 🚀 Funcionalidades

- **Listar todos os livros**: Retorna uma lista de todos os livros cadastrados.
- **Obter detalhes de um livro**: Retorna as informações de um livro específico através do seu ID.
- **Adicionar um novo livro**: Permite adicionar um novo livro à coleção.
- **Atualizar um livro**: Atualiza as informações de um livro existente.
- **Excluir um livro**: Remove um livro do sistema.

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: Node.js
- **Framework**: Express
- **Banco de Dados**: MongoDB
- **Autenticação**: JWT (opcional)

## 📄 Endpoints

| Método | Endpoint          | Descrição                   |
|--------|-------------------|-----------------------------|
| GET    | `/books`          | Lista todos os livros       |
| GET    | `/books/:id`      | Retorna um livro específico |
| POST   | `/books`          | Adiciona um novo livro      |
| PUT    | `/books/:id`      | Atualiza um livro existente |
| DELETE | `/books/:id`      | Remove um livro             |

