---
title: Ejercicios de Programación Funcional
linkTitle: Programación Funcional
date: 
lastmod:
tags: [Ejercicios, Programación Funcional]
categories: [Programación, Python]
type: book
weight: 70
---

## Ejercicio 1

Escribir una función que aplique un descuento a un precio y otra que aplique el IVA a un precio. Escribir una tercera función que reciba un diccionario con los precios y porcentajes de una cesta de la compra, y una de las funciones anteriores, y utilice la función pasada para aplicar los descuentos o el IVA a los productos de la cesta y devolver el precio final de la cesta.

<a target=blank href="https://colab.research.google.com/drive/1rVxKqZ7BJuRBn0YklDnCMU0w6I46euLq" class="btn btn-info">Solución</a>

## Ejercicio 2

Escribir una función que simule una calculadora científica que permita calcular el seno, coseno, tangente, exponencial y logaritmo neperiano. La función preguntará al usuario el valor y la función a aplicar, y mostrará por pantalla una tabla con los enteros de 1 al valor introducido y el resultado de aplicar la función a esos enteros.

<a target=blank href="https://colab.research.google.com/drive/1f_Vfi6tW6HrharfNPH8lsZ1wxSHLOfuv" class="btn btn-info">Solución</a>

## Ejercicio 3

Escribir una función que reciba otra función y una lista, y devuelva otra lista con el resultado de aplicar la función dada a cada uno de los elementos de la lista.

<a target=blank href="https://colab.research.google.com/drive/17LAQHzxPuCo983xmNqgcbK2FwPprsU03" class="btn btn-info">Solución</a>

## Ejercicio 4

Escribir una función que reciba otra función booleana y una lista, y devuelva otra lista con los elementos de la lista que devuelvan `True` al aplicarles la función booleana.

<a target=blank href="https://colab.research.google.com/drive/1r-3t1-ru81L2DdfuVEJYKoLKHcqwGq6p" class="btn btn-info">Solución</a>

## Ejercicio 5

Escribir una función que reciba una frase y devuelva un diccionario con las palabras que contiene y su longitud.

<a target=blank href="https://colab.research.google.com/drive/1Su2wDdBOT6-UdrJr7RPceG6Wp1pEjBj1" class="btn btn-info">Solución</a>

## Ejercicio 6

Escribir una función reciba una lista de notas y devuelva la lista de calificaciones correspondientes a esas notas.

<a target=blank href="https://colab.research.google.com/drive/1viR8klDP4exMnC_ey0vAPcfNB3W1ULnz" class="btn btn-info">Solución</a>

## Ejercicio 7

Escribir una función reciba un diccionario con las asignaturas y las notas de un alumno y devuelva otro diccionario con las asignaturas en mayúsculas y las calificaciones correspondientes a las notas.

<a target=blank href="https://colab.research.google.com/drive/1TbsGwJe1yA5x94087ETQpM8wEn_GgT06" class="btn btn-info">Solución</a>

## Ejercicio 8

Escribir una función reciba un diccionario con las asignaturas y las notas de un alumno y devuelva otro diccionario con las asignaturas en mayúsculas y las calificaciones correspondientes a las notas aprobadas.

<a target=blank href="https://colab.research.google.com/drive/1-QwS56FflteBMecpqF4_FiOvQp23ImSB" class="btn btn-info">Solución</a>

## Ejercicio 9

Escribir una función que calcule el módulo de un vector.

<a target=blank href="https://colab.research.google.com/drive/1DkP0JFSr6cuNoWA9k4SM_9NEkTibxWrC" class="btn btn-info">Solución</a>

## Ejercicio 10

Una inmobiliaria de una ciudad maneja una lista de inmuebles como la siguiente:

```python 
[{'año': 2000, 'metros': 100, 'habitaciones': 3, 'garaje': True, 'zona': 'A'},
{'año': 2012, 'metros': 60, 'habitaciones': 2, 'garaje': True, 'zona': 'B'},
{'año': 1980, 'metros': 120, 'habitaciones': 4, 'garaje': False, 'zona': 'A'},
{'año': 2005, 'metros': 75, 'habitaciones': 3, 'garaje': True, 'zona': 'B'},
{'año': 2015, 'metros': 90, 'habitaciones': 2, 'garaje': False, 'zona': 'A'}]
```

Construir una función que permita hacer búsqueda de inmuebles en función de un presupuesto dado. La función recibirá como entrada la lista de inmuebles y un precio, y devolverá otra lista con los inmuebles cuyo precio sea menor o igual que el dado. Los inmuebles de la lista que se devuelva deben incorporar un nuevo par a cada diccionario con el precio del inmueble, donde el precio de un inmueble se calcula con las siguiente fórmula en función de la zona:

- Zona A: precio = (metros * 1000 + habitaciones * 5000 + garaje * 15000) * (1-antiguedad/100)
- Zona B: precio = (metros * 1000 + habitaciones * 5000 + garaje * 15000) * (1-antiguedad/100) * 1.5

<a target=blank href="https://colab.research.google.com/drive/1Qj5j00aNz3p4ZQwRjathNku826RdU6di" class="btn btn-info">Solución</a>

## Ejercicio 11

Escribir una función que reciba una muestra de números y devuelva los valores atípicos, es decir, los valores cuya puntuación típica sea mayor que 3 o menor que -3. 
Nota: La puntuación típica de un valor se obtiene restando la media y dividiendo por la desviación típica de la muestra.

<a target=blank href="https://colab.research.google.com/drive/1KhFLR3ShHJu_Rae9BH_gkhdWq0CRxLJL" class="btn btn-info">Solución</a>