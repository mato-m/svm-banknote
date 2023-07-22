# Support vector machine - Bank note authentication

#### Dataset

[Dataset](https://www.kaggle.com/datasets/ritesaluja/bank-note-authentication-uci-data) was downloaded from Kaggle. It contains data about bank note feature
that was extracted from images. It has 5 numeric columns of varioous parameters. Columns Variance, Skewness, Curtosis and Entropy represent various
parameters extracted from images, while column Class represents whether the bank note is authentic or not. There's a total of 1372 rows in the dataset.

#### Support vector machine (SVM)

SVM only supports binary classification, which means it can only have two output classes. SVM finds the optimal hyperplane that seperates the two classes.
The dimension of the hyperplane is the same as the number of input features. For example, data on 2D plot is separated by a straight line (2D object). 

#### Model

Model achieved 99.5% accuracy and 99.2% recall, which means that the model is very accurate on the current data. In order for data to be visually represented
onto a 2D plot we use Principal Component Analysis (PCA) in order to reduce the number of input dimensions.

![image](https://github.com/mato-m/svm-banknote/assets/64593617/5d974ef3-2f88-4304-ac03-8967b7f12d77)
