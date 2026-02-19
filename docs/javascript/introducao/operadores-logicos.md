---
sidebar_position: 6
---

# Operadores Lógicos

`&&`

```js
// e
// so as duas sendo verdeiro > true
let a = 1;
let b = 2;
let c = 3;
let d = 4;

console.log((a > b) && (c < d));
```

`||`

```js
// ou
// ou uma ou outra verdaderio > true
let a = 1;
let b = 2;
let c = 3;
let d = 4;

console.log((a > b) && (c < d));
console.log((a > b) || (c < d));
```

`!`

```js
// not
// inverte o true > false | false > true
let a = 1;
let b = 2;
let c = 3;
let d = 4;

console.log((a > b) || !(c < d));
```