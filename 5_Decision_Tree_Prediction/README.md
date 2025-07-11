# Prediction using Decision Tree Algorithm

This project was completed as part of my Data Science Internship at LetsGrowMore (October 2023 batch). The objective was to build a classification model using the Decision Tree algorithm to predict the species of iris flowers based on their morphological measurements.

## Objective

To implement a supervised learning model using the Decision Tree algorithm on the Iris dataset. The project focuses on training the model to classify iris flowers into three species using features such as sepal and petal dimensions.

## Tools and Libraries Used

- Python  
- pandas  
- numpy  
- seaborn  
- matplotlib  
- scikit-learn (DecisionTreeClassifier, train_test_split, accuracy_score, confusion_matrix)

## Summary of Work

- Loaded the Iris dataset and examined its structure, shape, and summary statistics.
- Performed data cleaning checks to ensure the dataset had no missing values.
- Defined features (`X`) and labels (`Y`) based on sepal and petal dimensions.
- Split the dataset into training and testing subsets (70:30 ratio).
- Trained a Decision Tree Classifier using the entropy criterion.
- Made predictions on the test data and calculated the model's accuracy.
- Evaluated model performance using a confusion matrix.
- Visualized the trained decision tree using `sklearn.tree.plot_tree`.

## Key Outcomes

- Achieved accurate classification of iris flower species using a decision tree model.
- Gained practical experience in supervised learning, model evaluation, and visualization.
- Developed understanding of how decision trees split data based on feature importance.

## Files Included

- `Prediction_using_Decision_Tree_Algorithm.ipynb` – Google Colab notebook containing full implementation.
- `README.md` – Project summary and documentation.

## Dataset

The dataset used is the classic **Iris Flower Dataset**, which is publicly available and commonly used for classification tasks in machine learning.  
Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)  
(Note: Dataset is not included in this repository.)

## Acknowledgement

This project was developed during my internship at LetsGrowMore under the guidance of Mr. Aman Kesarwani.
