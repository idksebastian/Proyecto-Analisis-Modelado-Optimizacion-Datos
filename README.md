# Proyecto de Analítica de Datos – Empleo Público en Colombia  
## Metodología ASUM-DM y Redes Neuronales

Este repositorio contiene el desarrollo completo del proyecto de analítica de datos del curso, aplicando la metodología **ASUM-DM** desde la comprensión del problema hasta la evaluación y comunicación de resultados.  
El proyecto incluye análisis exploratorio de datos (EDA), preparación y limpieza, modelado mediante **redes neuronales**, optimización del modelo y documentación de los resultados obtenidos.

---

## Equipo de Trabajo (5 integrantes)

- **Nicolás Quintana** — Rol: adquisición y limpieza de datos  
- **Sebastián Lizarazo** — Rol: documentación y bitácoras  
- **Juan Marín** — Rol: análisis exploratorio de datos (EDA)  
- **Christian Joven** — Rol: modelado, métricas y evaluación  
- **Yeisson Romero** — Rol: soporte técnico, validación del repositorio y apoyo en modelado  

---

## Objetivo del Proyecto

Realizar un análisis exhaustivo del empleo público en Colombia utilizando el dataset **“Caracterización del Empleo Público”**, con el fin de identificar patrones, tendencias y relaciones relevantes entre variables laborales y sociodemográficas.  
Adicionalmente, se busca construir y optimizar un modelo predictivo basado en **redes neuronales** para estimar el **salario mensual promedio**, justificando las decisiones técnicas y evaluando su desempeño mediante métricas cuantitativas.

---

## Dataset Seleccionado

- **Nombre:** Caracterización del Empleo Público  
- **Fuente:** Portal de Datos Abiertos del Estado Colombiano – Datos.gov.co  
- **Entidad responsable:** Departamento Administrativo de la Función Pública  
- **Descripción:**  
  El conjunto de datos contiene información detallada sobre los servidores públicos registrados en el Sistema de Información y Gestión del Empleo Público (SIGEP). Incluye variables relacionadas con el perfil laboral y sociodemográfico, tales como tipo de entidad, sector administrativo, tipo de vinculación, nivel jerárquico, nivel educativo, género y variables salariales.
- **Periodicidad:** Actualización periódica  
- **Relevancia para el proyecto:**  
  La amplitud y nivel de detalle del dataset permiten realizar análisis exploratorios profundos y aplicar técnicas de analítica avanzada e inteligencia artificial, justificando el uso de modelos no lineales como las redes neuronales.

---

## Metodología Aplicada: ASUM-DM

El proyecto se desarrolló siguiendo las fases de la metodología **ASUM-DM**, documentadas tanto en el notebook como en el informe final en PDF:

1. **Comprensión del problema**  
   Definición del objetivo analítico y selección del enfoque basado en redes neuronales.

2. **Comprensión de los datos**  
   Exploración inicial del dataset, análisis de tipos de datos, valores faltantes, escalas y distribución de variables.

3. **Análisis Exploratorio de Datos (EDA)**  
   Visualizaciones, identificación de patrones, detección de anomalías y formulación de conclusiones clave que fundamentaron el modelado.

4. **Preparación de los datos**  
   Limpieza, imputación de valores faltantes, codificación de variables categóricas, normalización de variables numéricas y partición en conjuntos de entrenamiento y prueba.

5. **Modelado**  
   Construcción de una primera red neuronal como línea base para la predicción del salario mensual promedio.

6. **Optimización del modelo**  
   Ajustes en la arquitectura y el preprocesamiento, incluyendo la normalización de la variable objetivo, aumento de neuronas y épocas de entrenamiento, con evidencia comparativa mediante métricas.

7. **Evaluación y comunicación de resultados**  
   Comparación entre el modelo inicial y el modelo optimizado utilizando RMSE y MAE, análisis de los resultados y conclusiones finales.

---

## Modelo Utilizado

- **Tipo de modelo:** Red neuronal artificial (Deep Learning)  
- **Propósito:** Predicción del salario mensual promedio  
- **Justificación:**  
  El comportamiento del salario presenta relaciones complejas y no lineales con múltiples variables, lo que hace adecuado el uso de redes neuronales frente a modelos lineales tradicionales.

Se construyeron dos versiones del modelo:
- **Modelo inicial:** arquitectura básica como línea base.
- **Modelo optimizado:** ajustes en la arquitectura y en el escalado de la variable objetivo, logrando una mejora significativa en el desempeño.

---

## Evaluación y Resultados

El desempeño de los modelos fue evaluado mediante las métricas **RMSE** y **MAE**.  
Los resultados evidencian una reducción significativa de los errores en el modelo optimizado frente al modelo inicial, demostrando la efectividad del proceso de optimización y del preprocesamiento aplicado.

---

## Entregables

- **Repositorio público en GitHub**  
- **Notebook en Google Colab** con todo el proceso documentado  
- **Informe final en PDF** que incluye:
  - Metodología ASUM-DM  
  - EDA y conclusiones  
  - Modelado con redes neuronales  
  - Optimización y comparación de resultados  
  - Conclusiones finales  

---

## Avances del Proyecto

✔ Selección y validación del dataset oficial  
✔ Creación y organización del repositorio en GitHub  
✔ Limpieza y preparación de los datos  
✔ Análisis exploratorio exhaustivo (EDA)  
✔ Construcción de red neuronal inicial  
✔ Optimización del modelo con evidencia comparativa  
✔ Documentación completa en notebook y README  

---

## Observaciones Finales

Este proyecto evidencia la importancia de la correcta preparación de los datos y del enfoque iterativo en analítica de datos. La aplicación de redes neuronales permitió capturar patrones complejos en el empleo público colombiano, demostrando el valor de las técnicas de inteligencia artificial en el análisis de datos reales.
