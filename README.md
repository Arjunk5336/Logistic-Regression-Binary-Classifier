# Breast Cancer Diagnosis Using Logistic Regression

This project demonstrates the application of logistic regression to predict breast cancer diagnoses using a real-world dataset. The model is trained to classify tumors as malignant or benign based on various features computed from digitized images of fine needle aspirate (FNA) of breast masses.


Dataset:

The dataset used in this project is derived from the Breast Cancer Wisconsin (Diagnostic) Data Set.

diagnosis: Target variable (Malignant = 1, Benign = 0)

Other columns: Various tumor measurements (e.g., radius, texture, smoothness)



Technologies & Libraries:

Python

Pandas & NumPy

Scikit-learn

Matplotlib

SciPy



Workflow:

1. Data Loading & Preprocessing

Drops irrelevant columns (id, Unnamed: 32)

Label-encodes the target column (diagnosis)

Splits the dataset into training and testing sets

Standardizes features using StandardScaler



2. Model Training

Trains a logistic regression classifier

Predicts labels and probabilities on test data



3. Evaluation

Confusion matrix

Classification report (precision, recall, F1-score)

ROC-AUC score and ROC curve plotting



4. Threshold Tuning

Evaluates the effect of different decision thresholds (0.3, 0.5, 0.7)

Prints updated confusion matrices, precision, and recall



5. Sigmoid Function Visualization

Plots the sigmoid function used in logistic regression
