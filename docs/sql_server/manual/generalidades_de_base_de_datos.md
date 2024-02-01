<h2>
    <div style="text-align: center;">
        ¿Qué es una base de datos? 
    </div>
</h2>


> <p style="text-align: justify;">
>Una base de datos es un conjunto de datos que tienen una procedencia similar y 
>que son apuntados de forma sistemática para ser procesados posteriormente. El 
>procesamiento de estos datos va a depender de los objetivos que tengamos 
>nosotros o nuestra empresa.
>
>Todas las bases de datos hacen casi lo mismo. Ordenan y clasifican los datos y
> después estará dispuesta para que investiguemos y analicemos. -- Graph Everywhere, 2021
></p>

## Sistemas gestores de bases de datos

Un sistema gestor de base de datos (SGBD), es un conjunto de programas que 
permiten el almacenamiento, modificación y extracción de la información en una 
base de datos. Los usuarios acceden a la información con herramientas específicas 
de consulta y de generación de informes.


## ¿Cuáles son los componentes de un SGBD?


Un sistema de gestión de base de datos consta de varios componentes, todos ellos
contribuyen al buen funcionamiento del software. Los elementos básicos que lo 
conforman son tres: `el diccionario de datos`, `el lenguaje de definición de datos` y el 
`lenguaje de manipulación de datos`.

**Diccionario de datos:** consiste en una lista de metadatos que reflejan las 
características de los diversos tipos de datos incluidos en la base de datos. Además, 
estos metadatos informan sobre los permisos de uso de cada registro y su
representación física. De esta manera, el diccionario proporciona toda la 
información relevante sobre los datos almacenados.

**Lenguaje de definición de datos:** el lenguaje de definición de datos, también llamado 
lenguaje de base de datos o DDL (Data Definition Language), sirve para estructurar 
el contenido de la base de datos. Gracias a este lenguaje, es posible crear, modificar 
y eliminar objetos individuales, como referencias, relaciones o derechos de usuario.

**Lenguaje de manipulación de datos:** mediante el lenguaje de manipulación de datos 
o DML (Data Manipulation Language), se pueden introducir nuevos registros en la 
base de datos, así como eliminar, modificar y consultar los que ya contiene. Este 
lenguaje también permite comprimir y extraer los datos.

## Tipos de Base de Datos

- Bases de Datos Relacionales (RDBMS):
<pre>
    Ejemplos: MySQL, PostgreSQL, Oracle, Microsoft SQL Server.
    Utilizan tablas y relaciones para organizar la información.
</pre>
- Bases de Datos No Relacionales (NoSQL):
<pre>
    Incluyen varios modelos de datos como documentos, clave-valor, columnares y grafos.
    Ejemplos: MongoDB (documento), Cassandra (clave-valor), Neo4j (grafos).
</pre>