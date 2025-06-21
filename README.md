![Screenshot 2025-06-21 210053](https://github.com/user-attachments/assets/0142a585-57a9-4dbc-a6b8-aa94a5ecd13f)# Project-3---Personal-Loan-Default-Prediction
This repository presents a supervised machine learning pipeline to predict personal loan subscription using customer demographic and financial data. Leveraging a publicly available banking dataset, the workflow comprises:

Exploratory Data Analysis (EDA):
Data ingestion, cleansing (duplicate removal, missing‑value checks) and feature inspection via summary statistics, histograms, boxplots, and correlation heatmaps.

Model Development:
Three classifiers are trained on a 75/25 train–test split:

K-Nearest Neighbors (KNN)

CatBoost Classifier

LightGBM Classifier

Evaluation:
Each model is assessed using Accuracy and F1 score, with results compared side‑by‑side. Confusion matrices visualize class‑specific performance, highlighting trade‑offs between precision and recall.

Key Findings:
The CatBoost Classifier achieved the highest overall accuracy and F1 score, demonstrating superior balance between sensitivity and specificity in predicting loan uptake.

This notebook offers a clear, reproducible template for binary classification tasks on structured tabular data, illustrating best practices in EDA, model training, hyperparameter tuning, and performance visualization using Python libraries (Pandas, Scikit‑learn, CatBoost, LightGBM, Matplotlib, Seaborn).

F1 Score comparison
![Screenshot 2025-06-21 210053](https://github.com/user-attachments/assets/d0133ad5-a42a-41b7-b674-d8624ccd3e50)
Accuracy Score comparison
![Screenshot 2025-06-21 210046](https://github.com/user-attachments/assets/233eed78-26a3-434c-aa01-f88e2f7d1aac)
