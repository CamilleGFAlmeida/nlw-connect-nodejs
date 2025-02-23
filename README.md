# Evento NLW Connect Node.js

## 📍 Sobre

Este projeto foi desenvolvido durante o evento NLW da Rocketseat e tem como objetivo fornecer uma API para gerenciar inscrições em eventos. Os usuários podem se inscrever, gerar links de indicação e visualizar um ranking baseado nas indicações realizadas.

## 🚀 Tecnologias Utilizadas

O projeto foi desenvolvido com as seguintes tecnologias:

- **Node.js**
- **TypeScript**
- **Fastify**
- **Prisma ORM**
- **SQLite**
- **Zod**

## 📂 Estrutura do Projeto

O projeto segue uma organização modular para melhor escalabilidade e manutenção:

- **src/** → Código-fonte da aplicação.
  - **routes/** → Definição das rotas da API.
  - **controllers/** → Controladores para manipular regras de negócio.
  - **services/** → Lógica de aplicação e integração com banco de dados.
  - **prisma/** → Configuração do Prisma ORM.
  - **schemas/** → Validações de dados com Zod.

## ✨ Funcionalidades

- 📌 **Inscrição em Eventos**: Cadastro de usuários nos eventos.
- 🔗 **Geração de Links de Indicação**: Cada inscrito pode gerar um link único.
- 📊 **Ranking de Indicações**: Listagem dos usuários que mais indicaram.
- 📅 **Listagem de Eventos**: Recupera eventos disponíveis para inscrição.

## 🌐 Como Rodar o Projeto

### 🔹 Pré-requisitos
Certifique-se de ter instalado:
- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/) ou [npm](https://www.npmjs.com/)

### 🔹 Passos para execução

1. **Clone o repositório**

    ```bash
    git clone https://github.com/CamilleGFAlmeida/nlw-connect-nodejs.git
    ```

2. **Acesse a pasta do projeto**

    ```bash
    cd nlw-connect-nodejs
    ```

3. **Instale as dependências**

    ```bash
    npm install  # ou yarn install
    ```

4. **Configure o banco de dados**

    ```bash
    npx prisma migrate dev
    ```

5. **Inicie o servidor**

    ```bash
    npm run dev  # ou yarn dev
    ```

O servidor estará rodando em `http://localhost:3333/`.

## 🛠 Melhorias Futuras
- Integração com um frontend para exibição dos dados
- Implementação de autenticação de usuários
- Testes automatizados para garantir a estabilidade do sistema

---

Este projeto foi desenvolvido com base no evento NLW da Rocketseat. 💜🚀


