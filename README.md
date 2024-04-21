# Bot de Atendimento no Telegram

Este é um bot de atendimento desenvolvido para o Telegram, utilizando Node.js, o framework node-telegram-bot-api, e o ORM Prisma para integração com um banco de dados SQLite.

## Funcionalidades

- Responde automaticamente às mensagens recebidas, fornecendo informações sobre o horário comercial da empresa.
- Solicita o e-mail do usuário fora do horário comercial e o armazena no banco de dados para posterior contato.
- Reinicia o atendimento após o registro do e-mail válido ou quando o usuário inicia uma nova conversa.

## Requisitos

- Node.js
- npm (ou yarn)
- Conta no Telegram para registrar um novo bot

## Como Configurar

1. Clone este repositório:
   ```
   git clone https://github.com/victorfpaulino/bot_telegram.git
   ```

2. Instale as dependências do projeto:
   ```
   npm install
   ```

3. Configure o arquivo `.env` com as suas credenciais do Telegram e do banco de dados SQLite.

4. Execute o bot:
   ```
   node ./src/bot.js
   ```

## Configuração do `.env`

No arquivo `.env`, adicione as seguintes variáveis de ambiente:

```
TELEGRAM_TOKEN=Sua_Token_do_Telegram
DATABASE_URL=sqlite://caminho_para_seu_banco_de_dados.db
```
