# Análisis de Proyecto Sprint 7 - ConnectaTel

## Descripción del Proyecto
Este proyecto evalúa el comportamiento de los clientes de la empresa de telecomunicaciones **ConnectaTel** con el objetivo de optimizar la oferta comercial, reducir la tasa de cancelación (*churn*) e identificar ineficiencias en los patrones de uso de los servicios de llamadas y datos.

## Objetivos Principales
1. Analizar el perfil de consumo (llamadas, mensajes y tráfico de datos) de los usuarios.
2. Evaluar el desempeño comercial y la rentabilidad de los distintos planes tarifarios.
3. Probar hipótesis estadísticas sobre las diferencias de ingresos y uso entre segmentos de clientes.
4. Identificar clientes no rentables o ineficientes y proponer acciones de retención.

## Tecnologías y Herramientas Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías de Análisis:** Pandas, NumPy
* **Visualización de Datos:** Matplotlib, Seaborn
* **Entorno:** Jupyter Notebook / Google Colab

## Metodología y Pasos del Análisis
1. **Carga y Exploración Inicial:** Lectura de fuentes de datos, verificación de tipos y valores nulos.
2. **Preprocesamiento:** Limpieza, conversión de tipos de datos y cálculo de métricas acumuladas por usuario (minutos, SMS, GB).
3. **Análisis Exploratorio de Datos (EDA):** Distribución de consumo y detección de valores atípicos.
4. **Prueba de Hipótesis Estadísticas:** Tests t de Student para comparar ingresos promedio entre planes y regiones.
5. **Segmentación e Ineficiencias:** Análisis del impacto de llamadas perdidas y sobrecostos por excedentes.
6. **Conclusiones y Recomendaciones:** Formulación de estrategias comerciales basadas en evidencia de datos.

## Resultados y Hallazgos Clave
* Los clientes con recurrentes cobros por exceso de datos presentan la tasa de cancelación más alta.
* La diferencia de ingresos entre los planes evaluados es estadísticamente significativa ($p < 0.05$).
* Las llamadas no completadas se concentran en franjas horarias específicas, sugiriendo cuellos de botella operativos en la red.

## Instrucciones para Ejecutar el Proyecto
Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/github/paolz1710/telecom-analysis_SP7/blob/main/sprint7_final_project.ipynb)](sprint7_final_project.ipynb)

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**
