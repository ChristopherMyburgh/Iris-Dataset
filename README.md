# Iris-Dataset
Performing Multiple Clustering techniques on the Iris dataset

Using the Famour Iris Dataset, this repository contains 3 different classifiaction techniques used in order to classify our target data.

I have conducted Kmeans clustering. We created 3 groups based off the 3 different types of iris flowers. The model would classify each feature to each distinct group in accordance with how close the feature was, relative to the group. Ultimately, Kmeans produced a accuracy score of 44.64%

The 2nd method was to create multiple Dendograms and adjust each hyperparameter. In the end, I utilized complete linkage with euclidean distancing to perform Agglomerative Clustering. This method, albeit very similar to the Kmeans method, gave us a better clustering accuracy score as we had more parameters to play around with to help refine our model. In the end, we achieved a accuracy score of 58%.

The final clustering technique used was to perform a Principle Component Analysis of the Dataset. PCA allowed us to identify which features were most important to the classification of our target variables. During the assignment, We found that of the 4 main features, 92.46% of the exlpanatory assumptions could be found within the first Principle Component. What this means, is that when conducting a PCA report, if we were to get rid of 75% of the feature data, we would stil;l have a 92.46% confidence level to classify our data correctly.

## Tools
The project consisted of utilizing SkLearn Library to employ the various clustering techniques.

MatplotLib as well as Seaborn was used to display the data.
