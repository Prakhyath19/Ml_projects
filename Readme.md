# Detection of defective heart using a hybrid machine learning model.
### What deos this project do?
This project predicts the chances of a person having a defective heart.
### Platform used
This project is done in [googleColab]
### Algorithms used
1. [Logistic Regression]
2. [Gradient Boosting Classifier]
3. [Multi-Layer Perceptron]
4. [Voting Classifier]
### Input
Training data used is available in kaggle [Heart.csv]

### Working
The data is read and preprocessed for the usage.

Three models namely, _Logistic regression_, _Gradient boosting classifier_, _Multi-Layer Perceptron_ are trained on the same data which gives us the accuracies 82%,75%,85% respectively.

Using _voting classifier_ the three models are merged and form a Hybrid model which gives us better accuracy than individual predictions.

The final accuracy of the hybrid model is 87%.



[//]:#
[googleColab]:<https://research.google.com/colaboratory/>
[Heart.csv]:<https://www.kaggle.com/zhaoyingzhu/heartcsv>
[Logistic Regression]:<https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html>
[Gradient Boosting Classifier]:<https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjhxfD41ov2AhXM4zgGHVPZA78QFnoECDgQAQ&url=http%3A%2F%2Fscikit-learn.org%2Fstable%2Fmodules%2Fgenerated%2Fsklearn.ensemble.GradientBoostingClassifier.html&usg=AOvVaw2Di5F4WfMEDdgwCFwiB_zU>
[Multi-Layer Perceptron]:<https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html>
[Voting Classifier]:<https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.VotingClassifier.html>