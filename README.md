# Modelo Dimensional en Pentaho

Se tiene un modelo relacional de ventas de productos de clientes cargado en  MS SQL Server 2014. El objetivo es diseñar un Data Warehouse  utilizando tanto un esquema Copo de Nieve, como un esquema Estrella y realizando el procesamiento de la informacion a traves de la herramienta ETL Pentaho.


## Esquema Estrella:

**Requisitos previos:**
Se requiere previamente crear dos bases de datos en SQL Server. La primera debe estar asociada a una conexion que se debe llamar "conMSSQL_relacional" la cual contendrá todas las tablas del modelo relacional con los datos de prueba precargados a traves del ETL.
La segunda conexion se debe nombrar "conMSSQL_dimensional_estrella". Esta última almacenara tanto las dimensiones, como la tabla de hechos del Modelo Dimensional.

**Ejecucion:**
Descargar todos los archivos de la carpeta "Esquema Estrella" y ejecutar el job "JOB_BI.kjb"


## Esquema Copo de Nieve:

**Requisitos previos:**
Se requiere previamente crear dos bases de datos en SQL Server. La primera debe estar asociada a una conexion que se debe llamar "conMSSQL_relacional" la cual contendrá todas las tablas del modelo relacional con los datos de prueba precargados a traves del ETL.
La segunda conexion se debe nombrar "conMSSQL_dimensional". Esta última almacenara tanto las dimensiones, como la tabla de hechos del Modelo Dimensional.

**Ejecucion:**
Descargar todos los archivos de la carpeta "Esquema Copo de Nieve" y ejecutar el job "JOB_BI.kjb"


