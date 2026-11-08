# Apuntes de R y Aprendizaje Automático

Apuntes personales organizados por tema. Cada apunte es un notebook de Google Colab (entorno R).

## Índice

| Carpeta | Contenido |
|---|---|
| [`01-r-basico`](01-r-basico/) | Sintaxis, tidyverse, data.table, funciones |
| [`02-eda-y-visualizacion`](02-eda-y-visualizacion/) | Análisis exploratorio y ggplot2 |
| [`03-preprocesamiento`](03-preprocesamiento/) | Faltantes, feature engineering, balanceo de clases |
| [`04-modelos`](04-modelos/) | Árboles, random forest, LightGBM, regresión |
| [`05-evaluacion`](05-evaluacion/) | Validación cruzada, métricas, optimización de hiperparámetros |
| [`snippets`](snippets/) | Trozos de código reutilizables (.R) |

# Estructura de cada apunte
## 1. Intuición
   Qué problema resuelve, con un ejemplo simple.
## 2. Conceptos y fórmulas
   Cada concepto: en palabras → símbolo → cómo se lee.
   Fórmula completa leída como receta.
## 3. Flujo interno del modelo
   Tabla: paso → qué hace → fórmula → para qué sirve
   (preparar → entrenar → predecir → evaluar → interpretar)
## 4. Código en R
   4.1 Datos y train/test
   4.2 Entrenar (lm / glm / svm)
   4.3 Predecir y evaluar (métricas)
   4.4 Interpretar (coeficientes, odds ratio, etc.)
## 5. Supuestos y límites
   Qué dice cada uno, qué rompe, cómo se detecta y cómo se corrige.
   Cuándo usar este modelo y cuándo no.
## 6. Resumen y errores comunes
   Frases para el examen y confusiones típicas (ej. ε vs e, odds vs probabilidad).
## Convenciones
- Nombres de archivo en minúscula y con guiones: `lightgbm-basico.ipynb`
- No se suben datos pesados ni sensibles; solo links de descarga o ejemplos chicos en `datos/`
