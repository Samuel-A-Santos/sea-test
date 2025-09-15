# CRUD


Aplicativo **React + TypeScript** para gerenciamento de **EPIS e de funcionários**. Utiliza **Ant Design** para a interface e conta com uma estrutura moderna baseada em Vite.

---

## Instruções para rodar o projeto

1. Clone o repositório:

   ```bash
   git clone git@github.com:Samuel-A-Santos/crud.git
   cd crud
   Instale as dependências:
   npm install 
   ```

---

## Executando a aplicação

A aplicação possui duas partes: o front-end React e um servidor de API mock.

   1. Para iniciar a API em json

   ```bash
      npx json-server --watch db.json --port 3001
   ```

   2. Para iniciar a aplicação do front-end

   ```bash
      npm run dev

      Após isso é só abrir em algum navegador na url: http://localhost:5173/
   ```

🧩 Funcionalidades:

✅ Gerenciamento de funcionários (ativo/inativo)

👤 Cadastro e edição de informações pessoais

🧾 Rastreamento e controle de EPIs entregues

📱 Design responsivo com Ant Design

🪜 Formulários em múltiplas etapas com progresso visual

🛠️ Tecnologias Utilizadas
React 19

TypeScript

Redux Toolkit

React Router v7

Ant Design

Vite

CSS Modules
