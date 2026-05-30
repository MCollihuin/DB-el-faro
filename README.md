# DB-el-faro
Base de datos utilizada para guardar la informacion nueva de el Faro

Modelo relacional 

USUARIO
--------
ID_Usuario (PK)
Nombre
Apellido
Email
Contrasena

CATEGORIA
---------
ID_Categoria (PK)
Nombre

ARTICULOS
---------
ID_Articulo (PK)
Titulo
Descripcion
ID_Usuario (FK)
ID_Categoria (FK)

CONTACTO
--------
ID_Contacto (PK)
Nombre
Mensaje
Fecha
