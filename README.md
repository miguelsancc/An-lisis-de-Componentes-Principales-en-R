# Anlisis de Componentes Principales en R

## Descripción
Este repositorio contiene dos archivos: un archivo CSV con datos sobre autos, que incluye variables como el año de fabricación, modelo, potencia y cilindrada, y un archivo R Markdown (Rmd) donde se realiza un Análisis de Componentes Principales (PCA) utilizando RStudio. El objetivo es mostrar las distintas funciones y librerías en R relevantes para realizar un PCA. Este proyecto se basa en una práctica de la asignatura de Minería de Datos de mi carrera universitaria.

## Archivos
- `autos.csv`: Contiene el conjunto de datos con varios atributos de autos.
- `PCA_analysis.Rmd`: Un archivo R Markdown que detalla los pasos y el código para realizar un PCA en el conjunto de datos de autos.

## Introducción
Principal Component Analysis (PCA) es un procedimiento estadístico utilizado para reducir la dimensionalidad de un conjunto de datos manteniendo la mayor parte de la variabilidad presente en los datos. Al transformar las variables originales en un nuevo conjunto de variables no correlacionadas llamadas componentes principales, el PCA ayuda a identificar la estructura subyacente en los datos.

En este proyecto, realizamos un PCA en un conjunto de datos que contiene información sobre varios autos. Las variables incluyen el año de fabricación, modelo, potencia, cilindrada y otras. El objetivo es demostrar la aplicación del PCA utilizando R e interpretar los resultados de manera efectiva.

## Datos
El conjunto de datos `autos.csv` contiene las siguientes variables:
- `year`: Año de fabricación
- `model`: Modelo del auto
- `power`: Potencia del auto
- `displacement`: Cilindrada del motor del auto
- Variables adicionales como peso, aceleración y precio

## Metodología
El análisis se realiza mediante los siguientes pasos:
1. Cargar las librerías necesarias: `FactoMineR`, `factoextra`, `ggplot2`, `corrplot`.
2. Cargar el conjunto de datos y preprocesar los datos (por ejemplo, eliminar variables categóricas, manejar valores faltantes).
3. Calcular la matriz de correlación para entender las relaciones entre las variables.
4. Realizar el PCA utilizando la función `PCA` del paquete `FactoMineR`.
5. Interpretar los resultados, incluyendo valores propios, varianza explicada y contribuciones de las variables.
6. Visualizar los resultados del PCA utilizando gráficos biplot y gráficos de correlación.

## Contribuciones
¡Las contribuciones son bienvenidas! Si tienes alguna sugerencia o mejora, no dudes en abrir un issue o enviar un pull request.


