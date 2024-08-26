
# Mobile-Atv2 - Crud de usuários

## Descrição

Este projeto é uma aplicação backend desenvolvida em Node.js e TypeScript, que utiliza MongoDB Atlas como banco de dados e foi implantada usando Railway. O objetivo principal é gerenciar usuários através de uma API REST.

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript.
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática.
- **Express**: Framework web para Node.js.
- **MongoDB Atlas**: Banco de dados NoSQL.
- **Railway**: Plataforma para deploy de aplicações.
- **Validator**: Biblioteca para validação de strings.
- **dotenv**: Gerenciamento de variáveis de ambiente.

## Scripts

- **`start:dev`**: Inicia o servidor em modo de desenvolvimento utilizando Nodemon e TS-Node.
- **`start`**: Inicia o servidor em modo de produção, executando o arquivo JavaScript compilado.
- **`build`**: Compila o código TypeScript para JavaScript.

## Endpoints da API

### Base URL

A aplicação está disponível em: [https://aps-atv2-production.up.railway.app/users](https://aps-atv2-production.up.railway.app/users)

### Rotas

- **GET `/users`**: Retorna todos os usuários salvos no banco.
- **POST `/users`**: Cria um novo usuário.
- **PATCH `/users/:id`**: Atualiza um usuário existente pelo `id`.
- **DELETE `/users/:id`**: Deleta um usuário existente pelo `id`.

## Como Executar o Projeto Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/SeuUsuario/mobile-atv2.git
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Configure as variáveis de ambiente no arquivo `.env`. 
PORT=8000.
MONGODB_URL=localhost:27017(caso use docker, já está preparado para isso).
MONGODB_URL= url do mongo mongodb+srv://#####.#####.mongodb.net.
MONGODB_USERNAME= login no mongodb.
MONGODB_PASSWORD= senha no mongo db.

4. Inicie o servidor em modo de desenvolvimento:
   ```bash
   npm run start:dev
   ```

