# dMeans-Dimensionality-Reduction
Dimensionality reduction using the dMeans method. This algorithm allows, by calculating differences based on the means of each attribute.

Step-by-step


1. En la primera celda se incluyen las librerías necesarias para poder ejecutar el código que realiza el método de reducción de dimensionalidad, dMeans.

2. En la segunda celda, únicamente se establece la fuente de obtención del dataset (en este caso alojado en Google Drive). Este puede ser sustituido por cualquier otro método de lectura del dataset.

3. La función calculate_relevance_array, toma cada uno de los rasgos de tal manera que calcula la media aritmética entre los patrones de la clase Positive, y la clase Negative. Esto genera un valor numérico real por cada feature analizado. Finalmente, se crea un arreglo que incluye los índices de los features, y son ordenados de manera descendente, siendo el primero elemento el rasgo de mayor relevancia.
