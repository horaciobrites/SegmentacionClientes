# SegmentacionClientes (Clustering, Agrupamiento)
## 1. Introducción
En este estudio de caso nos centraremos en la comprension detallada de nuestros clientes, sus habitos de compra y caracteristicas socioeconomicas. Ademas, se llevara a cabo una evaluacion exhaustiva de la situacion actual y la efectividad de nuestras campañas de marketing con el proposito de mejorar la personalizacion del marketing, optimizar la asignacion de recursos, identificar oportunidades de mejora y facilitar la toma de decisiones estrategicas.

La personalizacion del marketing se ha convertido en un factor crucial para el exito. Conocer a fondo a nuestros clientes nos permite ofrecerles productos, servicios y experiencias que se ajusten especificamente a sus necesidades y preferencias, lo que a su vez aumenta la satisfaccion del cliente y lealtad a la marca. Sin embargo, para lograr esta personalizacion efectiva, es fundamental comprender en detalle quienes son nuestros clientes, como se comportan y que los motiva.

Con el objetivo de abordar estos desafios y mejorar nuestra estrategia de merketing, este estudio tiene como objetivo especifico segmentar a nuestros clientes en grupos mas homogéneos segun caracteristicas similares. Ademas, se evaluara el impacto economico de estas segmentaciones y se exploraran posibilidades de eficientizar nuestras campañas de marketing.

**Metodologia**

Para llevar a cabo este estudio, se utilizara un dataset preparado especificamente para este proposito. Este dataset contiene una gama de inofrmacion, incluyendo datos socioeconomicos, canales de compra, respuestas a campañas de marketing, historial de compreas entre otros. Esta informacion nos proporcionará una vision completa y detallada de cada uno de nuestros clientes, permitiendonos identificar patrones, tendencias y segmetarlos de manera mas efectiva.

*Preparación de datos:* Se realizará una limpieza y preparación exhaustiva del dataset para garantizar la calidad y consistencia de los datos.

*Análisis exploratorio de datos:* Se llevará a cabo un análisis exploratorio de los datos para entender mejor la distribución y características de las variables, identificar posibles correlaciones y patrones.

*Segmentación de clientes:* Utilizando kmeans, se agruparán a los clientes en segmentos más homogéneos según características similares.

*Evaluación del impacto económico:* Se evaluará el impacto económico de las segmentaciones, analizando métricas presupuestos de campaña en cada segmento, retorno de la inversion y otros.

*Identificación de oportunidades de mejora:* Se identificarán oportunidades de mejora en la estrategia de marketing, teniendo en cuenta los insights obtenidos de la segmentación y la evaluación del impacto económico.

*Desarrollo de recomendaciones y lineamientos futuros:* Se desarrollarán recomendaciones específicas para mejorar la personalización del marketing, optimizar la asignación de recursos y facilitar la toma de decisiones estratégicas, basadas en los hallazgos del estudio.

## 2. Preguntas iniciales
### 2.1. ¿Que caracteristicas generales tiene nuestra cartera de clientes?

Nivel de estudio predominante Graduado universitarios, seguidos por clientes que cuentan con algun posgrado, esto sugiere que nuestra base de clientes suele ser altamente educada y probablemente valora la calidad y sofisticacion en los productos que ofrece la empresa.
Mayoritariamente conviven en pareja, esto nos da una pauta de que podriamos enfocar nuestras estrategias de marketing en productos o servicios que sean atractivos para parejas o familias, como ofertas especiales para actividades compartidas.
La mayoria de los clientes tienen una familia de 3 integrantes. Nos da una pauta para el diseño de promociones y ofertas por cantidad.
La distribucion del ingresos tiene una media en 51 mil dolares, informacion importante para poder desarrollar una estrategia de precios correctamente.
Normalmente el canal de compra preferida es en tienda. Esto nos ayudaria a priorizar las promociones y disponibilidad de productos en las tienda fisicas.

### 2.2. ¿Cuales son los clientes mas relevantes?
**Insights Relevantes en Términos de Volúmenes de Ventas:**

*Clientes Relevantes:* Se destaca la relevancia de las personas en pareja y los graduados universitarios como segmentos clave en nuestra base de clientes.

*Canasta de Productos Más Relevantes:* Los productos de vinos y carne sobresalen como los más relevantes, especialmente entre clientes con educación universitaria.

*Productos por Rango de Edad y Nivel de Ingresos:* Se ha observado un alto volumen de ventas en vinos y carnes entre clientes de entre 35 y 60 años, con ingresos anuales en el rango de USD 60,000 a USD 80,000. Esta segmentación demográfica muestra una preferencia notable por estos productos.

*Volumen de Ventas en Vinos y Carnes en Familias de 2 y 3 Integrantes:* Se evidencia que las familias con 2 y 3 integrantes son las principales consumidoras de vinos y carnes, lo que sugiere una correlación entre el tamaño familiar y las preferencias de compra de estos productos.

*Correlación Entre Ingresos y Volumen de Compra:* Se observa una correlación esperada entre los ingresos y el volumen de compra, lo que indica que a medida que aumentan los ingresos, también lo hace el monto de las compras realizadas.

*Alta Correlación Entre Compras por Catálogo y Gastos en Carnes:* Existe una fuerte correlación entre las compras realizadas a través de catálogo y los gastos en productos cárnicos. Esto sugiere un comportamiento de compra específico entre nuestros clientes, particularmente cuando se trata de productos seleccionados por catálogo.

### 2.3. ¿Que porcentaje de nuestra cartera de clientes tuvo alguna queja de nuestro servicio?
Porcentaje de clientes que realizaron alguna queja: 0.89%

## 3. Descripcion de clusteres obtenidos
![image](https://github.com/horaciobrites/SegmentacionClientes/assets/38353865/70259438-33c6-405c-9394-dca1f3688844)

**Cluster A:**

- Este grupo está compuesto por 861 clientes, lo que representa un 38,51% de la cartera total.
- La media de gasto en compras de este cluster es de USD 1.255.
- El tamaño familiar promedio es de 2 integrantes.
- La mayoría de los clientes en este grupo no tienen hijos.
- El ingreso promedio anual de los clientes de este cluster es de USD 71.782.
- Representa el 80% del volumen de ventas

**Cluster B**

- Este cluster está conformado por 1375 clientes, lo que constituye un 61,49% de la cartera total.
- La media de gasto en compras de este grupo es de USD 199.
- En promedio, el tamaño familiar de este cluster es de 3 integrantes.
- Los clientes en este grupo tienen al menos un hijo.
- El ingreso promedio anual de los clientes de este cluster es de USD 39.535.
- Representa el 20% del volumen total de ventas

## 4. Resultados aplicados al marketing
![image](https://github.com/horaciobrites/SegmentacionClientes/assets/38353865/8bce610f-daa7-42f0-9d9f-b043dbef6181)

En el grafico observamos un conteo de las respuestas de los clientes a las campañas de marketing, donde "SI" son los clientes que compraron a partir de una campaña de marketing.
Lo que representa que la tasa de conversion del cluster A es de 36,7%, mientras que para el cluster B es del 10,6%.

**Presupuestos de campaña**
*Campaña de marketing para la cartera en general:* teniendo en cuenta que el costo por cliente de una campaña es de USD 3 y el ingreso esperado por cada cliente si es exitosa es de USD 11.
Costo total de la campaña   USD 6708
Ingresos previstos          USD 5082
Tasa de conversion          USD 20,66%
ROI                         0,75 ----> Estariamos perdiendo USD 0,25 por cada dolar invertido en marketing

*Campaña por clusteres*
Cluster A

Presupuesto campaña: USD 2583
Ingresos esperados:  USD 3476
Tasa conversion:     36,7 %
ROI                  1,34


Cluster B

Presupuesto campaña: USD 4125
Ingresos esperados:  USD 1606
Tasa conversion:     10.62 %
ROI                  0,38

## 5. Recomendaciones
*Enfoque en Segmento A:*
Se recomienda centrar los esfuerzos de marketing y promoción en el Cluster A, dada su mayor capacidad de generación de ingresos y su alta tasa de conversión.

*Personalización de Ofertas:*
Diseñar ofertas y promociones específicas que se ajusten a las preferencias y necesidades de cada segmento de clientes, aprovechando los insights obtenidos sobre los productos más relevantes y las características demográficas de cada grupo.

*Mejora Continua:*
Es importante realizar un seguimiento continuo y análisis de los resultados de las campañas de marketing, así como de los cambios en las características y comportamientos de nuestros clientes, para adaptar nuestras estrategias de manera efectiva y mantenernos competitivos en el mercado. Seria interesante realizar un sistema de scoring de los clientes para ordenarlos por mayor probabilidad de conversión

METADATA
https://www.kaggle.com/datasets/vishakhdapat/customer-segmentation-clustering
