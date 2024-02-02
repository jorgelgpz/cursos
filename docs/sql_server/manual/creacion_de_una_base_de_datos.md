
## Creación de una base de datos

En este ejemplo el script crea la base de datos, sino está creada.


```sql linenums="1"
USE master;
GO

IF NOT EXISTS (SELECT name FROM sys.databases WHERE name = 'NombreDeTuBaseDeDatos')
BEGIN
    CREATE DATABASE NombreDeTuBaseDeDatos;
    PRINT 'Base de datos creada con éxito.';
END
ELSE
BEGIN
    PRINT 'La base de datos ya existe. No se requiere acción.';
END
GO
```
## SQL Server Management Studio Management Studio

![creacion_bd.png](..%2F..%2Fassets%2Fimagenes_sql_server%2Fcreacion_bd.png)

![creacion_nombre_db.png](..%2F..%2Fassets%2Fimagenes_sql_server%2Fcreacion_nombre_db.png)