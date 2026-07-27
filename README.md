# Genesis Protection — Landing Page

Landing page institucional B2B da Genesis (PPF Guardian, películas automotivas e ferramentas profissionais).

## Arquivos

- `index.html` — a página em si
- `genesis-video-sobre.mp4` — vídeo usado na seção "A Genesis fornece..."
- `genesis-video-poster.jpg` — capa/thumbnail exibida antes do vídeo tocar
- `genesis-hero-van.jpg` — foto da van usada no banner principal (hero)
- `genesis-card-guardian.jpg` — foto usada no card "Guardian PPF"
- `genesis-card-peliculas.jpg` — foto usada no card "Películas Automotivas"
- `genesis-card-ferramentas.jpg` — foto usada no card "Ferramentas Profissionais"
- `genesis-logo-icon.png` — escudo da marca (usado no menu e no rodapé)

**Importante:** todos os arquivos acima precisam ficar juntos, na mesma pasta, sempre. O `index.html` referencia os outros pelo nome — se algum for movido ou renomeado, a imagem/vídeo correspondente para de aparecer.

## Como publicar no GitHub Pages

1. Suba este repositório (ou a pasta) no GitHub, com todos os arquivos na raiz.
2. Vá em **Settings → Pages**.
3. Em "Branch", selecione a branch principal (ex: `main`) e a pasta `/ (root)`.
4. Salve. Em alguns minutos o site estará no ar em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

## WhatsApp

O número já está configurado: **(11) 99176-6474**.

Se precisar trocar, abra o `index.html`, use Ctrl+F (ou Cmd+F) e procure por `WHATSAPP_NUMBER`. O valor deve estar no formato: código do país + DDD + número, só dígitos (ex: `"5511999998888"`).

Cada botão de catálogo (Guardian, Películas, Ferramentas, Seja um Revendedor, etc.) já envia uma mensagem pronta e personalizada para o WhatsApp, específica daquele produto/seção. Para editar essas mensagens, procure por `data-msg=` no `index.html`.

## Sobre o formulário de newsletter

É apenas front-end (sem backend conectado) — captura visual do e-mail, mas não envia para nenhum lugar ainda.
