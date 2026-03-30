# 🍕 Sistema de Pizzaria

Sistema completo de gerenciamento de pizzaria desenvolvido com Node.js, utilizando SQLite (sql.js) como banco de dados. A aplicação permite o cadastro de usuários, clientes, pizzas e pedidos, além de autenticação com JWT.

- 📌 Funcionalidades
- 🔐 Autenticação de usuários (login com JWT)
- 👤 Cadastro e gerenciamento de usuários
- 🧑‍💼 Cadastro de clientes
- 🍕 Cadastro de pizzas
- 📦 Criação e gerenciamento de pedidos
- 💾 Banco de dados SQLite (em memória ou persistente)
- 🌐 Interface web simples (HTML, CSS e JavaScript)
- 🛠️ Tecnologias Utilizadas
Node.js
Express
SQLite (via sql.js)
JavaScript (ES6+)
HTML5 + CSS3
JWT (jsonwebtoken)
bcryptjs (criptografia de senhas)
dotenv (variáveis de ambiente)
cors
# 📁 Estrutura do Projeto
📦 sistema_pizzaria
├── index.js            # Arquivo principal do servidor
├── routes-index.js     # Rotas da aplicação
├── auth.js             # Middleware de autenticação
├── sqlite.js           # Configuração do banco de dados
├── seed.js             # Script para popular o banco
├── Cliente.js          # Model de cliente
├── Usuario.js          # Model de usuário
├── Pizza.js            # Model de pizza
├── Pedido.js           # Model de pedido
├── index.html          # Interface web
├── script.js           # Lógica do front-end
├── style.css           # Estilos
├── .env.example        # Exemplo de variáveis de ambiente
├── package.json        # Dependências do projeto

# ⚙️ Instalação
Clone o repositório:
git clone <url-do-repositorio>
cd sistema_pizzaria
Instale as dependências:
npm install
Configure o arquivo .env:

Crie um arquivo .env baseado no .env.example.

# ▶️ Como Executar
🔹 Modo normal
npm start
🔹 Modo desenvolvimento (com nodemon)
npm run dev
🔹 Popular banco de dados
npm run seed
🔐 Autenticação

O sistema utiliza JWT (JSON Web Token) para autenticação.

Faça login para obter um token
Envie o token nas requisições protegidas:
Authorization: Bearer SEU_TOKEN


# 🌐 Interface Web

A aplicação possui uma interface simples localizada em:

index.html

Abra no navegador após iniciar o servidor.

# 📌 Scripts Disponíveis
Script	Descrição
npm start	Inicia o servidor
npm run dev	Inicia com nodemon
npm run seed	Popula o banco de dados
# 📊 Banco de Dados

O sistema utiliza SQLite com sql.js, permitindo:

Execução local sem necessidade de servidor externo
Persistência simples de dados
Fácil integração com Node.js

# 👨‍💻 Desenvolvedores

## Guilherme Barbosa torres🚀
## Nicolas Stekl Tordino🚀
