# Barrica — Documentos Legais

Site estático com a Política de Privacidade e os Termos de Uso do aplicativo Barrica, hospedado via GitHub Pages.

## Por que repo separado

O código do aplicativo Barrica está em repositório privado. Este repositório existe **apenas** para hospedar os documentos legais em URL pública, conforme exigência da Google Play Store (e futuramente da App Store).

Mantém o código do app privado e expõe publicamente apenas o que precisa ser público.

## Conteúdo

- `index.html` — landing com links para os dois documentos
- `privacy.html` — Política de Privacidade (LGPD)
- `terms.html` — Termos de Uso
- `style.css` — estilo único compartilhado

Sem JS, sem build step, sem dependências externas. HTML estático puro.

## URLs públicas

- `https://legal.barrica.app/`
- `https://legal.barrica.app/privacy.html`
- `https://legal.barrica.app/terms.html`

O endereço antigo (`https://ciberagresco.github.io/barrica-legal/`) continua no ar e funcionando, mas o domínio próprio é o canônico a partir de agora.

## Como atualizar

A fonte da verdade é o repositório do aplicativo (`src/legal/privacyPolicy.js` e `src/legal/termsOfUse.js`). Quando o conteúdo mudar lá, copiar manualmente para os HTMLs deste repositório e versionar a mudança (subir o número de versão e a data).

## Versão atual dos documentos

- Política de Privacidade: 1.3 — 17 de julho de 2026
- Termos de Uso: 1.0 — 20 de março de 2026

## Contato

[barricaapp@gmail.com](mailto:barricaapp@gmail.com)
