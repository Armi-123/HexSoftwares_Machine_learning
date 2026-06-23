# Heart Disease Detection using Machine Learning

## Overview

Heart Disease Detection is a Machine Learning project designed to predict the likelihood of heart disease based on patient medical records and health-related parameters.

Cardiovascular diseases are among the leading causes of death worldwide. Early detection and diagnosis can significantly improve treatment outcomes and reduce health risks. This project leverages Machine Learning techniques to analyze medical data and assist healthcare professionals in identifying patients at risk of heart disease.

---

## Objective

The primary objective of this project is to build a predictive model that can determine whether a patient is likely to have heart disease based on various medical indicators.

The system aims to support healthcare decision-making by providing accurate and data-driven predictions.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Machine Learning Algorithm

### Random Forest Classifier

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

Advantages:

* High Accuracy
* Handles Large Datasets Efficiently
* Robust Against Noise
* Good Feature Importance Analysis

---

## Dataset

**File:** `heart.csv`

### Dataset Information

* Total Records: 1000+ Patients
* Medical Features: 13+
* Target Variable: Heart Disease Presence

### Dataset Columns

| Feature  | Description                       |
| -------- | --------------------------------- |
| age      | Age of Patient                    |
| sex      | Gender                            |
| cp       | Chest Pain Type                   |
| trestbps | Resting Blood Pressure            |
| chol     | Serum Cholesterol                 |
| fbs      | Fasting Blood Sugar               |
| restecg  | Resting ECG Results               |
| thalach  | Maximum Heart Rate Achieved       |
| exang    | Exercise Induced Angina           |
| oldpeak  | ST Depression                     |
| slope    | Slope of Peak Exercise ST Segment |
| ca       | Number of Major Vessels           |
| thal     | Thalassemia                       |
| target   | Heart Disease (0 = No, 1 = Yes)   |

---

## Project Workflow

1. Load patient medical dataset.
2. Perform data cleaning and preprocessing.
3. Analyze patient health parameters.
4. Visualize feature distributions.
5. Split data into training and testing sets.
6. Train Random Forest Classifier.
7. Evaluate model performance.
8. Predict heart disease risk for new patients.

---

## Features

* Medical Data Analysis
* Heart Disease Prediction
* Data Visualization
* Confusion Matrix Visualization
* Classification Report
* Patient Risk Assessment
* Model Performance Evaluation

---

## Data Visualization

The project includes various visualizations such as:

* Disease Distribution Charts
* Correlation Heatmaps
* Feature Analysis Graphs
* Confusion Matrix Visualization

These visualizations help understand relationships between medical factors and heart disease risk.

---

## Output

The model predicts whether a patient is likely to have heart disease.

### Example

#### Input Patient Data

```text
Age: 52
Sex: Male
Blood Pressure: 125
Cholesterol: 212
Maximum Heart Rate: 168
```

#### Prediction

```text
Heart Disease Detected
```

or

```text
No Heart Disease Detected
```

---

## Applications

* Healthcare Analytics
* Medical Decision Support Systems
* Early Disease Detection
* Hospital Management Systems
* Clinical Research
* Preventive Healthcare

---

## Project Structure

```text
Task2_Project2_Heart_Disease_Detection/
│
├── Task2_Project2_Heart_Disease_Detection.ipynb
├── heart.csv
├── requirements.txt
└── README.md
```

---

## Tools and Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Learning Outcomes

Through this project, the following concepts were implemented:

* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Classification Models
* Feature Engineering
* Random Forest Algorithm
* Model Training
* Model Evaluation
* Healthcare Data Analytics

---

## Future Enhancements

* Deep Learning-Based Disease Prediction
* Real-Time Patient Monitoring
* Web-Based Healthcare Dashboard
* Integration with Electronic Health Records (EHR)
* Multi-Disease Prediction System

---

## Conclusion

The Heart Disease Detection System successfully demonstrates the application of Machine Learning in healthcare analytics. By utilizing a Random Forest Classifier, the model analyzes patient health parameters and predicts the likelihood of heart disease with high accuracy.

This project highlights how Machine Learning can assist medical professionals in early diagnosis, improve healthcare decision-making, and contribute to better patient outcomes.

---

## Author

**Armi Sherathiya**

HexSoftwares Machine Learning Internship

2025
