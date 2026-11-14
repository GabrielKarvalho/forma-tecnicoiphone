# Formação Técnico em iPhone — Landing page

Site estático (HTML + CSS + JS puros), sem build. Pronto para GitHub + Vercel.

## Estrutura
- `index.html` — página completa (estilos e scripts embutidos)
- `img/` — imagens otimizadas em WebP + `og-image.jpg` (prévia de compartilhamento)
- `favicon.svg` — ícone da aba
- `vercel.json` — cache das imagens e URLs limpas

## Publicar
1. Crie um repositório no GitHub e envie estes arquivos (na raiz).
2. Na Vercel: **Add New → Project → Import** o repositório.
3. Framework Preset: **Other**. Build Command: vazio. Output Directory: vazio (raiz).
4. Deploy. Depois, em **Settings → Domains**, conecte seu domínio.

## Antes de rodar anúncios
- Trocar o `href="#"` do botão de compra (classe `js-checkout`) pelo link do checkout.
- Meta Pixel já instalado (ID 1126461060235843). Cadastre o mesmo Pixel na plataforma de checkout para o evento Purchase.
- Depois de ter o domínio, troque `content="img/og-image.jpg"` por `https://SEUDOMINIO/img/og-image.jpg` (o Facebook exige link completo).
