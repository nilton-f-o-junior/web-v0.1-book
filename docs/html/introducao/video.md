---
sidebar_position: 8
---

# Vídeos

`iframe`

```html
<iframe width="560" height="315" 
  src="https://www.youtube.com/embed/ID_DO_VIDEO" 
  frameborder="0" 
  allowfullscreen>
</iframe>
```

`video + source`

```html
<video width="640" height="360" controls poster="imagem-de-capa.jpg">
  <source src="seu-video.mp4" type="video/mp4">
  <source src="seu-video.webm" type="video/webm">
  Seu navegador não suporta vídeos em HTML5.
</video>
```