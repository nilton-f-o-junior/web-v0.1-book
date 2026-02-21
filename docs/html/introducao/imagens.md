---
sidebar_position: 3
---

# Imagem e Favicon

`img`

```html
<img src="images.jpeg" alt="texto alternativo">
```

`picture`

```html
<picture>
  <source media="(max-width: 600px)" srcset="imagem-pequena.jpg">
  <source media="(max-width: 1024px)" srcset="imagem-media.jpg">
  <img src="imagem-grande.jpg" alt="Descrição da imagem" style="width:100%;">
</picture>
```

`favicon`

```html
<link rel="icon" href="favicon.ico" type="image/x-icon">
```