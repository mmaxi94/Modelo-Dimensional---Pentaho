# Modelo Dimensional en Pentaho

Se tiene un modelo relacional de ventas de productos de clientes cargado en  MS SQL Server 2014. El objetivo es diseñar un Data Warehouse  utilizando un esquema Copo de Nieve y realizando el procesamiento de la informacion a traves de la herramienta ETL Pentaho.


**Requisitos:**
Se requiere previamente crear dos bases de datos en SQL Server. La primera debe estar asociada a una conexion que se debe llamar "conMSSQL_relacional" la cual contendrá todas las tablas del modelo relacional con los datos de prueba precargados a traves del ETL.
La segunda conexion se debe nombrar "conMSSQL_relacional". Esta última almacenara tanto las dimensiones, como la tabla de hechos del Modelo Dimensional.
