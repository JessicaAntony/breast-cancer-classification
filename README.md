# Breast Cancer Classification

## Description
This project uses the Breast Cancer Wisconsin dataset to classify tumors as malignant or benign.  
It includes exploratory data analysis (EDA), preprocessing, logistic regression modeling, and model evaluation.

## Dataset
- Source: data.csv  
- Rows: 569  
- Columns: 31 (1 target + 30 features)  
- Target: diagnosis (M = Malignant, B = Benign)  

## Steps Done
Loaded and explored the dataset.  
Dropped unnecessary columns (id, Unnamed: 32).  
Encoded the target variable (M → 1, B → 0).  
Checked for missing values and confirmed all features are numeric.  
Split the dataset into training and testing sets (80% / 20%).  
Standardized features using StandardScaler.  
Trained a Logistic Regression model.  
Evaluated the model using accuracy, precision, recall, F1 score, confusion matrix, and ROC-AUC score.  
Plotted class distribution, correlation heatmap, pairplot for top features, feature importance, and ROC curve.  
Tuned the classification threshold to improve recall.  
Added explanation of the sigmoid function.

## Tools Used
Python  
Pandas, NumPy  
Matplotlib, Seaborn  
Scikit-learn  

## Results
Accuracy (threshold 0.5): 96.49%  
Precision: 97.50%  
Recall: 92.86%  
Accuracy (threshold 0.4): ~96%  
Precision: 97.56%  
Recall: 95.24%  
