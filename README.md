# week4_day1

> MongoDB & MongoDB Compass


## Main points: `mongoimport`

El comando `mongoimport` permite importar un archivo JSON o CSV a una colección de MongoDB con la siguiente sintaxis:

`mongoimport --db <dabataseName> --collection <collectionName> --file <fileName> [flags]`

- El flag `--jsonArray` identifica un JSON con un array de objetos
- El flag `--drop` vacía la colección previo a importar los nuevos datos
