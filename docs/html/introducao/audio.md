---
sidebar_position: 6
---

# Áudio

`audio`

```html
<audio src="musica.mp3" controls autoplay loop muted preload="auto">
  Seu navegador não suporta o elemento de áudio.
</audio>
```

`audio + source`

```html
<audio controls autoplay loop muted preload="auto">
  <source src="audio/musica.mp3" type="audio/mpeg">
  <source src="audio/musica.ogg" type="audio/ogg">
  <source src="audio/musica.wav" type="audio/wav">
    <p>Seu navegador não suporta este áudio.</p>
</audio>
```

`audio + source + download`

```html
<audio controls autoplay loop muted preload="auto">
  <source src="audio/musica.mp3" type="audio/mpeg">
  <source src="audio/musica.ogg" type="audio/ogg">
  <source src="audio/musica.wav" type="audio/wav">

  <p>
    Seu navegador não suporta este player.
    <a href="audio/musica.mp3">Clique aqui para baixar o arquivo.</a>
  </p>
</audio>
```