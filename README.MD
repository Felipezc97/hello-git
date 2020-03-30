# Tipos de cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
===========
Underline 2
-----------

# Formatos de énfasis
- Formato *italica* de la primera forma (con *)
- Formato _italica_ de la segunda forma (con _ )
- Formato **negrita, bold o strong** de la primera forma (con **)
- Formato __negrita, bold o strong__ de la segunda forma (con __ )
- Formato ~~tachado~~
- Formato normal

# Listas
1. Esto es un ítem de una lista ordenada
2. Esto es un ítem de una lista ordenada
3. Esto es un ítem de una lista ordenada
- Esto es un ítem de una lista desordenada
- Esto es un ítem de una lista desordenada
- Esto es un ítem de una lista desordenada

# Links
- <a href="http://www.google.com">Esto es un link en HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al archivo index](index.html)

# Imágenes
![Logo de github](https://1000marcas.net/wp-content/uploads/2020/02/GitHub-Logo.jpg)

<img src="https://1000marcas.net/wp-content/uploads/2020/02/GitHub-Logo.jpg" alt="Logo de Github">

# Code snippets
Ejemplo de código en C#
```C#
using System.IO.Compression;

#pragma warning disable 414, 3021

namespace MyApplication
{
    [Obsolete("...")]
    class Program : IInterface
    {
        public static List<int> JustDoIt(int count)
        {
            Console.WriteLine($"Hello {Name}!");
            return new List<int>(new int[] { 1, 2, 3 })
        }
    }
}
```

EJEMPLO DE CÓDIGO EN JSON
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

EJEMPLO DE CODIGO EN JAVASCRIPT
```JavaScript
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
| Nombre | Apellido | Cédula |
| ------ | -------- | ------ |
| Felipe | Zumárraga | 1004083760 |
| Jimena | Zumárraga | 1001783925 |
| Bertha | Cadena | 1000227080 |

# Citas
Esto es un texto que se relaciona con la primera referencia.
>Felipe Zumárraga.

Esto es el texto de la segunda cita
>Luis Zumárraga

# Líneas divisorias
Esto es un texto que será dividido con guiones medios

---
Esto es otro texto dividido con asteriscos

***
Esto es otro texto dividido con guiones bajos

___

# Saltos de línea
Este texto pertenece al primer párrafo.

Este texto pertenece al segundo párrafo.

Este texto pertenece al tercer párrafo.

