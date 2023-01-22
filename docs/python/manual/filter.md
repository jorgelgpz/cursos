---
title: Función Filter
lastmod: 
tags: [Funciones, Filter]
categories: [Programación, Python]
type: book
weight: 141
---

## La función filter()

La función incorporada `filter()` permite filtrar elementos de una lista o de cualquier objeto iterable. 
Como primer argumento se le debe indicar una función `f(i)` que tome como argumento un objeto y retorne un valor 
booleano (`True` o `False`); en segundo lugar, el objeto iterable it que se desea filtrar. 
Como resultado retorna un iterador cuyos elementos son aquellos presentes en `it` para los cuales `f(i) == True`.



```python linenums="1"
def es_par(n):
    return n % 2 == 0

list(filter(es_par, range(1, 51))) 
```
`output`
```py 
[2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50]
```

En este caso, `filter()` recorre cada uno de los elementos de `range(1, 51)` y ejecuta para cada uno de ellos la función 
especificada (`es_par()`). Si el resultado es verdadero, lo incluye en el iterador resultante.