# Predictive-and-Clustering-Analysis-of-Kickstarter-Projects

This repository contains a machine learning project that predicts Kickstarter project success using a classification model and groups projects based on shared characteristics through clustering. These projects are part of my academic coursework in Data Analytics and AI for Business at McGill University.

## **Project Overview**


This project focuses on building a classification model to predict the success of crowdfunding campaigns on Kickstarter at launch, and a clustering model to identify key characteristics of different project types. By leveraging only launch-time data, the project provides insights that can guide decision-making and optimize project success rates.

## **Key Insights**
**Prediction Model:**

The Logistic Regression model with Lasso Regularization achieved:

F1 Score: 76.83%

Accuracy: 76.76%

The model balances precision and recall, making it suitable for predicting project success based on launch characteristics.

**Clustering Model:**

K-means clustering (k=3) was applied to segment projects into three distinct groups:

Cluster 1: Highly successful projects

Cluster 0: Moderately successful projects

Cluster 2: Underperforming projects

Each cluster is characterized by unique financial and promotional traits, providing valuable insights into factors contributing to success.

## **Data Preprocessing and Modeling**

**Libraries:**

Pandas, NumPy (Data manipulation)
Scikit-learn (Modeling, Feature Selection)
Matplotlib, Seaborn (Visualization)
PCA for dimensionality reduction in clustering

**Preprocessing steps:**

Missing Value Handling: Imputed or dropped missing values.

Categorical Encoding: Applied one-hot encoding to categorical features.

Feature Engineering: Created new features, such as project duration.

Feature Selection: Applied ANOVA, RFE, L1 Regularization, and Random Forest to select the most relevant predictors.

**Modeling Approach**

Classification:

Multiple models were tested: Logistic Regression, Random Forest, Gradient Boosting, Neural Networks, and KNN.

Logistic Regression with Lasso Regularization was chosen for its interpretability and performance.

Clustering:

K-means clustering (with k=3 clusters) was applied to group projects by similar characteristics.

Principal Component Analysis (PCA) was used to reduce dimensionality and improve clustering performance.

**Impact**

Actionable Insights: The models empower Kickstarter to predict the success of a project at launch with high accuracy, aiding in project evaluation.

Marketing Optimization: Clustering results highlight patterns in successful projects, offering data-driven recommendations to improve marketing and resource allocation strategies.

Resource Allocation: By identifying characteristics of successful projects, Kickstarter can better allocate resources to projects with high potential.

