# Modelo Entidad Relación

## Entidad Libro

Atributo | Tipo de dato | Longitud | Tipo de Dato | Nulo | Compuesto | Restricciones |
--|--|--|--|--|--|--|
ISBNID | 13 | Cadena | No | Simple | Llave Primaria
Titulo | 100 | Cadena | No | Simple |
Autor | 50 | Cadena | No | Simple |
Titulo | 30 | Cadena | No | Simple |
Categoria | 30 | Cadena | Si | Simple |
AñoPublicacion | - | Entero | Si | Simple |
Editorial | 30 | Cadena | No | Simple |
Idioma | 20 | Cadena | No | Simple |
Estado | 20 | Cadena | No | Simple |
Cantidad | - | Entero | No | Simple |

## Entidad Autor

Atributo | Tipo de dato | Longitud | Tipo de Dato | Nulo | Compuesto | Restricciones |
--|--|--|--|--|--|--|
Nombre | Cadena | 30 | No | Simple |
Nacionalidad | Cadena | 20 | Si | Simple |
Nacimiento | Cadena | 20 | Si | Simple |
ID | Cadena | 20 | No | Simple | Llave Primaria

## Entidad Usuario

Atributo | Tipo de dato | Longitud | Tipo de Dato | Nulo | Compuesto | Restricciones |
--|--|--|--|--|--|--|
Nombre | Cadena | 40 | No | Simple |
Dirección | Cadena | 30 | Si | Simple |
NumeroTel | Cadena | 20 | No | Simple |
Correo | Cadena | 20 | No | Simple |
ID | Cadena | 20 | No | Simple | Llave Primaria
Estado | Booleano | - | No | Simple |

## Entidad Préstamo

Atributo | Tipo de dato | Longitud | Tipo de Dato | Nulo | Compuesto | Restricciones |
--|--|--|--|--|--|--|
IdPrestamo | Entero | - | No | Simple | Llave Primaria
Estado | Cadena | 30 | No | Simple | 
FechaInicio | Cadena | 6 | No | Compuesto | 
FechaEntrega | Cadena | 6 | No | Compuesto | 
Periodo | Cadena | 6 | No | Compuesto | 
Usuario | Cadena | 40 | No | Compuesto | 
LibroId | Entero | - | No | Simple | 

## Entidad Categoría

Atributo | Tipo de dato | Longitud | Tipo de Dato | Nulo | Compuesto | Restricciones 
--|--|--|--|--|--|--
Id | Cadena | 10 | No | Simple | Llave Primaria 
Nombre | Cadena | 20 | No | Simple |
Descripcion | Cadena | 20 | Si | Simple |
