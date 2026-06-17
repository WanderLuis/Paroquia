# Conheça os Santos

Site estático pronto para GitHub Pages.

## Publicar pelo GitHub

1. Crie um repositório no GitHub.
2. Envie os arquivos `index.html` e `.nojekyll` desta pasta para a raiz do repositório.
3. No GitHub, abra `Settings` > `Pages`.
4. Em `Build and deployment`, escolha `Deploy from a branch`.
5. Selecione a branch `main` e a pasta `/root`.
6. Salve. O GitHub mostrará o link público da página.

## Publicar por git

```bash
git init
git add index.html .nojekyll README.md
git commit -m "Publica pagina Conheca os Santos"
git branch -M main
git remote add origin URL_DO_REPOSITORIO
git push -u origin main
```

Depois, ative o GitHub Pages em `Settings` > `Pages`.
