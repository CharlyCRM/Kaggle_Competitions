# Cuadernos de aprendizaje de machine learning

Aquí reúno ejercicios de la etapa en la que estaba aprendiendo a preparar datos, construir pipelines y evaluar modelos. Los casos de vivienda y Titanic me sirvieron para recorrer el proceso completo, desde la exploración hasta las primeras predicciones.

Es material de formación, no una colección de resultados de competición verificados. No atribuyo posiciones en rankings ni un rendimiento validado fuera de estos ejercicios.

## Qué encontrarás

- [California Housing](California_Housing.ipynb): exploración de datos de vivienda, muestreo, imputación, codificación, escalado y comparación de regresión lineal, árboles y random forest. Incluye validación cruzada y búsqueda de hiperparámetros.
- [Titanic](Titanic_Machine_Learing_from_Disaster.ipynb): preparación de variables y un árbol de decisión para estudiar la supervivencia de pasajeros.
- `NY-House-Dataset.csv`: archivo de datos conservado de otra práctica. El repositorio no incluye un tercer cuaderno de análisis de Nueva York.

## Cómo leerlos

Puedes abrir los notebooks directamente en GitHub. Las salidas guardadas reflejan ejecuciones del entorno original, no una evaluación actual ni una garantía de reproducción con versiones nuevas.

California Housing busca `housing.csv`, que no está incluido. El cuaderno de Titanic conserva la ruta configurada durante el ejercicio. Antes de ejecutar, revisa esas rutas, consigue los datos correspondientes y comprueba las librerías importadas. Algunas imágenes y archivos externos tampoco forman parte del repositorio.

Para trabajar en local necesitas Jupyter y las dependencias de cada cuaderno: pandas, NumPy, scikit-learn y las librerías de visualización utilizadas. Titanic también usa Graphviz. No hay un entorno de versiones fijado.

## Qué me aportaron

Estos ejercicios me ayudaron a separar preparación de datos, entrenamiento y evaluación, y a comparar un modelo sencillo con alternativas más flexibles. Los conservaría como punto de partida para rehacer una evaluación reproducible, no como evidencia de que un modelo está listo para producción.

La predicción de vivienda es un caso didáctico, no una recomendación de inversión. Antes de reutilizar datos o material de estos cuadernos, revisa sus fuentes y condiciones de uso.

Para ver proyectos más recientes con aplicaciones y pruebas, puedes visitar [mi portfolio](https://carlos-ramirez-martin.up.railway.app/es/).
