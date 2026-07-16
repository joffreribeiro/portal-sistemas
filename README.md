# Portal de Sistemas

Página estática (HTML/CSS puro) com atalhos para os 3 sistemas internos:
Controle de Estoque, Ponto e Controle TED.

## Como usar

Abra `index.html` diretamente no navegador, ou sirva com qualquer servidor
estático (ex: `npx serve .`).

## Como editar os links

Em `index.html`, cada sistema é um card `<a>`. Troque o `href="#"` pela URL
real de cada sistema assim que estiverem publicados:

```html
<a class="card card--estoque" href="https://SUA-URL-AQUI" target="_blank" rel="noopener">
```

Repita para os cards `card--ponto` e `card--ted`.
