---
sidebar_position: 1
---

# Variáveis + Constante

`let`

```js
// recomendável por conta do escopo!
// toda váravel é mutavel por padrão
let texto_a = "Texto pequeno!";
console.log(texto_a);
```

```js
let texto_a = "Texto pequeno!";
console.log(texto_a);


texto_a = "Texto médio!";
console.log(texto_a);

texto_a = "Texto Grande!";
console.log(texto_a);

texto_a = 12;
console.log("Não é mais um texto: " + texto_a);
```

`const`

```js
const TEXTO = "Texto médio!";
console.log(TEXTO);
```

`var`

```js
var texto_b = "Médio grande!";
console.log(texto_b);
```
