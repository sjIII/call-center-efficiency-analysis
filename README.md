# Modelado de Eficiencia Operativa en Call Center 📞📊

## 🎯 Contexto del Problema (Negocio)
La retención de clientes y la velocidad de respuesta son métricas críticas para cualquier centro de contacto. El objetivo de este proyecto consistió en analizar múltiples conjuntos de datos masivos de un Call Center para diagnosticar de forma analítica y automatizada qué operadores presentaban ineficiencias en su desempeño diario. 

Para fines de este análisis, el negocio definió a un operador ineficaz bajo tres criterios operativos clave:
1. Alta tasa de llamadas entrantes perdidas (tanto de canales internos como externos).
2. Tiempo de espera prolongado para los clientes antes de ser atendidos.
3. Baja productividad en llamadas salientes realizadas (en los segmentos de operadores donde esta actividad fuera un requerimiento del puesto).

---

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Lenguaje Principal:** Python (Versión 3.x)
* **Manipulación y Procesamiento de Datos:** Pandas, NumPy
* **Análisis Exploratorio y Estadístico:** Matplotlib, Seaborn, Scikit-Learn
* **Consultas e Ingesta:** Pandas
* **Control de Versiones:** Git & GitHub

---

## 🏗️ Flujo del Proyecto (Acciones Realizadas)

### 1. Ingesta y Limpieza de Datos (Data Cleansing)
* Conexión y extracción estructurada de los registros del centro de contacto mediante un dataset en Pandas
* Procesamiento, unificación y saneamiento de los *datasets* crudos utilizando **Python (Pandas)** para eliminar valores nulos, corregir tipos de datos y estandarizar marcas de tiempo.

### 2. Análisis Exploratorio de Datos (EDA) y Segmentación
* Lógica aplicada en **Python** para segmentar a la plantilla de operadores en dos grupos operativos: los enfocados exclusivamente en atención entrante y aquellos con responsabilidades híbridas (llamadas salientes).
* Cálculo de métricas agregadas por operador para identificar distribuciones de tiempos de espera y tasas de abandono de llamadas.

### 3. Pruebas de Hipótesis Estadísticas
* Implementación de pruebas estadísticas con **Scikit-Learn** y librerías científicas para validar con un alto nivel de confianza la correlación real entre el incremento de los tiempos de espera y el decremento en la productividad individual.

---

## 🚀 Resultados del Análisis & Insights de Negocio
El modelo analítico arrojó conclusiones claras y accionables que fueron estructuradas para la toma de decisiones gerenciales:

* **Segmento de Llamadas Entrantes:** Se identificó con precisión que el **5% de los operadores** presentaban métricas de ineficacia debido a cuellos de botella en la atención y tiempos de espera fuera de los umbrales tolerables.
* **Segmento de Llamadas Salientes:** La ineficiencia operativa se elevó drásticamente a un **12% de los operadores** en este grupo, detectando una baja ejecución de llamadas salientes requeridas por el negocio.
* **Impacto Operativo:** A partir de estos *insights*, se propuso formalmente a la gerencia un **plan de capacitación focalizado** en los operadores detectados y una reestructuración de cargas de trabajo para optimizar la ventana de atención al cliente y mitigar las llamadas perdidas.

---

## 📂 Estructura del Repositorio
* `/data`: Carpeta con los archivos de datos (o instrucciones para descargarlos si son masivos).
* `/notebooks`: Contiene el Jupyter Notebook principal con todo el código documentado del EDA, limpieza y pruebas estadísticas.
