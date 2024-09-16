# Parkinson's Disease Prediction ML Model

This project implements a machine learning model to predict Parkinson's Disease based on biomedical voice measurements. Parkinson's Disease is a progressive neurodegenerative disorder that primarily affects movement. It is characterized by tremors, stiffness, and difficulty with balance and coordination. Early detection is crucial to improve the quality of life of patients.

## About Parkinson's Disease:

Parkinson's Disease is a chronic and progressive movement disorder that affects the central nervous system, particularly the motor system. It is caused by the loss of dopamine-producing brain cells. Symptoms often begin gradually, with tremors being the most common sign. Over time, patients may experience stiffness, slowness of movement, and impaired posture. While there is no cure, early detection and treatment can help manage symptoms and slow disease progression.

The model is trained to classify whether a person has Parkinson's Disease based on various vocal attributes using supervised machine learning techniques.

## Key Features:

### Data Preprocessing:
- The dataset is cleaned by handling missing or irrelevant values.
- Features are normalized using `StandardScaler` to ensure uniformity in the input data.

### Model Training:
- Multiple machine learning models were evaluated, including Support Vector Machine (SVM), Random Forest, and Logistic Regression.
- The final model selected is based on performance metrics like accuracy, precision, and recall.

### Evaluation:
- The model’s performance is evaluated using test data, with metrics such as accuracy, precision, recall, and F1 score.
- Cross-validation is used to ensure the model generalizes well to unseen data.

### User Input:
- The model allows user input, enabling predictions based on biomedical features such as jitter, shimmer, HNR, and more.

## Tools & Libraries:

- **Python:** (NumPy, Pandas)
- **Scikit-learn:** (SVM, RandomForest, LogisticRegression, StandardScaler)
- **Jupyter Notebook:** For development, experimentation, and visualization.
