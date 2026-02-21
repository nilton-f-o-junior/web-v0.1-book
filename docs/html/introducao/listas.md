---
sidebar_position: 7
---

# Listas

`ol`

```html
// lista ordenadas
// atributos - type // start // reversed // value
<ol type="A" >
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

`ul`

```html
// listas não ordenadas
// css: list-style-type
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

`lista dentro de lista`

```html
<ol type="I" >
    <li>Item 1</li>
        <ol>
            <li>Item A</li>
            <li>Item B</li>
            <li>Item C</li>
        </ol>
    <li>Item 2</li>
        <ul>
            <li>Item D</li>
            <li>Item E</li>
            <li>Item F</li>
        </ul>
    <li>Item 3</li>
</ol>
```

`dl dt dd`

```html
// lista de definição
<dl>
    <dt>Lista Ordenada</dt>
    <dd>Conjunto de itens que segue uma ordem</dd>

    <dt>Lista não Ordenada</dt>
    <dd>Conjunto de itens em que a ordem não foi definida</dd>

    <dt>Lista com Definição</dt>
    <dd>Conjunto de itens que possui o nome e depois uma descrição</dd>
</dl>
```

`dl div dt dd div`

```html
// div para falicitar o css
<dl>
    <div>
        <dt>Lista Ordenada</dt>
        <dd>Conjunto de itens que segue uma ordem</dd>

        <dt>Lista não Ordenada</dt>
        <dd>Conjunto de itens em que a ordem não foi definida</dd>

        <dt>Lista com Definição</dt>
        <dd>Conjunto de itens que possui o nome e depois uma descrição</dd>
    </div>
</dl>
```