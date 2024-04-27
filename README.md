# Bot de Atendimento no Telegram

Este é um bot de atendimento desenvolvido para o Telegram, utilizando Node.js, o framework node-telegram-bot-api, e o ORM Prisma para integração com um banco de dados SQLite.

## Funcionalidades

- Responde automaticamente às mensagens recebidas, fornecendo informações sobre o horário comercial da empresa.
- Solicita o e-mail do usuário fora do horário comercial e o armazena no banco de dados para posterior contato.
- Reinicia o atendimento após o registro do e-mail válido ou quando o usuário inicia uma nova conversa.

## Requisitos

- [Node.js](https://nodejs.org/en/download)
- [Conta no Telegram para registrar um novo bot](https://web.telegram.org/k/)
- Token do seu Bot pelo [Bot Father](https://www.npmjs.com/package/botfather)

## Como Configurar

1. Clone este repositório:
   ```
   git clone https://github.com/victorfpaulino/bot_telegram.git
   ```

2. Abra a pasta do projeto com sua IDE.

3. Instale as dependências do projeto:
   ```
   npm install
   ```
4. Coloque o TOKEN do seu bot no código bot.js

5. Faça migração do banco de dados:
   ```
   npx prisma migrate dev
   ```

6. Execute o bot:
   ```
   node ./src/bot.js
   ```
