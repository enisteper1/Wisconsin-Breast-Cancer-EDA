<h1 align="center">
Wisconsin-Breast-Cancer-EDA
</h1>

<p align="center">
  <img src="https://www.rxdatascience.com/hubfs/Raj%20Files/es1.jpg" >
</p>

In this project we will show potential of the machine learning to enhance cancer detection accuracy while also speeding up diagnosis. On the other hand, humans rely on a small set of clearly quantifiable criteria to diagnose, machine learning may uncover deeper trends and patterns in test findings. Perhaps most crucially, machine learning has the potential to increase the percentage of patients detected early, which has been shown to treble cancer survival rates.

 Project will be done in 3 sections, these are:
1. Introduction & First Look
2. Preprocessing & Visualization
3. Train & Evaluation

## 1. Introduction & First Look
Required libraries will be imported and data will be read from **wdbc.data** file. Then, columns will be generated to name each feature and description of data will be shown.
<p align="center"><img src="https://user-images.githubusercontent.com/45767042/159067594-b8b4023b-a612-42e3-9307-afecba6ded15.png"></p>


## 2. Preprocessing & Visualization
Data will be scaled to drop computational power at traning section and outliers will be supressed to avoid machine learning algorithms to be biased because of outliers. Also, data will be visualized to understand how malignant and benign cells are differ from each other. At last, correlations will be shown both for both input input features and target feature.
<p align="center">
<img width=720 height= 480 src="https://user-images.githubusercontent.com/45767042/159067704-bb739863-3154-47e1-9eda-199203cccf8b.png">
</p>


## 3. Train & Evaluation
In this section 5 machine learning models will be trained at total, which are:

* SVM - Support Vector Machine
* Logistic Regression
* Random Forest
* Decision Tree
* KNN

After training each model their scores from different metrics will be shown to visualize their performances. Also, indices that model failed at prediction will be printed to understand reason of why machine learning model fails to predict that data. Then, their scores will be compared. After comparison, best model will be selected and commented, to understand reason of why it was better than others.
<h3 align="center">Logistic Regression Evaluation</h3>
<p align="center"><img src="https://user-images.githubusercontent.com/45767042/159067818-60cff9f3-3cc6-4913-b103-e6dca929a234.png"></p>
