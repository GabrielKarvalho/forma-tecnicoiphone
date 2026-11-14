# Formação Técnico em iPhone — Landing page

Site estático (HTML + CSS + JS puros), sem build. Todos os arquivos ficam na RAIZ do repositório (sem pastas), para o upload pelo navegador do GitHub funcionar.

## Publicar
1. No GitHub: Add file → Upload files → selecione TODOS os arquivos desta pasta → Commit.
2. Na Vercel: o projeto já conectado ao repositório publica sozinho a cada commit.
   (Projeto novo: Add New → Project → Import; Framework: Other; sem build.)

## Antes de rodar anúncios
- Trocar o href="#" do botão de compra (classe js-checkout) pelo link do checkout.
- Meta Pixel instalado (ID 1126461060235843). Cadastre o mesmo Pixel na plataforma de checkout para o evento Purchase.
- Se mudar de domínio, atualize a meta og:image no index.html.
