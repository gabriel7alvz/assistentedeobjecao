# Assistente de Objeções — Foodzap

Ferramenta interna de apoio ao time comercial com IA.

## Deploy no Vercel

1. Faça upload deste repositório no GitHub
2. Importe o projeto no Vercel (vercel.com)
3. Nas configurações do projeto, adicione a variável de ambiente:
   - Nome: `ANTHROPIC_API_KEY`
   - Valor: sua chave da API da Anthropic (platform.anthropic.com)
4. Clique em Deploy

## Estrutura
- `public/index.html` — interface do assistente
- `api/chat.js` — backend que conecta com a API do Claude (chave fica segura no servidor)
- `vercel.json` — configuração de rotas
