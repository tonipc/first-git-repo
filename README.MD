# Cabeceras
# Cabecera h1
## Cabercera h2
### Cabecera h3
#### Cabercera h4
##### Cabecera h5
###### Cabecera h6

# Subrayados
Underline 1
----------

Underline 2
==========

# Formatos de enfasis
- letra *italica* de la primera manera.
- letra _italica_ de la segunda manera.
- formato **bold o strong** de la 1a manera.
- formato  __bold o strong__ de la 2a manera.
- formato ~~tachado~~.
- aqui podemos usar formato *italico*, **bold** y ~~tachado~~.

# Listas

1. Esto es un item de lista ordenada.
1. Este es un item de lista ordenada.
-  Este es un item de lista no ordenada.
-  Este es un item de lista no ordenada.

# Links o enlaces

- <a href="http://www.pepe.es">Esto es un link html</a>
- [Esto es un link en Markdown](http:/www.pepe.es)
- [Esto es un link al index](index.html)

# Imágenes
![Logo Github](https://image.flaticon.com/icons/svg/25/25231.svg)

# Code Snippets
Código en JSON
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
````
Código en Javascript
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
| Toni | Crack | GitHub curso |
|Pepe | Sanchez | GitHub curso 2 |

# Citas
Texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto ya no es una cita.
> Pero esto ya es otra cita.

# Lineas divisorias
Texto que será dividido.

---
Más texto dividido.
****
Otro dividido por guiones bajos.
___

# Saltos de linea
1er párrafo. 

2o párrafo. 

3er párrafo.
