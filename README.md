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

