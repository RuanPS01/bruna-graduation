# Convite de Formatura | Bruna Eduarda dos Santos Martinez

Site estático, sem build. Basta servir a pasta como está.

## Publicar no Render

1. Suba esta pasta em um repositório no GitHub.
2. No Render: New, Static Site, conecte o repositório.
3. Build Command: deixe em branco.
4. Publish Directory: `.` (a raiz, onde está o `index.html`).
5. Deploy.

## Antes de divulgar o link

Abra o `index.html` e troque todas as ocorrências de
`https://convite-bruna.onrender.com` pela URL real do site.
São as tags `og:url`, `og:image`, `twitter:image` e `canonical`.
O preview do WhatsApp só funciona com URL absoluta e em HTTPS.

Depois de publicar, se o WhatsApp já tiver cacheado o link antigo,
use o Facebook Sharing Debugger para forçar a releitura das tags.

## Arquivos

- `index.html` : a página inteira
- `assets/preview.jpg` : imagem 1200x630 que aparece no preview do link
- `assets/favicon.ico`, `favicon-32.png`, `favicon-192.png`, `favicon-512.png`, `apple-touch-icon.png` : ícones
- `assets/capelo.png` : ícone do capelo usado na capa
- `assets/hero.jpg`, `p1.jpg`, `p2.jpg`, `p3.jpg`, `final.jpg` : fotos

Para trocar o capelo por outra arte, substitua `assets/capelo.png`
mantendo o mesmo nome e regenere os ícones a partir dela.
