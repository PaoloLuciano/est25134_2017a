# EST-25134 Aprendizaje Estadístico

## Repositorio de datos

Este es el repositorio de datos para el curso Aprendizaje Estadístico de Primavera 2017. Aquí encontramos tanto los datos que estaremos estudiando en el curso. 

### Datos

* `AllstateClaim_DataShort.Rdata` - Datos de reclamos de siniestros de un portafolio de seguros de autos
* `DanishInsuranceMultivariate_Data.Rdata` - Datos de reclamos de siniestros de un portafolio de seguros de vivienda

## Importación en R

Empleando la libreria `repmis` de R, podemos importar los datos empleando las siguientes instrucciones

```
library(repmis)

source_data("https://github.com/jcmartinezovando/est25134_2017a/blob/master/datos/AllstateClaim_DataShort.RData?raw=true")
```
Noten que debemos especificar el path de los datos desde el repositorio en GitHub.
