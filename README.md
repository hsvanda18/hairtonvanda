# Visitas 360° · Hairton Vanda

Site estático (HTML + CSS + JS). Não precisa de build.

## Publicar na Vercel
1. Cria um repositório no GitHub e envia o conteúdo desta pasta.
2. Na Vercel: Add New → Project → importa o repositório.
3. Framework Preset: **Other**. Build Command: vazio. Output Directory: vazio (raiz).
4. Deploy.

Ou pela linha de comandos, dentro desta pasta: `npx vercel --prod`

## Estrutura
- `index.html` — página, demo 360° (three.js via cdnjs) e portfólio
- `assets/` — capturas dos sites, favicon e imagem de partilha (og.jpg)
