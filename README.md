Jupyter Notebook : https://github.com/Etavonni/Assignment17.1/blob/main/Assignment17.1.ipynb

Business Objective : Create a predictive model that identifies the key characteristics of clients who are likely to say "yes" to a long-term bank deposit. With this model, the bank can more accurately target a smaller, higher-quality group of potential customers.

1. The data was studied, cleaned and transformed to make it easy to use in a model.
2. Various models such as Logistic Regression, KNN, Decision Trees and SVM were used to model the data.
3. Comparison of the score showed that SVM has the best score for the test data.
                 Model  Train Time  Train Accuracy  Test Accuracy
0  Logistic Regression      0.9218          0.5895         0.5830
1                  KNN      0.0184          0.8914         0.8775
2        Decision Tree      0.1379          0.9171         0.8640
3                  SVM     15.9440          0.8873         0.8874

4. Various suggestions were provided to improve the model such as:
    Changing the following parameters :
      - number of neighbors in KNN
      - max depth or min samples leaf in the Decision Tree
      - max iter in Logistic Regression
      - penalty term or kernel type in SVM
