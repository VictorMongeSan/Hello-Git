# Cabeceras

# Cabecera  H1
## Cabecera H2 
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6


# UNDERLINES

Underline 1
-----------

Underline 2
===========




# Formatos de enfasis
- formato *italica* de la primera forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primera forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- aqui podemos usar formato *italico* , pero tambien **bolt** y ~~tachado~~.

# LISTAS
1. lista ordenada
2. lista ordenada
3. lista ordenada

- lista desordenada
- lista desordenada
- lista desordenada



# Links
- <a href="http://www.googel.com">Link html</a>
- [Esto es un link en markdown MD](http://www.google.com)
- [Esto es un link al index](index.html)


# Imagenes
![Logo GitHub](https://th.bing.com/th?id=OIP.8SVgggxQcO5L6Dw_61ac4QHaEK&w=333&h=187&c=8&rs=1&qlt=90&o=6&pid=3.1&rm=2)

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

Codigo en JavaScript
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