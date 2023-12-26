# Iris Flower Classification with Logistic Regression
Utilizing the sklearn.datasets Iris flower dataset, this project employs logistic regression to classify flowers into
1. Setosa
2. Versicolour
3. Virginica
based on features like:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width.
The accuracy of the model is assessed, and predictions are made on the test dataset.


**Project Overview:**
This project utilizes the Iris flower dataset from sklearn.datasets to train a logistic regression model. The dataset comprises 150 samples with features like Sepal Length, Sepal Width, Petal Length, and Petal Width, categorized into Setosa, Versicolour, and Virginica.

**Project Steps:**

1. **Data Loading and Splitting:**
   - The Iris dataset is loaded, and features (X) and target labels (y) are defined.
   - The dataset is split into training and testing sets (80-20 split).

2. **Logistic Regression Model Training:**
   - A logistic regression model is instantiated and trained on the training set.

3. **Model Accuracy Evaluation:**
   - The accuracy of the model is calculated using the test set.

4. **Prediction on New Samples:**
   - The trained model is used to predict the species of new flower samples.

**Results:**
The logistic regression model achieved 100% accuracy on the test set. The model accurately predicted the species of new flower samples: Setosa, Virginica, and Virginica, respectively.

*Note: Include visuals or further analysis if available.*

This project provides a comprehensive demonstration of training a logistic regression model for iris flower classification and showcases high accuracy in both training and predicting new samples.
