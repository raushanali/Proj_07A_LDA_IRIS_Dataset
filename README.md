# Proj_07A_LDA_IRIS_Dataset

This project demonstrates the use of Linear Discriminant Analysis (LDA) for classifying iris flowers based on their physical characteristics. The classic Iris dataset is used, which contains measurements of three iris species: Setosa, Versicolor, and Virginica.

Purpose
The main goal of this project is to classify iris flowers into their respective species using LDA, a supervised machine learning algorithm. In this example, we focus on distinguishing between the Setosa and Versicolor species.

Features
Data Loading: Utilizes scikit-learn's built-in Iris dataset.

Visualization: Plots the original and predicted class distributions using Matplotlib.

Model Training: Trains an LDA classifier on the selected data.

Evaluation: Measures performance using a confusion matrix and accuracy score.

Result Visualization: Displays both the confusion matrix and classification results.

Usage Instructions
Install Dependencies:

pip install scikit-learn matplotlib
Run the Code:

Copy the provided Python code into your IDE or a Jupyter notebook.

Execute the code to see data visualization, model training, predictions, and evaluation.

Workflow Overview:

Load the Iris dataset.

Select the first 100 samples (Setosa and Versicolor).

Split the data into training and testing sets.

Train the LDA model.

Predict the classes and evaluate the results.

Display the confusion matrix and accuracy score.

Visualize the original and predicted classes.

Example Output

Confusion Matrix:

Accuracy Score:

Plots:

Original data points (Sepal Length vs Sepal Width) colored by actual class.

Predicted data points colored by predicted class.
