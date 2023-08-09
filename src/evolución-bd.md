# Introducción

## Definición

- Información: Datos que pueden ser **relacionados entre si** con un fin común y de forma mas o menos coherente.

## Objetivo

Tomar decisiones importantes en base a esa información.

## Historia

Las primeras bases de datos **basada en procesos** presentaban ambigüedades y contradicciones debido a la dificultad de acceso simultáneo. Posteriormente se estandarizo a un **modelo relacional** para representar los datos.

# Sistemas de Información Orientados a los Datos

- Los datos se centralizan en un a BD común a todas las las aplicaciones: Evita incoherencias.
- Los datos se almacenan en una única estructura lógica basado en tablas.
- Todos los datos son comunes.

Se crearon **sistemas gestores de datos**, suministra un lenguaje que permita consultar la base de datos sin necesidad de crear un programa para cada consulta.

## Ventajas

- Los datos pueden repartirse en múltiples tablas, ficheros o bases de datos.
- Da una visión uniforme de los datos.

## Acceso Concurrente

El sistema gestor de datos está preparado para responder ante situaciones que provoquen ambigüedades.

Ejemplo: Eliminar un registro y posteriormente modificarlo.

## Seguridad

Se asignan una serie de prioridades a cada usuario par acceder a un dato.

## Integridad de los datos

Deben de tener tipos de datos válidos y coherentes acorde a lo que se pretende hacer con ellos.

# Sistema Gestor de BD

Es una serie de recursos para manejar grandes volúmenes de información (Bases de Datos). Actuando como un intermediario entre el usuario y los datos.

Permite el almacenamiento, modificación y extracción de la información en una base de datos de forma eficiente, simultanea, redice la redundancia y los cambios no requieren cambios en el modelo de los datos. También mantiene los datos íntegros, protegiendo los datos contra perdidas de información y restringiendo los acceso no autorizados.

<!-- # Pendiente que es LDM y LDD -->

## Diccionario de Datos

<!-- #Pendiente que es diccionario de bases de datos? -->

La base de datos se acompaña con un diccionario de datos

## Roles

- Administrador: Define el esquema de datos (tipo, formato, características...), decide que se almacena y como, ademas define la estructura de almacenamiento y los metidos de acceso. Decide como recuperar la información, modifica el esquema y la organización física y hace la concesión de permisos y privilegios para el acceso a los datos, asigna prioridades, claves de usuarios y especifica los restricciones de integridad.
- Diseñador de BD: Realiza el diseño lógico de la BD, conoce la empresa, reglas, datos, relaciona con los usuarios para el desarrollo del diseño de la BD.
- Programador de aplicaciones: Escribe programas para manipular la BD escritos en lenguajes de alto nivel y SQL.
- Otros usuarios: Escriben BD especializadas, interactúan con la BD usando SQL como principal lenguaje de manipulación de datos o simplemente interactúan a través de aplicaciones creadas por programadores (usuario final).
