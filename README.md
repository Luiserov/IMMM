# IMMM
Proyecto de programación

En el cuaderno de Jupyter que está en éste repositorio podemos encontrar un análisis exploratorio de la base de dadots del Índice de marginalización en México. 

## Limpieza de datos. 
Tuve que limpiar la base de datos, pues al cargarla, se trata de un archivo excel con columnas de encabezados y piés de peaginas. 
Tuve que transformar algunos data types, y guardar la información perteneciente a los totales nacionales. 

## Gráficas

Después hago algunas gráficas. 
Primero vemos una gráfica stacked, que por colores muestra el porcentaje de municipios con cada Grado de marginalización.
Después vemos la misma representación, pero ahora con el porcentaje de población total de cada entidad (no el número de municipios). 
También hago una matriz de correlación entre las variables para visualizar que variables tienen más correlación con otras. 
Por último visualizamos una gráfica de distribución. Cada punto representa un municipio. En el eje X vemos que % de la población de ese municipio vive en localidades con <5k habitantes y en el eje Y muestra el % de población >15 años que son analfabetas. Es evidente que las localidades con el 100% de la población en localidades de <5k habitantes, tienen mayores porcentajes de población >15 años que son analfabetas. 

