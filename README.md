## dMeans-Dimensionality-Reduction
Dimensionality reduction using the dMeans method. This algorithm allows, by calculating differences based on the means of each attribute.

Step-by-step dMeans_with_classifiers.ipynb

1. The first cell includes the libraries needed to run the code that performs the dimensionality reduction method, dMeans.
   
![imagen](https://github.com/jl-solorio/dMeans-Dimensionality-Reduction/assets/151310582/0f6313c2-faf0-46fd-b73d-f039b658a401)
 
2. In the second cell, only the source for obtaining the dataset (in this case hosted in Google Drive) is established. This can be replaced by any other method of reading the dataset.

![imagen](https://github.com/jl-solorio/dMeans-Dimensionality-Reduction/assets/151310582/67e3a235-de5f-42de-892b-e7e3cc31c165)

3. The function calculate_relevance_array, takes each of the traits in such a way that it calculates the arithmetic mean between the patterns of the Positive class, and the Negative class. This generates a real numeric value for each analysed feature. Finally, an array is created that includes the indices of the features, and they are sorted in descending order, with the first element being the feature with the highest relevance.
   
![imagen](https://github.com/jl-solorio/dMeans-Dimensionality-Reduction/assets/151310582/a44ba8b4-338e-4f21-a409-b418a9f8e58f)

4.  From this cell, functions are created for each classifier: 1-NN, 3-NN, 5-NN, SVM, Random Forest, Logistic, MLP and Adaboost. In each of these classifiers, a gradual feature integration method is integrated, and depending on the performance shown with a subset of features, it is established whether to terminate or continue running.

![imagen](https://github.com/jl-solorio/dMeans-Dimensionality-Reduction/assets/151310582/3552ddea-10b4-480c-b559-7df5651ca2e0)
![imagen](https://github.com/jl-solorio/dMeans-Dimensionality-Reduction/assets/151310582/5dece818-e4f3-4e99-a781-3491e7b52d9b)

5. Finally, a performance report is generated, showing which and how many features were necessary to reach its maximum performance.

![imagen](https://github.com/jl-solorio/dMeans-Dimensionality-Reduction/assets/151310582/3aae3e3f-cd1b-4e93-bffc-fab179d6a163)
