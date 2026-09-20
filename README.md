🎮 Locadora de Jogos - API REST

API RESTful para gerenciamento de uma locadora de jogos, desenvolvida para praticar rotas, manipulação de banco de dados e regras de negócio no back-end.

🚀 Tecnologias Utilizadas

Next.js (App Router / Route Handlers)

TypeScript

Prisma ORM

PostgreSQL

📌 Status do Desenvolvimento

 Modelagem do banco de dados no PostgreSQL

 Configuração do Prisma ORM e conexão com o banco

 CRUD de Jogos (/api/jogos)

 CRUD de Clientes (/api/clientes)

 CRUD de Locações (/api/locacoes)

 Validações e Regras de Negócio

🛠️ Como rodar o projeto localmente

Clone o repositório:

git clone https://github.com/FelipeGdasilva/locadora-de-jogos.git



Instale as dependências:

npm install


Configure as variáveis de ambiente:

Crie um arquivo .env na raiz do projeto com a URL do seu banco de dados PostgreSQL:

DATABASE_URL="postgresql://usuario:senha@localhost:5432/nome_do_banco?schema=public"


Rode o servidor de desenvolvimento:

npm run dev


A API estará rodando em http://localhost:3000.