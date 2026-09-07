# Seu João · Transporte Executivo

Página informativa estática (HTML + CSS, sem dependências) sobre os serviços de motorista particular do João Luiz Lochter, em Sorocaba/SP.

## Estrutura

- `index.html` — a página completa
- `assets/motorista-particular-sorocaba-joao-lochter.jpeg` — logomarca (salve a imagem aqui com esse nome)
- `.nojekyll` — desativa o processamento Jekyll no GitHub Pages

## Publicar no GitHub Pages

1. Salve a logomarca em `assets/motorista-particular-sorocaba-joao-lochter.jpeg`.
2. Crie um repositório no GitHub e envie os arquivos:

   ```bash
   git init
   git add .
   git commit -m "Página do Seu João"
   git branch -M main
   git remote add origin https://github.com/jlochter/motorista.seujoao.git
   git push -u origin main
   ```

3. No GitHub, abra **Settings → Pages**, em *Source* escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em alguns minutos a página estará em `https://jlochter.github.io/motorista.seujoao/`.

## Editar

Todo o texto está em `index.html`. As cores ficam nas variáveis CSS no topo do arquivo (`--amarelo`, `--preto`, etc.).

## Indexação no Google

- `robots.txt` e `sitemap.xml` já estão na raiz.
- Cadastre `https://jlochter.github.io/motorista.seujoao/` no [Google Search Console](https://search.google.com/search-console), envie o sitemap e peça a indexação da página inicial.
