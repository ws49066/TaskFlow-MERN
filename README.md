# 🚀 TaskFlow – Gerenciador de Projetos (MERN Stack)

TaskFlow é uma aplicação web fullstack inspirada em ferramentas como Trello, ClickUp e Asana. Permite a criação e gerenciamento de projetos em equipe, com funcionalidades de autenticação, autorização por cargos, tarefas em estilo Kanban e painel administrativo.

![taskflow-banner](https://via.placeholder.com/1000x300.png?text=TaskFlow+App+Preview)

---

## 🛠️ Tecnologias Utilizadas

### Frontend
- [React](https://reactjs.org/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Router](https://reactrouter.com/)

### Backend
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB + Mongoose](https://mongoosejs.com/)
- [JWT (Json Web Token)](https://jwt.io/)
- [TypeScript](https://www.typescriptlang.org/)

---

## 🔐 Funcionalidades

- [x] Registro e login com autenticação via JWT
- [x] Controle de acesso baseado em cargos (admin, gerente, membro)
- [x] CRUD de projetos e tarefas
- [x] Painel Kanban para tarefas (To do, Doing, Done)
- [x] Interface moderna com Tailwind CSS
- [x] Painel administrativo para gerenciar usuários
- [x] Responsividade para dispositivos móveis
- [x] Proteção de rotas no frontend e backend

---

## 📸 Prints

> Em breve...

---

## 🚧 Como Rodar Localmente

### Pré-requisitos
- Node.js 18+
- MongoDB local ou MongoDB Atlas
- Yarn ou NPM

### Backend

```bash
# Acesse a pasta do backend
cd server

# Instale as dependências
npm install

# Crie um arquivo .env com as seguintes variáveis:
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret

# Rode o servidor
npm run dev
