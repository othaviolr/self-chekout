# 🛒 Self-Chekout Delivery

Sistema de **self-checkout** para pedidos via delivery, desenvolvido com **TypeScript**, **React**, **Next.js** e **PostgreSQL**.  

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

---

## ✨ Funcionalidades

- 🛍️ Escolha de produtos e criação de pedidos
- 💳 Self-checkout com resumo e finalização
- 📦 Tela de status de pedidos
- 🔐 Áreas públicas e privadas com rotas protegidas
- ⚙️ Integração com banco de dados PostgreSQL

---

## 📸 Demonstração

> 

---

## 🧱 Tecnologias e ferramentas

- **Frontend:** Next.js + React + TypeScript
- **Backend:** API via Next.js + Prisma ORM
- **Banco de Dados:** PostgreSQL
- **Validação:** Zod / Yup
- **Estilo:** Tailwind CSS 
- **Ambiente:** Docker
- **Outros:** ESLint, Prettier, GitHub Actions

---

## 🚀 Como rodar o projeto localmente

### Pré-requisitos

- Node.js 
- PostgreSQL
- Yarn ou npm

### Passos

```bash
# 1. Clone o repositório
git clone https://github.com/othaviolr/self-chekout.git
cd self-chekout

# 2. Instale as dependências
npm install

# 3. Configure o banco de dados
# Crie um arquivo .env com base no .env.example

# 4. Rode as migrations e seeds (se houver)
npx prisma migrate dev

# 5. Inicie o projeto
npm run dev
