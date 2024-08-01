# IRIS FLOWER ANALYSIS

![](https://th.bing.com/th/id/R.4d52a0f78d9f3ac35b0f7dc2c73d1514?rik=QdVRYUyOP838PA&riu=http%3a%2f%2feskipaper.com%2fimages%2firis-flower-1.jpg&ehk=FyQ%2b4R3ZsoduaQl4FUhSqMnh3nhlCYoNO2tDTSicj6o%3d&risl=&pid=ImgRaw&r=0)

> ## Overview

The objective of this project is to classify Iris flowers into three species: Setosa, Versicolor, and Virginica, using four features: sepal length, sepal width, petal length, and petal width. The process starts by importing necessary libraries such as pandas, matplotlib, seaborn, and scikit-learn. The [`IRIS.csv`](https://github.com/Anuraghaldar/IRIS-FLOWER-ANALYSIS/blob/main/IRIS.csv)  dataset  is then loaded, explored, and cleaned. Statistical summaries and visualizations, including histograms, box plots, scatter plots, pair plots, and a heatmap, are used to understand the data. The dataset is split into training and testing sets. A Decision Tree classifier is trained on the training set and used to predict the species of Iris flowers in the test set. Finally, the model's performance is evaluated, achieving an accuracy of approximately `95.56%`.

---

> ## Flow Steps for Analysis

1. **Importing Libraries**: The necessary libraries for data manipulation, visualization, and machine learning are imported. These include `pandas`, `matplotlib`, `seaborn`, and `scikit-learn`.

2. **Data Loading and Exploration**:
- Load the [IRIS.csv](https://github.com/Anuraghaldar/IRIS-FLOWER-ANALYSIS/blob/main/IRIS.csv) dataset.
- Display the first few rows of the dataset to understand its structure.
- Check for null values to ensure data cleanliness.
- Obtain basic statistical summaries of the data.
- Explore the distribution of each feature and visualize it using histograms and box plots.

3. **Data Visualization**:
- Visualize pairwise relationships between features using scatter plots.
- Use a pair plot to visualize the distribution of species in the feature space.
- Generate a heatmap to visualize the correlation between features.

4. **Data Preprocessing**:
- Split the dataset into features `(X)` and target `(Y)`.
- Split the data into training and testing sets with a 70-30 ratio.

5. **Machine Learning Model**:
- Import the `DecisionTreeClassifier` from scikit-learn.
- Train the model using the training set.
- Predict the species of Iris flowers in the test set.

6. **Performance Check**:
- Evaluate the accuracy of the model on the test set.
---

<!-- ANURAG HALDAR -->
