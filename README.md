# Obesity Level Prediction using Machine Learning

This project develops a predictive model to classify obesity levels based on demographic data and daily living habits. We compare three distinct algorithms—Artificial Neural Networks (ANN), Random Forests, and Support Vector Machines (SVM)—to determine the most effective approach for health risk assessment.

## Project Overview
Obesity is a complex multi-class classification problem. Our pipeline handles the entire workflow from initial data cleaning and Exploratory Data Analysis (EDA) to hyperparameter tuning and model selection.

### Key Results
| Model | Accuracy | Macro-F1 |
| :--- | :--- | :--- |
| **ANN (MLPClassifier)** | **97%** | **0.97** |
| **Random Forest** | 96% | 0.96 |
| **SVM (Linear)** | 93% | 0.93 |

### Technical Highlights
* [cite_start]**Data Preprocessing:** Handled a dataset of 2,111 records, performing duplicate removal, label encoding, and feature scaling.
* [cite_start]**Exploratory Data Analysis:** Analyzed 17 variables including physical activity, caloric consumption, and family history using correlation matrices and distribution plots[cite: 64].
* [cite_start]**Model Optimization:** Employed GridSearchCV for parameter tuning (e.g., hidden layers for ANN, n_estimators for Random Forest)[cite: 64].
* [cite_start]**Evaluation:** Utilized a hybrid validation strategy with stratified 80/10/10 splits to ensure robust generalization across all obesity categories.

## Dataset Features
[cite_start]The model uses features such as Age, Height, Weight, Frequency of high-caloric food consumption (HCF), Physical activity (PhysAct), and Transportation methods (TransMeans).

## Conclusion
[cite_start]The **Tuned ANN** delivered the best generalization (~97% accuracy), proving that demographic and behavioral features are strong predictors of obesity levels when modeled with deep learning techniques[cite: 64].
