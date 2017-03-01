# EST-25134 Aprendizaje Estadístico

## Repositorio de datos

Este es el repositorio de datos para el curso Aprendizaje Estadístico de Primavera 2017. Aquí encontramos tanto los datos que estaremos estudiando en el curso. 

### Datos

* `EST25134_DanishInsuranceMultivariate_Data.Rdata` - Datos de reclamos de siniestros de un portafolio de seguros de vivienda

* `EST25134_Curve_Data.Rdata` - Datos asociados a una curva de respuesta univariada 

* `EST25134_ClasifSup.Rdata` - Datos simulados para clasificacion supervisada (Y-variable dicotomica, (X1,X2)-estimulos continuos)

* `EST25134_Pregnancy.Rdata` - Datos reales sobre embarazos prematuros en mujeres de EEUU (Y-variable dicotomica, X1-variable de estimulo, (Z1-Z4)-estimulo control).
  

## Importación en R

Empleando la libreria `repmis` de R, podemos importar los datos directamente de un repositorio en la web. Por ejemplo, para cargar los datos en R de la tabla de reclamos de seguros de vivienda en Dinamarca empleamos: 

```
library(repmis)

source_data("https://github.com/jcmartinezovando/est25134_2017a/blob/master/datos/DanishInsuranceMultivariate_Data.RData?raw=true")
```
Noten que debemos especificar el path de los datos desde el repositorio en GitHub; este lo pueden encontrar seleccionando la opción `Copy path` que se despliega al seleccionar cada archivo da datos. Noten también que al final de la instrucción se incluye la especificación libre de formato para el archivo por importar.

Reemplazando el nombre del archivo a importar por el correspondiente en nuestro código hará accesible los datos en R.
