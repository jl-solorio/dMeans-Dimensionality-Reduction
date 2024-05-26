# dMeans-Dimensionality-Reduction
Dimensionality reduction using the dMeans method. This algorithm allows, by calculating differences based on the means of each attribute.

Step-by-step


1. The first cell includes the libraries needed to run the code that performs the dimensionality reduction method, dMeans.

2. In the second cell, only the source for obtaining the dataset (in this case hosted in Google Drive) is established. This can be replaced by any other method of reading the dataset.

3. The function calculate_relevance_array, takes each of the traits in such a way that it calculates the arithmetic mean between the patterns of the Positive class, and the Negative class. This generates a real numeric value for each analysed feature. Finally, an array is created that includes the indices of the features, and they are sorted in descending order, with the first element being the feature with the highest relevance.
