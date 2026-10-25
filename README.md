# AS Soluções Tecnológicas

Site institucional estático. Os arquivos `index.html`, `styles.css`, `script.js` e `logo.png` ficam na raiz do projeto.

## Publicação no GitHub Pages

O workflow em `.github/workflows/pages.yml` publica o site automaticamente quando há um push para a branch `main`.

Na primeira publicação, configure o repositório em **Settings → Pages → Build and deployment → Source → GitHub Actions**. Depois, acompanhe a implantação na aba **Actions**; o endereço publicado aparece no ambiente `github-pages`.
