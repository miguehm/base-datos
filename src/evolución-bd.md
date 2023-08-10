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

Es una serie de recursos para manejar grandes volúmenes de información (Bases de Datos), actuando como un intermediario entre el usuario y los datos.

Permite el almacenamiento, modificación y extracción de la información en una base de datos de forma eficiente, simultanea, redice la redundancia y los cambios no requieren cambios en el modelo de los datos. También mantiene los datos íntegros, protegiendo los datos contra perdidas de información y restringiendo los acceso no autorizados.

### LDD

El LDD o DDL (Data Definition Language, en inglés) es un lenguaje proporcionado por el sistema de gestión de base de datos (SGBD) que permite a los usuarios **definir y modificar las estructuras que almacenarán los datos** y los procedimientos o funciones que permitan consultarlos. Esencialmente, se encarga de la creación, modificación y eliminación de la estructura de los objetos de la base de datos.

Las sentencias en SQL para LDD son `CREATE`, `DROP`, `ALTER`.

### LMD

LMD se utiliza para **manipular los datos** dentro de esta estructura permitiendo al usuario consultar, insertar, modificar y eliminar los datos dentro de las tablas de la base de datos.

Las sentencias en SQL para LMD son `SELECT`, `INSERT`, `UPDATE` y `DELETE`.

## Diccionario de Datos

El diccionario de datos enlista de manera organizada los nombres, definiciones y características de cada uno de los campos o atributos de una base de datos o conjunto de datos.

Un diccionario de datos puede incluir varios elementos esenciales que proporcionan una visión global de la estructura y las características de un conjunto de datos:

- Nombres de los campos de datos: Enumera los nombres o etiquetas asignados a cada campo de datos o columna del conjunto de datos.
- Tipos de datos: Describen la naturaleza de los datos dentro de cada campo, como numérico, texto, fecha o booleano.
- Descripciones de los campos: Proporcionan explicaciones claras y concisas de los campos de datos, ofreciendo un contexto adicional.
- Tamaño de los campos y restricciones: Define las limitaciones y restricciones de tamaño asociadas a cada campo de datos, como límites de caracteres, rangos de valores permitidos o formatos requeridos.
- Relaciones y dependencias: En los casos en que los conjuntos de datos están interconectados, los diccionarios de datos pueden incluir información sobre relaciones y dependencias entre distintos campos o tablas.
- Reglas de negocio y validaciones: Especifican las reglas de negocio y las validaciones aplicadas a cada campo de datos.
- Metadatos: Proporcionan información adicional sobre el conjunto de datos en su conjunto, como la fecha de creación, el autor, la fuente de datos y los detalles pertinentes sobre las versiones.

El objetivo principal de un diccionario de datos es proporcionar un lenguaje común entre el autor de los datos y sus posibles usuarios, facilitando la comprensión y el uso de los datos.

## Roles 

- **Administrador** 
    - Define el esquema de datos (tipo, formato, características...).
    - Decide que se almacena y como.
    - Define la estructura de almacenamiento y los métodos de acceso.
    - Decide como recuperar la información.
    - Modifica el esquema y la organización física y hace la concesión de permisos y privilegios para el acceso a los datos.
    - Asigna prioridades, claves de usuarios y especifica los restricciones de integridad.
- **Diseñador de BD** 
    - Realiza el diseño lógico de la BD.
    - Conoce la empresa, reglas, datos y relaciona con los usuarios para el desarrollo del diseño de la BD.
- **Programador de aplicaciones** 
    - Escribe programas para manipular la BD escritos en lenguajes de alto nivel y SQL.
- **Otros usuarios** 
    - Escriben BD especializadas.
    - Interactúan con la BD usando SQL como principal lenguaje de manipulación de datos.
    - Simplemente interactúan a través de aplicaciones creadas por programadores (usuario final).
