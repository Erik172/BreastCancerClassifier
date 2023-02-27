# Clasificador de cáncer de mama utilizando K-Nearest Neighbors

Este es un proyecto de clasificación de cáncer de mama utilizando el algoritmo K-Nearest Neighbors en Python. El objetivo del proyecto es construir un modelo que pueda clasificar tumores en benignos o malignos utilizando un conjunto de datos de cáncer de mama.

## Datos
Los datos utilizados en este proyecto se obtienen del conjunto de datos de cáncer de mama de Wisconsin, disponible en Scikit-Learn. El conjunto de datos contiene 569 muestras de tumores de mama con 30 características cada una. Las características incluyen medidas físicas de los núcleos celulares, como el tamaño, la forma y la textura. La variable objetivo es una etiqueta binaria que indica si el tumor es benigno o maligno.

## Requisitos
- Python 3
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Implementación
El clasificador de cáncer de mama se implementa utilizando el algoritmo K-Nearest Neighbors. En resumen, el algoritmo funciona de la siguiente manera: cuando se presenta una nueva muestra, el algoritmo encuentra los "k" puntos de datos más cercanos en el conjunto de entrenamiento y toma una decisión basada en la mayoría de las etiquetas de las muestras cercanas.

El proyecto se divide en varias secciones. En primer lugar, se cargan los datos de cáncer de mama y se dividen en un conjunto de entrenamiento y un conjunto de validación. A continuación, se entrena el modelo utilizando el conjunto de entrenamiento y se evalúa el rendimiento del modelo en el conjunto de validación. Luego, se realiza un análisis de sensibilidad del hiperparámetro "k" para encontrar el mejor valor de "k". Finalmente, se entrena el modelo con el mejor valor de "k" y se realiza una predicción en el conjunto de validación.

## Resultados
El modelo de clasificación de cáncer de mama logra una precisión del 93,85% en el conjunto de validación utilizando el mejor valor de "k" encontrado. Se observa que la precisión del modelo varía según el valor de "k". Por ejemplo, para k = 1, el modelo logra una precisión del 92,11%, mientras que para k = 23, el modelo logra una precisión del 93,85%.

## Conclusiones
En este proyecto se implementó un clasificador de cáncer de mama utilizando el algoritmo K-Nearest Neighbors en Python. Se logró obtener un modelo que puede clasificar tumores de mama en benignos o malignos con una precisión del 93,85% en el conjunto de validación. La sensibilidad del modelo a los valores de "k" también se investigó y se encontró que el mejor valor de "k" para este conjunto de datos es 23. Este proyecto puede ser útil para quienes quieran implementar un modelo de clasificación de cáncer de mama utilizando K-NN o para aquellos interesados en aprender más sobre el algoritmo K-NN en Python.