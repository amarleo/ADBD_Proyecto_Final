# Proyecto Administración y Diseño de Bases de Datos
***

## Participantes

- Anabel Díaz Labrador [alu0101206011@ull.edu.es](alu0101206011@ull.edu.es)
- Alejandro Martín de León [alu0101015941@ull.edu.es](alu0101015941@ull.edu.es)
- Jaime Pablo Pérez Moro [alu0101278919@ull.edu.es](alu0101278919@ull.edu.es)
- Andrea Calero Caro [alu0101202952@ull.edu.es](alu0101202952@ull.edu.es)
- Saúl Pérez García [alu0101129785@ull.edu.es](alu0101129785@ull.edu.es)
- Sheyla Ruiz-Gómez Ferreira  [alu0101124445@ull.edu.es](alu0101124445@ull.edu.es)

## Esquema de Archivos

Se muestra a continuación, el árbol de archivos:

.  
├── Carga_de_datos  
│   └── CargaDatos.pdf  
├── Esquema_ER  
│   ├── ERE_libreria.pdf  
│   └── libreria-modelo-ER.jpeg  
├── Generacion_de_codigo  
│   └── Plantilla_Scripts.pdf  
├── Modelo_Logico_Objeto_Relacional  
│   ├── PlantillaOR.pdf  
│   └── UML.PNG  
├── Modelo_Logico_Relacional  
│   ├── modelo_definitivo.png  
│   └── ModeloRelacional.pdf  
├── README.md  
├── Registro_de_Reuniones  
│   └── Registro de reuniones.pdf  
├── Requisitos  
│   └── Requisitos_Libreria.pdf  
└── Scripts  
    ├── script_completo.sql  
    └── script_Original.sql  

## Definición del supuesto

En este supuesto se plantea el caso de una librería, donde se pretende representar y almacenar en una base de datos todas las transacciones que se producen en ella, tales como el control de stock de libros, un registro de compras, ...

Con este proyecto, se intenta lograr los siguientes objetivos:

- Aprender a diseñar y optimizar un diseño de bases de datos.
- Tener iniciativa para aportar y/o evaluar soluciones alternativas o novedosas a los problemas.
- Aprender a utilizar nuevas herramientas.
- Capacidad para encontrar, relacionar y estructurar información proveniente de diversas fuentes y de integrar ideas y conocimientos.

## Requisitos

Tal y como se ha mencionado con anterioridad, existen una serie de requisitos para la implementación de esta base de datos. Dichos requisitos se encuentran descritos en el siguiente enlace: 

[Requisitos](https://github.com/amarleo/ADBD_Proyecto_Final/blob/master/Requisitos/Requisitos_Libreria.pdf)

## Modelo Conceptual

Una vez finalizado los requisitos, y con la intención de facilitar la representación de la base de datos, se ha plasmado en un modelo Entidad-Relación las entidades, atributos y relaciones necesarias para la implementación. Este modelo Entidad-Relación se encuentra descrito en el siguiente enlace: 

[Modelo Entidad-Relación](https://github.com/amarleo/ADBD_Proyecto_Final/blob/master/Esquema_ER/ERE_libreria.pdf)

## Modelo Lógico Relacional

Después de esquematizar todas las necesidades y requerimientos de este problema, se pretende aproximar al modelo de datos SQL. El procedimiento llevado a cabo se encuentra descrito en el siguiente enlace: 

[Modelo Lógico Relacional](https://github.com/amarleo/ADBD_Proyecto_Final/blob/master/Modelo_Logico_Relacional/ModeloRelacional.pdf)

## Modelo Lógico Objeto-Relacional

Por otro lado, con el objetivo de incorporar funciones del Modelo Orientado a Objetos, se ha creado ademñas el Modelo Lógico Objeto-Relacional. El procedimiento se puede observar en el siguiente enlace: 

[Modelo Lógico Objeto-Relacional](https://github.com/amarleo/ADBD_Proyecto_Final/blob/master/Modelo_Logico_Objeto_Relacional/PlantillaOR.pdf)

## Generación de Scripts

Después de haber creado el Modelo Lógico Relacional, se ha puesto en práctica la implementación de la Base de Datos a través de PostgreSQL con Scripts. En el siguiente directorio, se encuentran tanto la generación automática de script por parte de la aplicación [MySQL WorkBench](https://www.mysql.com/products/workbench/), como la transformación del mismo para el uso con PostgreSQL.

El directorio se encuentra en el siguiente [enlace](https://github.com/amarleo/ADBD_Proyecto_Final/tree/master/Scripts)

## Carga de Datos

En el [script_completo](https://github.com/amarleo/ADBD_Proyecto_Final/blob/master/Scripts/script_completo.sql) se muestra además, ejemplos de carga de datos sobre la base de datos creada.

## Registro de Reuniones

Por último, en el siguiente [enlace](https://github.com/amarleo/ADBD_Proyecto_Final/blob/master/Registro_de_Reuniones/Registro%20de%20reuniones.pdf) se encuentra el registro de todas las reuniones en las que han participado los integrantes del grupo.