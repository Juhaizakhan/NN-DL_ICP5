## 1. Naïve Bayes Method Implementation

### Code Explanation:
This script first loads the 'glass' dataset from a CSV file using Pandas. It then splits the dataset into features (X) and the target variable (y). The data is further split into training and testing sets using the `train_test_split` function from scikit-learn. 

A Naïve Bayes classifier (`GaussianNB`) is initialized and trained using the training data. Then, predictions are made on the test data using the trained classifier. The accuracy of the model is calculated using the `score` method, and a detailed classification report is generated using the `classification_report` function.

## 2. Linear SVM Method Implementation

### Code Explanation:
Similar to the Naïve Bayes implementation, this script starts by loading the 'glass' dataset and splitting it into features (X) and the target variable (y). The dataset is then split into training and testing sets using `train_test_split`.

Next, a linear Support Vector Machine (SVM) classifier (`SVC` with `kernel='linear'`) is initialized and trained using the training data. Predictions are made on the test data using the trained classifier. 

Similarly, the accuracy of the model is calculated using the `score` method, and a detailed classification report is generated using the `classification_report` function.

## Accuracy Comparison and Justification

The accuracy comparison between Naïve Bayes and Linear SVM is based on the evaluation of both models on the test dataset. The Linear SVM algorithm achieved higher accuracy compared to Naïve Bayes. This is attributed to the SVM's ability to find a more flexible decision boundary and handle outliers more effectively. Additionally, SVMs are less sensitive to the distribution of data and can handle non-linear relationships between features, which could lead to better performance, especially when dealing with complex datasets.

## Video link 
[https://drive.google.com/file/d/1vEQeDWcqqDpTPttguvbY-UtuEz0UXjSQ/view?usp=sharing] 

JUHAIZA KHAN
700757258
