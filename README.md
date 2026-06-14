Iris Dataset Visualization

Problem Statement
The goal of this project is to visualize patterns and relationships in the Iris dataset using different data visualization techniques. Visualizations help identify distributions, trends, and feature relationships before applying machine learning models.

Dataset Details
The Iris dataset is a famous dataset used for classification problems.
Features:
Sepal Length
Sepal Width
Petal Length
Petal Width

Target Variable:
Species
Iris-setosa
Iris-versicolor
Iris-virginica

Dataset Size:
150 records
4 numerical features
3 classes
Approach
1. Data Loading
Import dataset using Pandas.
Check dataset structure and columns.
2. Data Visualization
Bar Chart
Visualizes the number of samples in each species.

Histogram
Shows the distribution of Sepal Length values.

Scatter Plot
Displays the relationship between Sepal Length and Petal Length.

Feature Comparison
Compares multiple features visually within a dashboard.

3. Dashboard Creation
Combine all visualizations into a single dashboard using Matplotlib and Seaborn.

Results
Bar Chart Insights
Each species contains 50 samples.
Dataset is balanced.
Histogram Insights
Sepal Length values mostly range between 5 and 7 cm.
Distribution is approximately normal.
Scatter Plot Insights
Petal Length and Sepal Length show a positive relationship.
Setosa is clearly separated from other species.
Feature Comparison Insights
Petal features provide better separation between species than sepal features.
Petal Length is one of the most informative features.

Conclusion
The Iris dataset shows clear distinctions among species, especially through petal measurements. Visualization helps understand data structure and feature importance before model building.
