# Primeros comandos en MongoDB

### Mostrar las base de datos
`show dbs;`
`show databases;`

### Crear una Conexion
#### para crear una base de datos
*En mongo DB para crear una base de datos debe contener una conexion*

`use "nombre de la base de datos"`
*Ejemplo:*

`use db3;`

### Crear una Coleccion

`db.createCollection("Nombre de una Colección")`

*Ejemplo*

`db.createCollection ("Alumnos")`

*Nota: MongoDB sabe doferenciar las minusculas de mayusculas, escribir el nombre tal como esta*

## Mostrar las conecciones de la base de datos

*Ejemplo:*

`show collections`