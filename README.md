El presente proyecto tiene como objetivo analizar la base de clientes de RetailMax mediante técnicas de aprendizaje no supervisado, específicamente el algoritmo K-Means. El propósito principal es identificar grupos homogéneos de clientes a partir de variables clave como la edad, el ingreso anual y la puntuación de gasto. A diferencia del aprendizaje supervisado, en este enfoque no se utilizan etiquetas, sino que se buscan patrones naturales en los datos que permitan comprender mejor el comportamiento de los clientes.

 Metodología

Se realizó primero un análisis exploratorio de datos (EDA) con el fin de comprender la distribución de las variables y sus relaciones. Posteriormente, se seleccionaron las características más relevantes para el clustering: Age, Annual Income (k$) y Spending Score (1-100). Estas variables fueron estandarizadas para asegurar que todas contribuyeran de manera equilibrada al modelo.

Se aplicó el algoritmo K-Means, evaluando distintos valores de K mediante el método del codo. Con base en este análisis, se seleccionó un número óptimo de clusters que permitió una segmentación equilibrada entre complejidad e interpretabilidad.

Resultados

El modelo permitió identificar distintos segmentos de clientes con características claramente diferenciadas. Entre los grupos más relevantes se encontraron:

Clientes con alto ingreso y alto gasto, considerados de alto valor para la empresa.
Clientes con alto ingreso pero bajo gasto, que representan una oportunidad importante de conversión.
Clientes jóvenes con gasto moderado-alto, potencialmente sensibles a campañas digitales.
Clientes con bajo ingreso y bajo gasto, que podrían requerir estrategias de bajo costo o fidelización.

La segmentación obtenida proporciona una visión estructurada del comportamiento de los clientes, permitiendo comprender mejor sus necesidades y patrones de consumo.

Recomendaciones para el equipo de marketing

Con base en los resultados obtenidos, se recomiendan las siguientes estrategias:

Diseñar campañas personalizadas para el segmento de alto valor, con beneficios exclusivos y programas de fidelización.
Implementar estrategias de conversión para clientes con alto ingreso pero bajo gasto, mediante ofertas personalizadas y recomendaciones de productos.
Potenciar campañas digitales dirigidas a clientes jóvenes, aprovechando su mayor receptividad a canales digitales.
Minimizar costos de adquisición en segmentos de bajo valor, enfocándose en estrategias automatizadas o de retención básica.
Conclusión

El uso de técnicas de clustering ha permitido transformar datos no estructurados en información accionable para la toma de decisiones. Esta segmentación proporciona una base sólida para que RetailMax optimice sus estrategias de marketing, mejore la experiencia del cliente y aumente la rentabilidad general. El siguiente paso recomendado es integrar variables adicionales como comportamiento de compra histórico o frecuencia de visitas para refinar aún más los segmentos obtenidos.
