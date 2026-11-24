# Meu App Web

Estrutura inicial pronta para publicar um aplicativo web diretamente pelo GitHub.

## Estrutura da Pasta

- `index.html` — Página principal da aplicação.
- `src/style.css` — Estilização responsiva.
- `src/app.js` — Lógica da aplicação com salvamento local (`localStorage`).
- `.github/workflows/deploy.yml` — Workflow automático para publicação no **GitHub Pages**.
- `.gitignore` — Arquivos ignorados pelo Git.

## Como publicar no GitHub Pages

1. Crie um novo repositório no GitHub.
2. Envie todos os arquivos desta pasta para a branch `main`.
3. No repositório do GitHub, vá em **Settings > Pages**.
4. Em **Build and deployment > Source**, selecione **GitHub Actions** (ou **Deploy from a branch** -> `main`).
5. Seu app estará online em poucos segundos!
