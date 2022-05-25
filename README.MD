# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-
Underline 2
=


# Formato de enfasis
- letra *italica* primer forma. 
- letra _italica_ segunda forma.
- formato **bold** o strong primer forma
- formato __bold o strong__ primer forma
- formato ~~tachado~hola~~

# Listas
1. esto es un item de lista ordenada
2. esto es un item de lista ordenada
3. esto es un item de lista ordenada 
1. esto es un item de lista ordenada

- esto es un item de lista desordenada
- esto es un item de lista desordenada
- esto es un item de lista desordenada
- esto es un item de lista desordenada

# links

- <a href='http://google.com'> esto es un link html</a>
- [Esto es un link markdown](http://google.com)
- [Esto es un link index](index.html)

# Imagenes
![logo github](https://cdn-icons-png.flaticon.com/512/25/25231.png)

# Code snippets
codigo JSON
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
Codigo JavaScript

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
|Nombre| Apellido | Documento |
|------|----------|-----------|
|Maxi  | Burgos   |123456
|Tomas | Ros  | 23232323

# Citas
Esto ews un texto referente a una cita que pondremos abajo:
> Esto es una cita. 

esto es otro texto que no se relaciona con el texto anterior. dos enter de separacion 
> Esto es otra cita

# Lineas divisoras 
Esto es un texto que sera dividido por guiones medios

---
este es otro texto dividido por asteriscos 

***

esto es otro texto dividido por guines bajos

___

# Saltos de linea
esto es nuestro primer parrafo.

esto es nuestro segundo parrafo. 

esto es nuestro tercer parrafo. 
- lista