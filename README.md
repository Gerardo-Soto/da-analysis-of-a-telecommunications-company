# da-analysis-of-a-telecommunications-company
The objective of the analysis is to identify usage patterns, detect atypical behavior, and understand which customer segments have different needs, in order to optimize the commercial offering and improve the user experience.

Proyecto de Análisis de Segmentación de Clientes – ConnectaTel
🎯 Objetivo del Proyecto

El objetivo de este proyecto es analizar el comportamiento de los usuarios de ConnectaTel para identificar patrones de uso, segmentar clientes según edad y nivel de consumo, detectar valores extremos (outliers) y generar recomendaciones estratégicas que permitan optimizar la oferta de planes y maximizar la rentabilidad.

Se busca traducir hallazgos estadísticos en decisiones accionables para el negocio.

🗂️ Datasets Utilizados

El análisis se basa en un dataset consolidado denominado:

user_profile

Este dataset contiene información agregada por usuario, incluyendo:

age → Edad del usuario

cant_mensajes → Cantidad de mensajes enviados

cant_llamadas → Cantidad de llamadas realizadas

cant_minutos_llamada → Total de minutos consumidos en llamadas

plan → Tipo de plan contratado

Durante el análisis se generaron columnas adicionales:

grupo_edad

grupo_uso

🔎 Etapas del Análisis Realizadas
1️⃣ Exploración de Datos (EDA)

Revisión de estructura y tipos de datos.

Análisis de estadísticas descriptivas.

Identificación de valores extremos mediante método IQR.

Evaluación de dispersión y asimetría.

2️⃣ Limpieza y Validación

Verificación de valores inconsistentes.

Análisis de límites superiores e inferiores.

Decisión estratégica sobre mantenimiento de outliers.

3️⃣ Segmentación

Creación de grupos por edad:

Joven

Adulto

Adulto Mayor

Creación de grupos por nivel de uso:

Bajo uso

Uso medio

Alto uso

4️⃣ Visualización

Histogramas para variables numéricas.

Countplots para variables categóricas.

Análisis comparativo por plan y segmentos.

5️⃣ Análisis Ejecutivo

Identificación de segmentos más valiosos.

Evaluación de patrones de consumo extremo.

Recomendaciones estratégicas para el negocio.

▶️ Cómo Ejecutar el Notebook
Opción 1: Google Colab (Recomendado)

Subir el archivo .ipynb a Google Drive.

Hacer clic derecho → "Abrir con" → Google Colab.

Verificar que el dataset esté cargado en el entorno.

Ejecutar las celdas en orden (Runtime → Run all).

Si el dataset es local:

Subir el archivo CSV manualmente.

Ajustar la ruta en la celda de carga de datos.

🔁 Guía de Reproducción del Análisis

Para replicar los resultados:

Cargar el dataset original.

Ejecutar el análisis exploratorio (estadísticas descriptivas).

Calcular límites IQR para detectar outliers.

Crear variables derivadas:

grupo_edad

grupo_uso

Generar visualizaciones.

Analizar distribución por segmentos.

Elaborar conclusiones estratégicas basadas en los hallazgos.

Es importante ejecutar el notebook en orden secuencial para garantizar que todas las variables derivadas estén correctamente creadas.

💡 Resultado Esperado

Al finalizar el análisis, se obtiene:

Segmentación clara de clientes.

Identificación de usuarios de alto valor.

Detección de patrones de consumo extremo.

Recomendaciones estratégicas para creación y optimización de planes.
