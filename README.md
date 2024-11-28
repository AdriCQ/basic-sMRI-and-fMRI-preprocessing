# Preprocesamiento de Imágenes Anatómicas y Funcionales de ABIDE-I

Este repositorio contiene el código y la documentación relacionados con el preprocesamiento de imágenes funcionales y anatómicas del conjunto de datos ABIDE-I para el análisis de conectividad funcional cerebral. El pipeline está diseñado para preparar los datos de entrada necesarios para modelos de aprendizaje profundo, con un enfoque en la clasificación de sujetos con trastorno del espectro autista (ASD) y sujetos neurotípicos (TC).

---

## Descripción General

El preprocesamiento incluye:
- *Descarga de datos*: Obtención de imágenes anatómicas y funcionales preprocesadas de la colección ABIDE-I, proporcionadas por el proyecto *Preprocessed Connectomes Project (PCP) y datos crudos en formatos estandarizados (e.g., BIDS).
- *Preprocesamiento anatómico y funcional*: Implementación de un pipeline personalizado utilizando herramientas como FSL, Nilearn y NiBabel.
- *Extracción de series temporales promedio*: Obtención de señales de regiones de interés (ROIs) definidas por diversos atlas cerebrales.

---