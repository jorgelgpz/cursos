---
title: Ejercicios de Diccionarios
linkTitle: Diccionarios
date: 
lastmod:
tags: [Ejercicios, Diccionarios]
categories: [Programación, Python]
type: book
weight: 50
---

## Ejercicio 1

Escribir un programa que guarde en una variable el diccionario `{'Euro':'€', 'Dollar':'$', 'Yen':'¥'}`, pregunte al usuario por una divisa y muestre su símbolo o un mensaje de aviso si la divisa no está en el diccionario.

<a target=blank href="https://colab.research.google.com/drive/19pw9XO5nJl3WVw37_fxiYzYL7xQWUoB3" class="btn btn-info">Solución</a>

## Ejercicio 2

Escribir un programa que pregunte al usuario su nombre, edad, dirección y teléfono y lo guarde en un diccionario. Después debe mostrar por pantalla el mensaje `<nombre> tiene <edad> años, vive en <dirección> y su número de teléfono es <teléfono>`.

<a target=blank href="https://colab.research.google.com/drive/1iu5XeDFHZqq0b90QXxh_m4YaKe3cpBGE" class="btn btn-info">Solución</a>

## Ejercicio 3

Escribir un programa que guarde en un diccionario los precios de las frutas de la tabla, pregunte al usuario por una fruta, un número de kilos y muestre por pantalla el precio de ese número de kilos de fruta. Si la fruta no está en el diccionario debe mostrar un mensaje informando de ello.

| Fruta   | Precio |
|:--------|:------:|
| Plátano |  1.35  |
| Manzana |  0.80  |
| Pera    |  0.85  |
| Naranja |  0.70  |

<a target=blank href="https://colab.research.google.com/drive/1X0KVSKnWJ-Lys6HQ9VbzyXggUOFA6a4h" class="btn btn-info">Solución</a>

## Ejercicio 4

Escribir un programa que pregunte una fecha en formato `dd/mm/aaaa` y muestre por pantalla la misma fecha en formato `dd de <mes> de aaaa` donde `<mes>` es el nombre del mes.

<a target=blank href="https://colab.research.google.com/drive/1DSSTZjdgGCBmHaCmVyb4C7G0Jg6svJdr" class="btn btn-info">Solución</a>

## Ejercicio 5

Escribir un programa que almacene el diccionario con los créditos de las asignaturas de un curso `{'Matemáticas': 6, 'Física': 4, 'Química': 5}` y después muestre por pantalla los créditos de cada asignatura en el formato `<asignatura> tiene <créditos> créditos`, donde `<asignatura>` es cada una de las asignaturas del curso, y `<créditos>` son sus créditos. Al final debe mostrar también el número total de créditos del curso.

<a target=blank href="https://colab.research.google.com/drive/1WKgp8d8ST_tAtzXyJ64ClRKSAi72H4DS" class="btn btn-info">Solución</a>

## Ejercicio 6

Escribir un programa que cree un diccionario vacío y lo vaya llenado con información sobre una persona (por ejemplo nombre, edad, sexo, teléfono, correo electrónico, etc.) que se le pida al usuario. Cada vez que se añada un nuevo dato debe imprimirse el contenido del diccionario.

<a target=blank href="https://colab.research.google.com/drive/1LqYrMNuEetyeZaFFBAI8VVH-kFZMJdgu" class="btn btn-info">Solución</a>

## Ejercicio 7

Escribir un programa que cree un diccionario simulando una cesta de la compra. El programa debe preguntar el artículo y su precio y añadir el par al diccionario, hasta que el usuario decida terminar. Después se debe mostrar por pantalla la lista de la compra y el coste total, con el siguiente formato

| Lista de la compra |        |
|:-------------------|-------:|
| Artículo 1         | Precio |
| Artículo 2         | Precio |
| Artículo 3         | Precio |
| ...                |    ... |
| Total              |  Coste |

<a target=blank href="https://colab.research.google.com/drive/10S4eBUTD3cbB1AnlAnSZYs-i7lsltYTE" class="btn btn-info">Solución</a>

## Ejercicio 8

Escribir un programa que cree un diccionario de traducción español-inglés. El usuario introducirá las palabras en español e inglés separadas por dos puntos, y cada par `<palabra>:<traducción>` separados por comas. El programa debe crear un diccionario con las palabras y sus traducciones. Después pedirá una frase en español y utilizará el diccionario para traducirla palabra a palabra. Si una palabra no está en el diccionario debe dejarla sin traducir.

<a target=blank href="https://colab.research.google.com/drive/1D9L4Imw_VhZltIRCp5-OodGPLNDX-a66" class="btn btn-info">Solución</a>

## Ejercicio 9

Escribir un programa que gestione las facturas pendientes de cobro de una empresa. Las facturas se almacenarán en un diccionario donde la clave de cada factura será el número de factura y el valor el coste de la factura. El programa debe preguntar al usuario si quiere añadir una nueva factura, pagar una existente o terminar. Si desea añadir una nueva factura se preguntará por el número de factura y su coste y se añadirá al diccionario. Si se desea pagar una factura se preguntará por el número de factura y se eliminará del diccionario. Después de cada operación el programa debe mostrar por pantalla la cantidad cobrada hasta el momento y la cantidad pendiente de cobro.

<a target=blank href="https://colab.research.google.com/drive/1ReZryzigoAcfiHM5NsGN5NVwMgE7H9aL" class="btn btn-info">Solución</a>

## Ejercicio 10

Escribir un programa que permita gestionar la base de datos de clientes de una empresa. Los clientes se guardarán en un diccionario en el que la clave de cada cliente será su NIF, y el valor será otro diccionario con los datos del cliente (nombre, dirección, teléfono, correo, preferente), donde preferente tendrá el valor `True` si se trata de un cliente preferente. El programa debe preguntar al usuario por una opción del siguiente menú: (1) Añadir cliente, (2) Eliminar cliente, (3) Mostrar cliente, (4) Listar todos los clientes, (5) Listar clientes preferentes, (6) Terminar. En función de la opción elegida el programa tendrá que hacer lo siguiente:

1. Preguntar los datos del cliente, crear un diccionario con los datos y añadirlo a la base de datos.
2. Preguntar por el NIF del cliente y eliminar sus datos de la base de datos.
3. Preguntar por el NIF del cliente y mostrar sus datos.
4. Mostrar lista de todos los clientes de la base datos con su NIF y nombre.
5. Mostrar la lista de clientes preferentes de la base de datos con su NIF y nombre.
6. Terminar el programa.

<a target=blank href="https://colab.research.google.com/drive/1xppN2P1MCr4H1Z-nggb6VoOeKevzIQUo" class="btn btn-info">Solución</a>

## Ejercicio 11

El directorio de los clientes de una empresa está organizado en una cadena de texto como la de más abajo, donde cada línea contiene la información del nombre, email, teléfono, nif, y el descuento que se le aplica. Las líneas se separan con el carácter de cambio de línea `\n` y la primera línea contiene los nombres de los campos con la información contenida en el directorio.

```python 
"nif;nombre;email;teléfono;descuento\n01234567L;Luis González;luisgonzalez@mail.com;656343576;12.5\n71476342J;Macarena Ramírez;macarena@mail.com;692839321;8\n63823376M;Juan José Martínez;juanjo@mail.com;664888233;5.2\n98376547F;Carmen Sánchez;carmen@mail.com;667677855;15.7"
```

Escribir un programa que genere un diccionario con la información del directorio, donde cada elemento corresponda a un cliente y tenga por clave su nif y por valor otro diccionario con el resto de la información del cliente. Los diccionarios con la información de cada cliente tendrán como claves los nombres de los campos y como valores la información de cada cliente correspondientes a los campos. Es decir, un diccionario como el siguiente

```Python 
{'01234567L': {'nombre': 'Luis González', 'email': 'luisgonzalez@mail.com', 'teléfono': '656343576', 'descuento': 12.5}, '71476342J': {'nombre': 'Macarena Ramírez', 'email': 'macarena@mail.com', 'teléfono': '692839321', 'descuento': 8.0}, '63823376M': {'nombre': 'Juan José Martínez', 'email': 'juanjo@mail.com', 'teléfono': '664888233', 'descuento': 5.2}, '98376547F': {'nombre': 'Carmen Sánchez', 'email': 'carmen@mail.com', 'teléfono': '667677855', 'descuento': 15.7}}
```

<a target=blank href="https://colab.research.google.com/drive/1WlKIfKHER5m3kCxdYorpXsty6y6ua3gf" class="btn btn-info">Solución</a>
