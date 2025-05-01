
# ElevateLabs_Task 5

## **Taks 5**:  Decision Trees and Random Forests

This task focuses on applying tree-based classification models, specifically Decision Trees and Random Forests, using the Heart Disease dataset. 
A Decision Tree is a machine learning algorithm used for classification and regression tasks. The tree is built by splitting the dataset into smaller subsets based on the feature that offers the highest information gain or lowest Gini impurity, helping the model decide which splits make the best predictions. Whereas a Random Forest is an ensemble method that builds many decision trees and combines their predictions to improve accuracy and reduce overfitting.

## **Dataset**

heart.csv

## **Tools**

- Python<br>
- Numpy<br>
- Pandas<br>
- Numpy<br>
- Seaborn<br>
- Scikit-learn<br>
- Jupyter Notebook<br>

# **Tasks Performed in the dataset**

## 1. Train a Decision Tree Classifier and visualize the tree.

The first step includes preprocessing the dataset to separate the features (X) from the target variable (y), which indicates whether or not a person has heart disease. After splitting the dataset into training and testing sets, we train a Decision Tree Classifier using Scikit-learn.

## 2. Analyze overfitting and control tree depth.

Decision trees are prone to overfitting, especially when they are allowed to grow to their full depth without constraints.To address this, we retrain the decision tree but limit its max_depth to a smaller value.  

## 3. Train a Random Forest and compare accuracy.

To improve accuracy and robustness, in the next step we train a Random Forest Classifier, which is a method that builds multiple decision trees and aggregates their predictions. By comparing its accuracy with the single decision tree model, it is observed that the random forest typically performs better.

## 4. Feature importance
Once the random forest model is trained,we analyze importance of each feature, which tells how much each feature contributes to the final prediction. Random Forest provides this information by measuring how each feature improves the splitting criterion across all trees.

## 5.Cross-validation

In the final task, a cross-validation is used to assess our model's stability and performance across different data splits. The average score is computed across all folds to summarize overall model effectiveness.
