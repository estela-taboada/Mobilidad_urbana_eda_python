# Analisis Exploratorio y Economía de la Movilidad Urbana

## Contexto y Objetivo del Proyecto
Evaluar los patrones de desplazamiento, costos operativos y eficiencia del transporte urbano mediante análisis exploratorio de datos (EDA). El objetivo es identificar cuellos de botella, variaciones tarifarias y oportunidades de optimización logística para mejorar la rentabilidad y el flujo de movilidad.

## Metodología y Flujo de Trabajo
1. **Preparación y Limpieza de Datos (Python / Pandas):** Estandarización de formatos, manejo de valores faltantes, depuración de duplicados y validación de integridad en las variables de viaje y costos.
2. **Análisis Estadístico y Segmentación:** Evaluación de métricas clave por zona, horarios pico, distancias recorridas y estructura de tarifas.
3. **Detección de Anomalías:** Identificación de valores atípicos (*outliers*) en tiempos de traslado y costos operativos para evitar distorsiones en los indicadores.
4. **Visualización de Datos (Matplotlib / Seaborn):** Construcción de gráficos comparativos y distribuciones para comunicar hallazgos de forma ejecutiva.

## Hallazgos Clave
* **Concentración de Demanda por Franja Horaria:** Se identificaron picos marcados de saturación en horarios específicos que impactan directamente los tiempos de traslado y el costo por kilómetro.
* **Desviaciones en Costos Operativos:** El análisis de distribución permitió aislar trayectos con sobrecostos atípicos, señalando rutas donde la eficiencia logística puede optimizarse.
* **Oportunidades de Reasignación:** La segmentación geográfica evidenció zonas con alta demanda y baja cobertura eficiente, respaldando decisiones de redistribución operativa.

## Cómo explorar este proyecto
1. Haz clic en el archivo `analisis_movilidad_urbana.ipynb` en este repositorio para visualizar el código completo, tablas y gráficas generadas.
2. Para ejecutarlo de manera interactiva, descarga el archivo `.ipynb` y ábrelo en **Google Colab** o **Jupyter Notebook** con las librerías `pandas`, `numpy`, `matplotlib` y `seaborn`.
