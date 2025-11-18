# Análisis de Arrestos en Nueva York: Pobreza, Crimen y Escuelas

## Descripción del proyecto
Este proyecto tiene como objetivo analizar los **factores socioeconómicos y delictivos asociados a los arrestos en la ciudad de Nueva York**, utilizando técnicas de procesamiento de datos a gran escala (*Big Data*).  

A partir de tres fuentes principales —**pobreza, criminalidad en escuelas y registros de arrestos**— se busca identificar **relaciones entre desigualdad social, entorno educativo y tasas de detención**, aplicando análisis exploratorio y modelos estadísticos.

---

## Objetivos
- Analizar cómo se distribuyen los arrestos entre los distintos distritos de Nueva York.  
- Evaluar la relación entre los niveles de pobreza y el número de arrestos.  
- Explorar si las zonas con mayor índice de criminalidad escolar presentan también más arrestos.  
- Identificar patrones y correlaciones significativas que puedan ayudar a comprender las causas del incremento de arrestos.
- Evaluar si los distritos con mayor pobreza presentan también más arrestos.
- Analizar la relación entre criminalidad escolar y acciones policiales.
- Identificar factores sociodemográficos que determinan vulnerabilidad.
- Construir modelos predictivos que permitan detectar perfiles de riesgo.
-   Generar insumos para la toma de decisiones basadas en evidencia pública.
---

## Estructura del repositorio

| Archivo | Descripción |
|----------|--------------|
| `Proyecto_Arrestos.ipynb` | Análisis, visualización y modelos relacionados con arrestos. |
| `Proyecto_Escuelas.ipynb` | Análisis de criminalidad escolar y clustering.|
| `Proyecto_Pobreza.ipynb` | Procesamiento de datos de pobreza, correlación y modelo MLP. |
| `Proyecto_Preguntas_Clave.ipynb` | Análisis exploratorio y respuestas a las preguntas iniciales. |
| `Presentación - Análisis de Arrestos en NYC.pdf` | Presentación final del proyecto. |
| `Entrega II Proyecto Procesamiento de Datos.pdf` | Documento completo de análisis, metodología y conclusiones.|
---

## Metodología
1. **Importación de datos de fuentes públicas (Open Data NYC).**  
2. **Preprocesamiento y limpieza de datos:** manejo de nulos, formatos, unión de datasets y normalización.  
3. **Análisis exploratorio (EDA):** visualizaciones y estadísticas descriptivas por distrito y variable.  
4. **Modelado y correlación:** uso de regresiones y correlaciones para medir la relación entre pobreza, crimen y arrestos.  
5. **Evaluación:** interpretación de resultados y generación de conclusiones basadas en evidencia.

---

## Tecnologías y herramientas utilizadas
- **Python 3.10+**
- **PySpark / MLlib**
- **Pandas / NumPy / Matplotlib / Seaborn**
- **Keras / TensorFlow (para modelos predictivos) (próximamente)**
- **Jupyter Notebooks**

---

## Modelos aplicados

### K-Means (Clustering)
- Agrupa escuelas según intensidad y tipo de incidentes.
- Identifica perfiles de riesgo escolar.
- Permite visualizar zonas críticas asociadas a vulnerabilidad social.

### Random Forest (Clasificación)
- Maneja datos complejos sin suposiciones estrictas.
- Identifica las variables que más influyen en los arrestos.
- Ofrece interpretabilidad mediante *feature importance*.

### Multilayer Perceptron – Deep Learning
- Modelo supervisado para predecir pobreza.
- Más del **99.6% de accuracy y F1-Score**.
- Aprende relaciones no lineales entre ingresos, vivienda, educación y estructura familiar.
- Robusto frente a cambios de arquitectura y parámetros.
---

## Resultados esperados
- Identificación de los distritos con **mayor tasa de arrestos** y su relación con los índices de pobreza.  
- Análisis de la **correlación entre crimen escolar y arrestos**.  
- Generación de **insights visuales** que faciliten la comprensión del fenómeno desde un punto de vista social y territorial.  

---

## Autores
- **Diego Alejandro Jara Rojas**  
- **Juan Felipe González Quintero**  
- **Tomás Felipe Guerra Hernández**  
- **Isaías Acosta Herrera**

---

## Universidad
**Pontificia Universidad Javeriana**  
Facultad de Ingeniería — Departamento de Ingeniería de Sistemas  
**Curso:** Procesamiento de Datos a Gran Escala  
**Periodo:** 2025-2

---

## Referencias
- [Open Data NYC](https://opendata.cityofnewyork.us/)  
- [NYPD Arrest Data](https://www.nyc.gov/site/nypd/stats/reports-analysis/arrest.page)  
- Department of Education NYC
- Artículos académicos sobre desigualdad y criminalidad urbana.

---

## 💬 Licencia
Este proyecto se publica con fines académicos bajo la **Licencia MIT**.
