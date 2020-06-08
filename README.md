# OPI
Ejercicio 1
Descarga la Base de datos histórica de Quién es Quién en los Precios de Profeco y resuelve los siguientes incisos. Para el procesamiento de los datos y el análisis exploratorio debes usar Spark SQL en el lenguaje de programación de tu elección.
1. ¿Cuántos registros hay? 
2. ¿Cuántas categorías? 
3. ¿Cuántas cadenas comerciales están siendo monitoreadas (y, por lo tanto, reportadas en esa base de datos)? 
4. ¿Cuáles son los productos más monitoreados en cada estado de la república? 
5. ¿Cuál es la cadena comercial con mayor variedad de productos monitoreados? 

Ejercicio 2 
El archivo demo.csv contiene una tabla con información de aeropuertos en el mundo. 
Deberás: 1. Generar un diccionario a partir de la columna country (country_id,country) 
2. Escribir el diccionario como CSV desde spark 
3. Leer el CSV generado y hacer inner join con demo.csv El dataframe, después del inner join, debe tener el mismo número de registros que el archivo original. Se debe utilizar para este ejercicio necesariamente Spark 2.4 con Spark SQL.
