# T: Tendencias Base de Datos

<!-- toc -->

# Bases de datos como servicio (DBaaS) 

Es un modelo de servicio en la nube que permite a los usuarios utilizar bases de datos sin tener que preocuparse por la infraestructura subyacente.

Las bases de datos como servicio (DBaaS, por sus siglas en inglés) son una forma de alojar y administrar bases de datos en la nube. En lugar de tener que configurar y mantener una infraestructura de base de datos por separado, las DBaaS permiten a los usuarios acceder y utilizar bases de datos a través de una plataforma en la nube. Esto significa que los usuarios no tienen que preocuparse por la instalación, configuración y mantenimiento de servidores de base de datos, ya que todo eso es manejado por el proveedor de servicios en la nube. Los usuarios pueden simplemente enfocarse en utilizar y administrar los datos en la base de datos sin tener que preocuparse por la infraestructura subyacente.

Aquí hay una lista de algunos servicios de bases de datos como servicio (DBaaS) que son populares y ampliamente utilizados:

1. **Amazon RDS**: Amazon Relational Database Service (RDS) facilita la configuración, la operación y la escalabilidad de bases de datos relacionales en la nube. Este servicio proporciona costos económicos y redimensionables mientras automatiza tareas de administración de bases de datos que consumen mucho tiempo ([Source 2](https://www.nutanix.com/es/info/what-is-dbaas)).

2. **Google Cloud SQL**: Es un servicio que facilita la configuración, el mantenimiento, la administración y la administración de bases de datos relacionales MySQL y PostgreSQL en la nube de Google ([Source 2](https://www.nutanix.com/es/info/what-is-dbaas)).

3. **Microsoft Azure SQL Database**: Es una base de datos relacional general como servicio (DBaaS) en la nube que proporciona las capacidades más avanzadas para las aplicaciones de datos más exigentes ([Source 5](https://www.computerweekly.com/es/opinion/Que-es-una-base-de-datos-como-servicio-DBaaS-y-como-impulsa-la-innovacion-empresarial)).

4. **IBM Db2 on Cloud**: Es una base de datos SQL totalmente administrada alojada en la nube de IBM. Db2 on Cloud ofrece la potente funcionalidad de una base de datos en local, pero está disponible a través de una compra flexible y basada en suscripción ([Source 5](https://www.computerweekly.com/es/opinion/Que-es-una-base-de-datos-como-servicio-DBaaS-y-como-impulsa-la-innovacion-empresarial)).

5. **MongoDB Atlas**: Es el servicio de base de datos global en la nube para aplicaciones modernas. Distribuido y seguro por diseño, Atlas es disponible en AWS, Azure y Google Cloud ([Source 6](https://www.cloud4u.com/us-es/cloud-hosting/database-as-a-service/)).

6. **Oracle Database Cloud Service**: Ofrece la capacidad de desplegar bases de datos Oracle con diferentes versiones, ediciones y opciones, en la nube de Oracle ([Source 6](https://www.cloud4u.com/us-es/cloud-hosting/database-as-a-service/)).

7. **Nutanix Database Service**: Permite a los administradores de bases de datos (DBA) gestionar fácilmente grandes flotas de bases de datos de Microsoft SQL Server, Oracle, MySQL y PostgreSQL con una única API y consola ([Source 13](https://www.nutanix.com/mx/products/database-service)).

Cada uno de estos servicios tiene sus propios pros y contras, por lo que la elección del servicio DBaaS correcto dependerá de las necesidades específicas de su proyecto o empresa.

# Bases de datos NoSQL 

## Introducción

## características

## Casos de Uso

## Ventajas y Desventajas

Las bases de datos NoSQL son un tipo de sistema de gestión de bases de datos que proporciona un mecanismo para almacenar y recuperar datos modelados de formas distintas a las tablas relacionales utilizadas en las bases de datos SQL. Los datos en las bases de datos NoSQL pueden ser almacenados en varios formatos, incluyendo modelos de valor clave, documentos, columnas anchas y grafos.

Aquí tienes algunos ejemplos de bases de datos NoSQL:

1. **MongoDB**: MongoDB es una base de datos NoSQL orientada a documentos. Permite almacenar y consultar datos en formato JSON-like, lo que facilita la flexibilidad y escalabilidad de los datos. Es ampliamente utilizado en aplicaciones web y móviles debido a su capacidad para manejar grandes volúmenes de datos y su facilidad de uso.

2. **Cassandra**: Cassandra es una base de datos NoSQL de tipo columna ampliamente utilizada para aplicaciones que requieren alta disponibilidad y escalabilidad lineal. Está diseñada para manejar grandes cantidades de datos distribuidos en múltiples servidores sin un único punto de fallo.

3. **Redis**: Redis es una base de datos NoSQL de tipo clave-valor que se utiliza principalmente como almacén de caché y para la gestión de sesiones. Es conocida por su alta velocidad y su capacidad para almacenar datos en memoria, lo que permite un acceso rápido a los datos.

4. **Elasticsearch**: Elasticsearch es una base de datos NoSQL de búsqueda y análisis de texto completo. Se utiliza para indexar y buscar grandes volúmenes de datos no estructurados, como registros de aplicaciones, documentos y contenido web.

5. **Neo4j**: Neo4j es una base de datos NoSQL de grafos. Está diseñada para almacenar y consultar datos relacionales de manera eficiente, lo que la hace ideal para aplicaciones que requieren modelado de relaciones complejas, como redes sociales y recomendaciones personalizadas.

Estos son solo algunos ejemplos de bases de datos NoSQL, y cada una tiene sus propias características y casos de uso específicos. La elección de la base de datos NoSQL adecuada dependerá de los requisitos y la naturaleza de tu proyecto o aplicación.

# Bases de datos de series cronológicas 

Estas bases de datos están diseñadas para manejar grandes volúmenes de datos de series temporales de manera eficiente y rápida.

Estas bases de datos se utilizan en una amplia gama de aplicaciones, que incluyen Internet de las cosas, monitoreo de sistemas y análisis de datos financieros.

Aquí tienes algunos ejemplos de bases de datos de series cronológicas:

1. **InfluxDB**: InfluxDB es una base de datos de series cronológicas de alto rendimiento y código abierto. Está diseñada específicamente para almacenar y consultar datos de series de tiempo, como métricas de sensores, registros de eventos y datos de aplicaciones. InfluxDB utiliza un modelo de datos basado en series de tiempo y ofrece una consulta flexible y eficiente para analizar datos temporales.

2. **Prometheus**: Prometheus es una base de datos de series de tiempo y un sistema de monitoreo y alerta de código abierto. Está diseñado para recopilar y almacenar métricas de series de tiempo, como latencia, uso de CPU y tráfico de red. Prometheus proporciona un lenguaje de consulta expresivo y permite la visualización de datos en tiempo real.

3. **Graphite**: Graphite es una base de datos de series de tiempo y un sistema de monitoreo de código abierto. Está diseñado para almacenar y visualizar datos de series de tiempo, como métricas de rendimiento y estadísticas de aplicaciones. Graphite utiliza el formato de datos Whisper para almacenar datos de series de tiempo y proporciona una interfaz web para explorar y visualizar los datos.

4. **OpenTSDB**: OpenTSDB es una base de datos de series de tiempo distribuida y escalable. Está diseñada para almacenar y consultar grandes volúmenes de datos de series de tiempo, como métricas de infraestructura, registros de eventos y datos de IoT. OpenTSDB utiliza una arquitectura distribuida y ofrece una interfaz de consulta eficiente para analizar datos de series de tiempo a escala.

Estos son solo algunos ejemplos de bases de datos de series cronológicas disponibles. Cada una tiene sus propias características y fortalezas, por lo que es importante evaluar tus necesidades específicas antes de elegir una base de datos para tu proyecto de series de tiempo.

# Cifrado Homomórfico 

## Introducción

Esta técnica permite tomar decisiones y responder consultas sobre datos cifrados sin descifrarlos, lo que simplifica enormemente la seguridad en la nube y el intercambio de datos.

## Características

Por ejemplo, una base de datos que almacena valores cifrados, esta base de datos permite realizar operaciones matemáticas con esos datos cifrados y obtener un resultado cifrado que puede ser descifrado para obtener la respuesta correcta

En las soluciones tradicionales de almacenamiento y computación en la nube, los clientes tienen que confiar en que el proveedor de servicios almacene y gestione sus datos de forma adecuada, por ejemplo, que no los comparta con terceros sin el consentimiento del cliente. Microsoft SEAL sustituye esta confianza por criptografía de última generación, lo que permite a los servicios en la nube proporcionar tanto almacenamiento cifrado como capacidades de computación, al tiempo que garantiza que los datos de sus clientes nunca estarán expuestos a nadie sin cifrar

Se basa en funciones lógicas

## Casos de Uso

- Microsoft SEAL: Es una biblioteca de criptografía homomórfica de código abierto desarrollada por Microsoft. Permite realizar operaciones homomórficas en datos cifrados utilizando diferentes esquemas de cifrado homomórfico. Puede ser utilizado para implementar características de cifrado homomórfico en bases de datos.
- PALISADE: Es otra biblioteca de cifrado homomórfico de código abierto que proporciona una implementación eficiente de esquemas de cifrado homomórfico. También se puede utilizar para agregar capacidades de cifrado homomórfico a una base de datos.

## Ventajas

- Garantiza la seguridad de los datos
- Eficiente en encriptaciones parciales
- Al basarse en la criptografía de retículos se considera resistente a ataques post-cuánticos.

## Desventajas

- Muy costoso de implementar y muy lento en encriptaciones completas.
- Las claves y los textos cifrados son de gran tamaño.
- Consume muchos recursos y es lento, produciendo latencia.

Craig Gentry 2008 primer modelo viable basándose en criptografía de retículos.
