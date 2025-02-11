# Breast Cancer Classification

## Overview
This project implements machine learning models to classify breast cancer cases using the **Breast Cancer Wisconsin (Diagnostic) Dataset**. The dataset consists of **30 numerical features** derived from digitized images of fine needle aspirate (FNA) biopsies.

## Branches
- **main branch (V1)**: Implements **Logistic Regression** for classification.
- **v2_branch (V2)**: Implements **Random Forest Classifier** for improved accuracy and robustness.

## Dataset
- The dataset is obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29).
- Each sample is labeled as **Benign (0)** or **Malignant (1)**.

## Preprocessing Steps
1. Remove the **ID column** (not useful for classification).
2. Convert the **Diagnosis column** from categorical (`B/M`) to numerical (`0/1`).
3. Standardize the dataset using **StandardScaler** to improve model performance.
4. Split the dataset into **80% training** and **20% testing**.

## Models
### **V1: Logistic Regression**
- A simple linear model used as the baseline for classification.
- Evaluated using **accuracy, confusion matrix, and classification report**.

### **V2: Random Forest Classifier**
- An ensemble model with 100 decision trees.
- Provides improved performance over logistic regression.
- Evaluated using **accuracy, confusion matrix, and classification report**.

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Running the Models
To execute the models, run the corresponding Python scripts:
```bash
python Zeyu_Li_model_v1.ipynb  # Logistic Regression Model
python Zeyu_Li_model_v2.ipynb  # Random Forest Model
```

## Results
- Both models perform well, with **Random Forest achieving higher accuracy**.
- The confusion matrix visualization helps understand the classification performance.

## Repository Link
This project is publicly available on GitHub: [Exercise2 Repository](https://github.com/Arsney091289421/Exercise2.git)
