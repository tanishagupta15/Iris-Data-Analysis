# Iris dataset analysis - Classification
# Dataset Information

The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant. One class is linearly separable from the other 2; the latter are NOT linearly separable from each other.
**Download link:** https://www.kaggle.com/uciml/iris


# Step 1: Import Modules
Import libraries for data manipulation (pandas, numpy), visualization (matplotlib, seaborn), and machine learning (scikit-learn).

# Step 2: Load Dataset and Derive Insights
<li>Load the Iris dataset.
<li>Display the first few rows to understand the structure.
<li>Get dataset info (data types, null values).
<li>Generate statistical summary (mean, median, standard deviation).

# Step 3: Preprocess the Dataset (Removing Null Values)
Check for and remove any null values to ensure a clean dataset.

# Step 4: Exploratory Data Analysis (Histogram and Scatter Plot)
<li>Create histograms for feature distribution.
<li>Generate pair plots to visualize relationships between features, categorized by species.

# Step 5: Correlation Matrix (Heat Map)
Compute and visualize the correlation matrix using a heat map to identify relationships between features.

# Step 6: Label Encoder
Convert categorical species labels into numeric form using a label encoder for machine learning compatibility.

# Step 7: Model Training
<li>Split data into features and target, then into training and testing sets.
<li>Train models (Logistic Regression, K-Nearest Neighbors, Decision Tree).
<li>Predict species on test data and evaluate model accuracy.
<li>Compare accuracies to determine the best-performing model.

# Libraries
<li>pandas
<li>matplotlib
<li>seaborn
<li>scikit-learn

# Algorithms
<li>Logistic Regression
<li>K-Nearest Neighbors
<li>Decision Tree
  
**Best Model Accuracy:** 100.00
