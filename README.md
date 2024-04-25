# Iris Species Classification Using Support Vector Machines

This project aims to develop a classification model that can identify the species of iris flowers by measuring their petals and sepals. The Iris dataset, a well-known machine learning benchmark dataset, contains samples of Setosa, Versicolor, and Virginica iris species. We used Python's Scikit-learn module to develop and evaluate the performance of a Support Vector Machine (SVM) classifier.

## Team Members

1. Anushuya Baidya - 101163891
2. Prayukti Dahal - 101145484
3. Binamra Neupane - 101169010
4. Nisha Lamgade - 101161837
5. Manisha Senchuri – 101162804

## Dataset

The Iris dataset consists of 150 samples, each with four features (sepal length, sepal width, petal length, and petal width). The target variable is the iris species, a categorical variable with three classes: 0 (Setosa), 1 (Versicolor), and 2 (Virginica). The dataset is available in the scikit-learn library.

## Data Exploration and Preprocessing

We performed exploratory data analysis (EDA) to understand the relationships between each attribute and its distribution using scatter plots and histograms. The data was split into features (X) and target variable (y), and then divided into training and testing sets using `train_test_split` from scikit-learn. Feature scaling was applied using `StandardScaler` to bring all features to a similar scale.

## SVM Implementation and Evaluation

The SVM classifier was built using the Scikit-learn toolkit, and several kernels (linear, polynomial, radial basis functions, and sigmoid) were experimented with to adjust hyperparameters. The model's performance was evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Cross-Validation

We assessed the model's generalization performance using 10-fold cross-validation with the `cross_val_score` function from scikit-learn. Different kernels were applied, and the resulting cross-validation scores varied between 0.93 and 1.0 for each fold, with an average cross-validation score of approximately 0.97.

## Results

The SVM classifier with the RBF kernel achieved the highest accuracy of 0.97, precision of 0.97, recall of 0.97, and F1-score of 0.97, indicating excellent performance in identifying iris species.

## Conclusion

Our team successfully developed and evaluated an SVM classifier that can identify iris flower species with high accuracy and overall performance across various evaluation criteria. Further research and validation are required to identify ways to enhance the model's effectiveness.