---
sidebar_position: 3
---

# Color

| Propriedade | O que faz | Valores Comuns / Exemplos |
|---|---|---|
| `color` | Cor do texto | `red`, `#4285f4`, `rgb(0,0,0)`, `hsl(0, 0%, 50%)` |
| `color-scheme` | Modo claro ou escuro | `normal`, `light`, `dark`, `light dark` |


`html`

```html
<body class="light-theme"> 
  
    <h1 id="titulo-tema">Tema Light</h1>
    <p>Este é um parágrafo para testar a legibilidade das cores e o comportamento dos elementos nativos.</p>
    <button id="btn-toggle">Alternar Tema</button>

    <script src="script.js"></script>
</body>
```

`css`

```css
body {
    transition: all 0.3s ease;
    padding: 50px;
    font-family: sans-serif;
}

body.light-theme {
    color: #000000;
    color-scheme: light; 

    background-color: #ffffff;
}

body.dark-theme {
    color: #ffffff;
    color-scheme: dark;

    background-color: #000000;
}
```

`js`

```js
const btn = document.getElementById('btn-toggle');
const body = document.body;
const titulo = document.getElementById('titulo-tema');

btn.addEventListener('click', () => {

    body.classList.toggle('light-theme');
    body.classList.toggle('dark-theme');

    if (body.classList.contains('dark-theme')) {
        titulo.textContent = "Tema Dark";
    } else {
        titulo.textContent = "Tema Light";
    }
});
```


