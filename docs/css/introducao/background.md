---
sidebar_position: 4
---

# Background

| Propriedade | O que faz | Valores Comuns / Exemplos |
|---|---|---|
| `background-color` | Cor de fundo do elemento | `transparent` (padrão), `blue`, `#ffffff`, `rgba(255, 0, 0, 0.5)` |

`html`

```html
<header>
    <h1>Header com Background Local</h1>
</header>

<main>
    <h2>Conteúdo Principal</h2>
    <p>Role a página para baixo para ver a diferença dos efeitos.</p>
</main>
```

`css`

```css
body {
    background-color:rgb(117, 117, 117);
}

header {
    color: #fff;
    background-color: black;
}

main {

    color: #fff;
    background-color: rgb(0, 0, 0);
}
```

Nota: [Mais tags](/css/extras/background-extra.md)