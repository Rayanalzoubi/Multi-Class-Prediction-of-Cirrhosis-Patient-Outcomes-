# Cirrhosis Outcomes Prediction using XGBoost

This project was developed as part of the TjDeeD AI Training Program.

## Project Goal
Build a multiclass classification model to predict liver cirrhosis patient outcomes:
- C (Censored)
- CL (Censored due to liver transplant)
- D (Deceased)

## Machine Learning Workflow
The project includes:
- Data exploration (EDA)
- Missing value handling
- Feature preprocessing
- OneHotEncoding
- RobustScaler
- SMOTE for class imbalance
- Hyperparameter tuning
- XGBoost classification

## Evaluation Metrics
The model was evaluated using:
- Accuracy
- ROC-AUC
- Log Loss
- Classification Report
- Confusion Matrix

## Final Output
The final model generates probability predictions for:
- Status_C
- Status_CL
- Status_D

and creates a valid `submission.csv` file.

## Files Included
- `XGBoostnewMulti_ClassPredictiono.ipynb`
- `submission.csv`

## Technologies Used
- Python
- Pandas
- Scikit-learn
- XGBoost
- Imbalanced-learn
- Matplotlib
- Seaborn
