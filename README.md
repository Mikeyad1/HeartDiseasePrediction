## Heart Disease Prediction Using Machine Learning

### Project Overview

This project leverages machine learning techniques to predict the presence of heart disease in patients based on a set of medical attributes. By utilizing a variety of features, the model aims to assist healthcare professionals in identifying potential heart disease cases, facilitating early diagnosis and treatment.

### Data Source

The dataset used for this project contains medical information about patients, including the following features:

- **age**: The age of the patient in years.
- **sex**: The sex of the patient (1 = male, 0 = female).
- **cp**: Chest pain type experienced by the patient. Categorized as:
  - 0: Typical angina (chest pain related to decreased blood supply to the heart).
  - 1: Atypical angina (chest pain not typically related to heart disease).
  - 2: Non-anginal pain (chest pain not related to heart disease).
  - 3: Asymptomatic (no chest pain).
- **trestbps**: Resting blood pressure (in mm Hg) of the patient upon admission to the hospital.
- **chol**: Serum cholesterol level (in mg/dL) of the patient.
- **fbs**: Fasting blood sugar level (> 120 mg/dL indicates higher risk for diabetes; 1 = true, 0 = false).
- **restecg**: Resting electrocardiographic results, categorized as:
  - 0: Normal
  - 1: ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
  - 2: Left ventricular hypertrophy by Estes' criteria.
- **thalach**: Maximum heart rate achieved by the patient during exercise.
- **exang**: Exercise induced angina (1 = yes, 0 = no).
- **oldpeak**: ST depression induced by exercise relative to rest.
- **slope**: The slope of the peak exercise ST segment, categorized as:
  - 0: Upsloping
  - 1: Flat
  - 2: Downsloping
- **ca**: Number of major vessels (0-3) colored by fluoroscopy.
- **thal**: Thalassemia (a blood disorder):
  - 1: Normal
  - 2: Fixed defect (no blood flow in some part of the heart)
  - 3: Reversible defect (a blood flow is observed in some part of the heart)
- **target**: The presence of heart disease in the patient (1 = presence, 0 = absence).

### Project Steps

1. **Data Preprocessing**: Cleaning and preparing the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Visualizing and understanding the data distribution and relationships between features.
3. **Model Selection**: Choosing and implementing various machine learning algorithms (e.g., Logistic Regression, Random Forest, SVM) to build predictive models.
4. **Model Evaluation**: Assessing the performance of the models using metrics such as accuracy, precision, recall, and the confusion matrix.
5. **Feature Importance Analysis**: Identifying the most influential features in predicting heart disease.
6. **Visualization**: Creating informative visualizations to communicate insights and model performance.

### Key Features

- **Data Retrieval**: Importing and preprocessing the heart disease dataset.
- **Exploratory Data Analysis**: Visualizing data distributions and feature relationships using pair plots and heatmaps.
- **Model Training and Evaluation**: Training multiple machine learning models and evaluating their performance.
- **Feature Importance Analysis**: Analyzing the importance of different features in the prediction models.
- **Visualization**: Generating various plots (e.g., confusion matrix, ROC curve) to present insights and model performance.

### Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Seaborn
- Matplotlib

### Conclusion

This project demonstrates the application of machine learning in the medical field, specifically for predicting heart disease. By accurately identifying patients at risk, this model can aid in early diagnosis and potentially save lives through timely medical intervention.
