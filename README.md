# Discord Bot Template

Template simples para criar bots Discord compatíveis com plataformas de hospedagem que usam Docker.

## Como usar

1. Clique em **Use this template** no GitHub.
2. Crie seu repositório.
3. Crie seu bot no Discord Developer Portal.
4. Copie o token do bot.
5. Faça deploy na plataforma de hospedagem.

## Estrutura

- index.js → arquivo principal do bot
- package.json → dependências do projeto
- Dockerfile → necessário para rodar em containers

## Importante

O token do bot deve ser enviado como variável de ambiente:

DISCORD_TOKEN
