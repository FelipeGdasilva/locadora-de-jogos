# 🎮 Locadora de Jogos - API REST

API RESTful para gerenciamento de uma locadora de jogos, desenvolvida para praticar rotas, manipulação de banco de dados e regras de negócio no back-end.

---

## 🚀 Tecnologias Utilizadas

- **Next.js** (App Router / Route Handlers)
- **TypeScript**
- **Prisma ORM**
- **PostgreSQL**

---

## 📌 Status do Desenvolvimento

- [x] Modelagem do banco de dados no PostgreSQL
- [x] Configuração do Prisma ORM e conexão com o banco
- [x] CRUD de **Jogos** (`/api/jogos`)
- [x] CRUD de **Clientes** (`/api/clientes`)
- [ ] CRUD de **Locações** (`/api/locacoes`)
- [ ] Validações e Regras de Negócio

---

## 🛠️ Como rodar o projeto localmente

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
   ```

2. **Instale as dependências:**

   ```bash
   npm install
   ```

3. **Configure as variáveis de ambiente:**

   Crie um arquivo `.env` na raiz do projeto com a URL do seu banco de dados PostgreSQL:

   ```env
   DATABASE_URL="postgresql://usuario:senha@localhost:5432/nome_do_banco?schema=public"
   ```

4. **Rode o servidor de desenvolvimento:**

   ```bash
   npm run dev
   ```

   A API estará rodando em http://localhost:3000.
