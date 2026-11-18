# Charme Brechó — site + link na bio

Prévia em modo demonstração (não indexada).

- Site: https://charme-brecho-exemplo.vercel.app/
- Link na bio: https://charme-brecho-exemplo.vercel.app/bio

## Como editar
- Cores: só no `:root` de `index.html` e `bio/index.html`.
- WhatsApp, mensagens, links e liga/desliga de seções: objeto `CONFIG` no fim de cada página.
- Fotos: pasta `img/` (vitrine em `img/vitrine/`).

## Ao publicar oficialmente
Remover a faixa `.demo`, a meta `robots` noindex, o header `X-Robots-Tag` do `vercel.json` e o `Disallow` do `robots.txt`.
