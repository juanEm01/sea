Para ejecutar los scripts primero se deben obtener los datos de la encuesta de condiciones de vida año 2022 que fue con el que se trabajó,

se descarga de esta ruta:

https://www.ine.es/dyngs/INEbase/es/operacion.htm?c=Estadistica_C&cid=1254736176807&menu=resultados&idp=1254735976608#!tabs-1254736195153

En la sesión de microdatos - Ficheros transversales. Base 2013, se descarga el fichero transversal año 2022 

y luego nos quedamos con este archivo: ECV_Tp_2022.xlsx como nuestro dataset

Luego se adecua y ruta se renombra para cargar el dataset en el script de notebook Python

Se ejecutan los pasos hasta llegar a la parte del análisis factorial, el cual se hace en SAS BASE

para lo cual se exporta a un archivo llamado EncuestaINE.csv

Este archivo se carga en el SAS BASE, se ejecuta el script de SAS y volvemos a Python con el archivo de los factores llamado Factores.xlsx

En Python con la carga del archivo Factores.xlsx se procede a la parte final de ejecución de los modelos.