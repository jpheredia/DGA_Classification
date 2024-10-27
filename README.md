# Diseño y Evaluación de un Filtro de Dominios DGA
Los dominios generados automáticamente (DGA) son utilizados en ataques de ciberseguridad para evadir sistemas de defensa y establecer comunicaciones maliciosas. Este proyecto tiene como objetivo desarrollar un filtro para identificar dominios DGA a partir de un conjunto de datos que incluye características clave como la longitud del nombre de dominio, el conteo de n-gramas y la entropía.

## Descripción de los Datos
El DataFrame utilizado en este proyecto contiene las siguientes columnas:

- length: Longitud del nombre del dominio (variable numérica continua).
- ngram_count: Conteo de n-gramas presentes en el dominio (variable numérica continua).
- entropy: Medida de la aleatoriedad del dominio (variable numérica continua).
- type: Clasificación del dominio como DGA o legítimo (variable categórica).

## Objetivos
El proyecto se centrará en aplicar técnicas de análisis exploratorio de datos (EDA), entrenar y evaluar modelos de aprendizaje supervisado para clasificar dominios y seleccionar el modelo más efectivo basado en métricas de evaluación.