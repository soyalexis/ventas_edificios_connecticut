# Análisis de venta de edificios en Connecticut
Estuve trabajando en una base de datos de ventas de edificios para mejorar mis habilidades.

Librerías usadas:

pyspark.sql import SparkSession hashtag#Sesión para uso de spark

pyspark.sql.functions as F hashtag#Funciones spark

pandas as pd hashtag#Tratamiento de datos

seaborn as sns hashtag#Gráficos

matplotlib.pyplot as plt hashtag#Gráficos

urllib.request import urlopen hashtag#Carga de información en línea

json hashtag#Análisis de archivos Json

plotly.express as px hashtag#Graficación de mapas

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

En el mundo actual de los negocios, la capacidad de analizar datos de manera efectiva se ha convertido en una habilidad esencial para la toma de decisiones. En este sentido, vamos a realizar un análisis de los datos de ventas de edificios de Connecticut para comprender el comportamiento del mercado inmobiliario en la región.

Para llevar a cabo este análisis, utilizaremos las bibliotecas Pandas y Pyspark, reconocidas por su eficacia en la extracción y transformación de datos. Estas herramientas nos permitirán manejar grandes volúmenes de información de manera eficiente, facilitando la identificación de tendencias y patrones significativos en los datos de ventas.

Además, para la visualización de los resultados, haremos uso de las bibliotecas Seaborn, Matplotlib y Plotly. Estas herramientas nos brindarán la posibilidad de crear gráficos claros y concisos que nos ayudarán a comunicar efectivamente los hallazgos de nuestro análisis.

En resumen, el análisis de los datos de ventas de edificios de Connecticut nos permitirá obtener información valiosa sobre el mercado inmobiliario en la región, lo cual nos ayudará a tomar decisiones estratégicas fundamentadas en datos sólidos. Gracias a la combinación de herramientas como Pandas, Pyspark, Seaborn, Matplotlib y Plotly, estaremos en una posición óptima para realizar un análisis exhaustivo y riguroso que nos permita maximizar el valor de la información obtenida.

# Veamos algunos gráficos que se realizaron durante el análisis.

# Scatterplot: Comparación de Ventas en 2011 y 2013

Para comenzar el análisis visual, se ha creado un scatterplot utilizando la librería Seaborn. En esta representación gráfica, se contrastan las ventas de propiedades entre los años 2011 y 2013. Esta comparativa muestra de forma clara la diferencia entre un año con ventas bajas (2011) y otro con ventas elevadas (2013). El scatterplot ayuda a identificar posibles patrones, valores atípicos y la distribución general de las ventas en estos dos años clave, ofreciendo una comprensión visual de la variabilidad en el mercado inmobiliario durante ese periodo.

![image](https://github.com/soyalexis/ventas_edificios_connecticut/assets/127549771/c1695dc5-9caf-4d41-a3e3-976452b215a6)

En el scatterplot presentado, se puede observar claramente el efecto de los outliers en cada uno de los años analizados. Es notable que en el año 2011, la propiedad con el precio tasado más alto se vendió a un precio significativamente menor, lo que se refleja en el punto atípico en el gráfico. Por otro lado, en el año 2013, estos casos de discrepancia entre el precio tasado y el precio de venta disminuyeron.

# Boxplot: Distribución de Valores Tasados y de Ventas por Tipos de Propiedad

Para complementar el análisis visual, se presentan boxplots que ilustran la distribución de los valores tasados y de ventas para diferentes tipos de propiedad. Esta representación gráfica permite observar la variabilidad en los datos y proporciona información sobre la dispersión y posibles outliers en cada categoría.

Al examinar los boxplots, se observa una dispersión significativa en los valores tasados y de ventas para las propiedades sin información especificada, destacándose por su alta variabilidad en comparación con otras categorías. Sin embargo, esta variabilidad no se refleja de la misma manera en el ratio de ventas. En este caso, las propiedades de la categoría "Familia de cuatro" muestran una mayor dispersión en los ratios de ventas, indicando una variabilidad considerable en la relación entre los valores tasados y de ventas para esta categoría en particular.

![image](https://github.com/soyalexis/ventas_edificios_connecticut/assets/127549771/376338c3-4516-498c-ab97-11910a35a969)

![image](https://github.com/soyalexis/ventas_edificios_connecticut/assets/127549771/9deae32e-7830-43d8-8094-ada330ff4e2f)

# Conclusiones
En este análisis se identificaron varios puntos clave para entender el mercado inmobiliario en Connecticut:

Facilidad para manejar bases de datos: Se demostró la capacidad de gestionar y manipular grandes conjuntos de datos usando Pyspark y Pandas, lo que facilita el procesamiento y análisis eficiente de la información.

Comportamiento diferencial por año y condado: Se observaron variaciones importantes en el comportamiento del mercado inmobiliario según el año y el condado, lo que resalta la importancia de analizar los datos específicamente para cada área geográfica y período de tiempo.

Uso efectivo de mapas para patrones de venta: Se implementaron mapas interactivos que permiten una visualización rápida y precisa de los patrones de venta de propiedades por condado. Esta técnica sirvió para identificar tendencias geoespaciales y disparidades regionales en el mercado.

Ideas clave para visualizaciones y filtros futuros: Se generaron ideas para las visualizaciones y los filtros a incorporar en futuras implementaciones. Estos incluyen la exploración detallada de tipos de propiedad, análisis comparativos por condado y la integración de datos adicionales para enriquecer el análisis.

Oportunidades para el desarrollo de modelos de Machine Learning: Se identificaron oportunidades para el desarrollo de modelos de Machine Learning, especialmente al considerar variables como tipo de propiedad, condado y otros factores adicionales. Estos modelos pueden proporcionar insights predictivos valiosos para el mercado inmobiliario.

En resumen, este notebook proporciona una sólida base para futuros análisis y desarrollos en el campo del mercado inmobiliario en Connecticut. Las observaciones y conclusiones obtenidas aquí son esenciales para guiar el camino hacia una comprensión más profunda y precisa del mercado, lo que puede llevar a decisiones estratégicas informadas en el futuro.


