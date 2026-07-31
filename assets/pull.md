Explicación de los campos de cada elemento

[tables]
___________
route
------
Formato: "<nombre-grupo>:<nombre-tabla>:<nombre-subtabla>:...
El nombre grupo vacío indica que es del grupo "_index_"

link
-----
En caso de obtener la tabla desde un link externo, este se especifica acá
Si está habilitado el {loadFromMultipleGoogleSheets}, cargará el nombre de la hoja escrito en link, usando como link el definido en {googleSheetsId}

content
--------
Es el contenido de la tabla, es decir, las filas sin procesar

__________________


[first-table]
Indica cuál es, por defecto, la primera tabla que se va a mostrar

__________________

[config]
Configuraciones sobre las tablas
Dichas configuraciones pueden incluir:
- min_price_to_buy: precio mínimo de compra

__________________

[updatedAt]
Fecha de la última vez que se actualizó el json