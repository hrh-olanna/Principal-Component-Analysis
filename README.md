# Principal-Component-Analysis

**Anderson Cancer Center – PCA & Logistic Regression Project**

**Overview**

The goal is to support donor funding decisions by identifying key variables driving cancer outcomes using Principal Component Analysis (PCA),
followed by predictive modeling with Logistic Regression.

**Dataset**
-	Source: sklearn.datasets
-	Dataset: Breast Cancer Wisconsin (Diagnostic)
-	Samples: 569
-	Features: 30 numerical variables
-	Target:
-	0 = Malignant
-	1 = Benign

**Methodology**
-	Standardized the dataset to remove scale bias
-	Applied PCA to extract essential variables
-	Reduced dimensionality to 2 principal components
-	Trained a Logistic Regression model
-	Evaluated classification performance
-	Identified key contributing features using PCA loadings

**Outputs**
-	Explained variance of PCA components
-	Logistic regression accuracy
-	Precision, recall, and F1-score
-	Top contributing variables for each PCA component

**Business Value**
-	Simplifies high-dimensional medical data
-	Highlights critical variables for donor communication
-	Improves interpretability and model performance
-	Enables data-driven funding justification

**Notes**
-	PCA is used strictly for feature extraction
-	Logistic regression is trained on PCA-transformed data
