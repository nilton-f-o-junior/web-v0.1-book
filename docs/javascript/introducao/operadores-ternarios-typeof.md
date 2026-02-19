---
sidebar_position: 8
---

# Operadores Ternários + Type of

`Se N + N = TRUE ? "True" : "False"`

```js
// condicao ?(se verdadeiro) faz isso :(se não) faz isso
let a = 2;
let b = 4;

let resultado = (a > b) ? "A maior B" : "A menor B";
console.log(resultado);
```

`typeof`

```js
let a = 1;
let b = "1"; // string
let c = '1'; // string
let d = a === b;
let e = {f: "f"};

console.log(typeof(a));
console.log(typeof(b)); 
console.log(typeof(c));
console.log(typeof(d));
console.log(typeof(e)); 
```