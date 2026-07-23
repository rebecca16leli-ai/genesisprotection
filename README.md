# Genesis Protection — Landing Page

Landing page institucional B2B da Genesis (PPF Guardian, películas automotivas e ferramentas profissionais).

## Como publicar no GitHub Pages

1. Suba este repositório (ou a pasta) no GitHub.
2. Vá em **Settings → Pages**.
3. Em "Branch", selecione a branch principal (ex: `main`) e a pasta `/ (root)`.
4. Salve. Em alguns minutos o site estará no ar em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

## Antes de publicar — IMPORTANTE

O número de WhatsApp ainda está com um valor de exemplo. Para corrigir:

1. Abra o arquivo `index.html` em um editor de texto.
2. Use Ctrl+F (ou Cmd+F) e procure por `WHATSAPP_NUMBER`.
3. Troque `"5500000000000"` pelo número real da Genesis, no formato:
   código do país + DDD + número, só dígitos (ex: `"5511999998888"`).

## Sobre o arquivo

- É um arquivo único (`index.html`), sem dependências externas — o logo e o vídeo da seção "Sobre" estão embutidos direto no código (base64).
- O arquivo é grande (~6MB) por causa do vídeo embutido. Isso é normal e não afeta o funcionamento do site, mas se quiser otimizar ainda mais o carregamento no futuro, o vídeo pode ser extraído para um arquivo `.mp4` separado e hospedado à parte (ex: em um CDN).
- Formulário de newsletter é apenas front-end (sem backend conectado) — captura visual do e-mail, mas não envia para nenhum lugar ainda.
