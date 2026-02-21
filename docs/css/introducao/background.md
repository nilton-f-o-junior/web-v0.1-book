---
sidebar_position: 4
---

# Background

| Propriedade | O que faz | Valores Comuns / Exemplos |
|---|---|---|
| `background-color` | Cor de fundo do elemento | `transparent` (padrão), `blue`, `#ffffff`, `rgba(255, 0, 0, 0.5)` |
| `background-image` | Uma ou mais imagens/gradientes de fundo | `url('imagem.jpg')`, `linear-gradient(red, yellow)`, `none` |
| `background-position` | Posição inicial da imagem de fundo | `center`, `top left`, `50% 50%`, `20px 50px` |
| `background-repeat` | A imagem de fundo deve se repetir (mosaico) | `repeat` (padrão), `no-repeat`, `repeat-x`, `repeat-y` |
| `background-size` | Tamanho da imagem de fundo | `auto`, `cover` (preenche tudo), `contain` (mostra tudo), `100% 50%` |
| `background-clip` | Até onde o fundo deve se estender (bordas, preenchimento ou conteúdo). | `border-box` (padrão), `padding-box`, `content-box`, `text` |
| `background-attachment` | O fundo rola com a página ou fica fixo | `scroll` (padrão), `fixed`, `local` |


`html`

```html
<header>
    <h1>Header com Background Local</h1>
</header>

<main>
    <h1>Conteúdo Principal</h1>
    <p>Role a página para baixo para ver a diferença dos efeitos.</p>
        
    <div class="caixa-teste">
    <p>Efeito background-attachment: fixed</p>
    </div>

    <p class="paragrafo">O fundo da caixa acima parece "estático", certo? Isso é o efeito de fixar a imagem!</p>
</main>
```

`css`

```css
body {
    background: linear-gradient(rgb(0, 255, 72), #ff0000);
}

header {
    background-image: url('https://picsum.photos/1200/800');
    background-size: 4%;
    background-position: 100% left; 
    background-attachment: local;
}

main {
    background-color: white;
    background-attachment: scroll;
}

.caixa-teste {
    height: 200px;
    
    background-image: url('https://picsum.photos/1200/801');
    background-size: cover;
    background-attachment: fixed;
}

h1, p {
    color: #fff;
    text-align: center;
}

.paragrafo {
    margin-top: 300px;
}
```