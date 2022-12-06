# Desafio Técnico - Full Stack

## Descrição

Desafio técnico para vaga de Full Stack Developer na [Clickideia](http://clickideia.com.br/).

## Objetivo

O objetivo do desafio é desenvolver uma aplicação quadro de tarefas (kanban) com as seguintes funcionalidades:

- Autenticação de usuário
- Criar novas tarefas
- Editar tarefas
- Mover tarefas entre colunas
- Excluir tarefas

## Backend

### Tecnologias utilizadas

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [Prisma](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [JWT](https://jwt.io/)

## Frontend

### Tecnologias utilizadas

- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Axios]("https://axios-http.com/")
- [Higlight.js](https://highlightjs.org/)
- [Marked](https://marked.js.org/)

## Rodando o projeto com Docker

1. Faça um fork desse repositório

2. Crie um arquivo `.env` na pasta back com as seguintes variáveis de ambiente:

```bash
PORT=5000
DATABASE_URL="postgresql://USER:PASSWORD@HOST:PORT/DATABASE?schema=SCHEMA"
JWT_SECRET="secret"
LOGIN="example"
SENHA="example"
```

3. Inicie o projeto

```bash
docker-compose up
```
