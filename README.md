# OC-SVM
## Exploratory Project

### Brief Description:
We designed a Fuzzy One-Class Support Vector Machine classifier.

• Our model fuzzifies the crisp input data using a square membership function.

• Then, the model trains on the fuzzified data. The parameters learned are defuzzified to predict on the test dataset.

• In our algorithm, the model treats points of a particular class with varying importance which greatly reduces the sensitivity to outliers compared to traditional OCSVM models.

• Our model achieved great results and performed much better than scikit-learn's classical OCSVM model.

### Sample Results:

For Non-Linear 2D data:
![Non_linear_OCSVM](https://user-images.githubusercontent.com/57266914/212932133-58cf57f6-7324-4698-a228-32e667d6b659.png)

For Linear data:
![Linear_OCSVM](https://user-images.githubusercontent.com/57266914/212932090-cc591393-2af0-45b2-8cae-23582aae0605.png)

