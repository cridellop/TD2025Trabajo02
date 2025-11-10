Análisis Multicriterio para la Selección de Inversiones
Este repositorio documenta la aplicación de modelos de Decisión Multicriterio para un problema de selección de inversiones. El objetivo es clasificar y evaluar cinco alternativas de inversión basándose en un marco de evaluación jerárquico.

La estructura de decisión considera siete subcriterios fundamentales, agrupados en tres categorías principales:
Rentabilidad: (Retorno Esperado, Riesgo, Diversificación)
Compromiso: (Horizonte Temporal, Dedicación)
Operativa: (Liquidez, Comisiones)

Componentes del Proyecto
Los archivos principales de este repositorio son:
<strong><code>Trabajo02_cridellop.Rmd</code></strong> Documento R Markdown que sirve como el análisis central. Integra la definición del problema, el código de ejecución para los modelos y las conclusiones de los resultados.
<strong><code>Trabajo02_cridellop.html</code> / <code>.pdf</code></strong> Salidas compiladas del informe (formatos HTML y PDF), presentando el análisis final, las tablas y visualizaciones.
<strong><code>Inversion.ahp</code></strong> Archivo que define la jerarquía de 3 niveles y contiene las matrices de comparación 2 a 2 requeridas por la librería ahp.
<strong><code>teoriadecision_funciones_...R</code></strong> Scripts que contienen las funciones personalizadas de R necesarias para ejecutar los algoritmos.

Metodología Aplicada
El análisis compara los resultados de tres métodos fundamentales de MCDA:
AHP (Analytic Hierarchy Process): Utilizado para la ponderación sistemática de la jerarquía de criterios y la síntesis de las alternativas.
ELECTRE I: Método de superación implementado para identificar el núcleo de alternativas preferidas o no dominadas.
PROMETHEE (I y II): Métodos de superación para establecer un preorden parcial (PROMETHEE I) y un ranking completo (PROMETHEE II) basado en flujos de preferencia.

Para poder usar valores realistas en mi problema, he consultado las siguientes fuentes, dividas en varias categorías dependiendo del criterio, aunque no son excluyentes:
Retorno
https://tesoro.es/
https://www.investopedia.com/ask/answers/042415/what-average-annual-return-sp-500.asp?utm_source=chatgpt.com
https://www.visualcapitalist.com/charted-golds-annual-returns-2000-2025/?utm_source=chatgpt.com
https://global.morningstar.com/es/acciones/las-mejores-acciones-tecnolgicas-para-comprar
https://www.bitcoinmagazinepro.com/blog/a-decade-of-bitcoin-annual-returns-and-insights-for-investors/?utm_source=chatgpt.com

Riesgo
https://www.hartfordfunds.com/insights/market-perspectives/fixed-income/how-volatility-is-reshaping-bond-returns.html
https://www.nydig.com/research/comparing-bitcoin-and-gold?

Comisiones:
https://www.novatostradingclub.com/brokers/brokers-con-menos-comisiones/
