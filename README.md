# Instructivo de Desarrollo de la Prueba Técnica - Hitss
#### Este instructivo describe el proceso de desarrollo, análisis y entrega de la prueba técnica para la vacante de Analista de Datos Estándar, realizada con base en las instrucciones proporcionadas. El flujo de trabajo incluye programación en Python, procesamiento de datos, visualización interactiva en Power BI y documentación técnica en PDF, todo alojado en un repositorio de GitHub.

## 1. Desarrollo del Proceso en Python
#### El desarrollo inicial de la prueba se realizó mediante el archivo '2. Desarrollo_Prueba_Hitss.py'. En este script se implementaron procesos de limpieza, transformación y análisis de datos utilizando librerías como pandas y scikit-learn. Las metodologías aplicadas incluyeron:
#### - ETL (Extracción, Transformación y Carga) para estandarización de columnas y conversión de formatos. 
#### - Clustering con KMeans para segmentación de planes móviles. 
#### - Regresión lineal múltiple para predicción del cargo fijo mensual (CFM_TOTAL) por cliente.

## 2. Generación de la Tabla Final en Excel
#### Como resultado del procesamiento de datos, se generó el archivo '3. Tabla_final.xlsx', el cual consolida todas las variables limpias y enriquecidas: tipo de plan, valores de CFM_VOZ, CFM_DATOS, recurso en GB, cliente, municipio, departamento, datos ilimitados y segmentación por clúster. Este archivo fue cargado en Power BI para su representación gráfica.

## 3. Construcción del Tablero Interactivo en Power BI
#### El archivo '4. Tablero Prueba Hitss.pbix' contiene el dashboard desarrollado con Power BI Desktop, estructurado en el análisis descriptivo del reporte consolidado. Se incorporaron gráficos de dispersión, barras apiladas, mapas interactivos y tablas dinámicas para representar visualmente el comportamiento de los planes móviles.

## 4. Documento de Análisis y Conclusiones
#### Finalmente, se generó un documento PDF ’5. Análisis Exploratorio y Conclusiones’ que resume el análisis exploratorio, identifica patrones relevantes, presenta insights tácticos y emite recomendaciones estratégicas. Este documento integra todos los hallazgos obtenidos a lo largo del análisis técnico.

## 5. Repositorio GitHub
#### Todos los archivos mencionados (script en Python, tabla final, archivo de Power BI y documento PDF) están disponibles en el siguiente repositorio público: https://github.com/DanielFernandoMC/Prueba_Tecnica_Hitss.git
