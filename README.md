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
![alt text](https://github.com/C-anwoy/OC-SVM/blob/main/Images/Non_linear_OCSVM.png?raw=true)

For Linear data:
![alt text](https://github.com/C-anwoy/OC-SVM/blob/main/Images/Linear_OCSVM.png?raw=true)
