# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========
# Formatos de enfasis
- formato *italica* de la primer forma
- formato _italica_ de la segunda forma
- formato **bold o strong** de la primer forma
- formato __italica__ de la segunda forma
- formato ~~tachado~~, formato normal.
- aqui podemos usar *formato italico*, pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es un item de la lista ordenada.
2. Esto es un item de la lista ordenada.
3. Esto es un item de la lista ordenada.
- Esto es un item de la lista desordenada.
- Esto es un item de la lista desordenada.
- Esto es un item de la lista desordenada.

# Links
- <a href="http//google.com">Esto es un link html</a>
- [Esto es un link en markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://www.muycomputerpro.com/wp-content/uploads/2019/12/GitHub_en_China.jpg)

# Code Snippets
Codigo en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Codigo en Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```
# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Ivan | Franco | 696969696 |
| Danin | Franco | 697967697 |
