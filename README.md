# Slides da Clínica II: modelos de linguagem

Slides da aula de modelos de linguagem da Clínica II do Insper, publicados com GitHub Pages. O visualizador (`ver.html`) mostra o PDF página a página e troca cada slide de animação pela página interativa (`animacao-*.html`), que mora na mesma pasta.

- `index.html` abre o deck.
- `ver.html?deck=aula-llm.pdf#N` abre na página N.
- `pdfjs/`: pdf.js, da Mozilla, sob a licença Apache 2.0 em `pdfjs/LICENSE`.

O visualizador busca o PDF por HTTP: para ver localmente, rode `python3 -m http.server` nesta pasta e abra `http://localhost:8000`.
