# HexSoftwares Machine Learning Projects – Task 3

## Overview

This repository contains the implementation of **Task 3** completed during the **HexSoftwares Machine Learning **.

Task 3 focuses on solving real-world problems using **Machine Learning (ML)** and **Natural Language Processing (NLP)**. The projects demonstrate practical applications of text summarization, personality prediction from resumes, and healthcare analytics for disease detection.

Each project follows a complete Machine Learning workflow, including:

- Data Collection
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building
- Model Evaluation
- Prediction
- Result Visualization

---

# Projects Included

## Project 1: News Article Summarization with Machine Learning

### Description

News Article Summarization is a Natural Language Processing (NLP) application that automatically generates concise summaries from lengthy news articles.

The system identifies the most important sentences from the original article and creates a meaningful summary while preserving the core information.

This project helps reduce reading time and improves accessibility to large volumes of textual information.

---

### Objective

- Automatically summarize long news articles.
- Reduce reading time.
- Extract important information.
- Improve information accessibility.
- Demonstrate NLP-based text summarization.

---

### Technologies Used

- Python
- Pandas
- NLTK
- NumPy
- Scikit-Learn
- Jupyter Notebook

---

### NLP Techniques

- Text Cleaning
- Tokenization
- Stop Word Removal
- Word Frequency Calculation
- Sentence Scoring
- Extractive Text Summarization

---

### Features

- Automatic News Summarization
- Text Preprocessing
- Keyword Extraction
- Important Sentence Selection
- Frequency-Based Ranking
- Quick Summary Generation

---

### Dataset

**Articles.csv**

Dataset contains approximately **2,600 news articles**.

Dataset Columns:

- Article
- Date
- Heading
- NewsType

---

### Workflow

1. Load Dataset
2. Clean News Articles
3. Remove Stop Words
4. Calculate Word Frequencies
5. Score Sentences
6. Generate Summary
7. Display Original Article and Summary

---

### Output

- Original News Article
- Automatically Generated Summary

---

### Real-World Applications

- News Websites
- Digital Newspapers
- Research Articles
- Educational Platforms
- AI Content Summarization

---

# Project 2: Personality Prediction System Through CV Analysis

### Description

This project predicts a candidate's personality based on resume or CV content using Machine Learning and Natural Language Processing techniques.

The model analyzes skills, work experience, education, certifications, and writing style to estimate personality traits that may help recruiters during candidate evaluation.

---

### Objective

- Analyze resume text.
- Predict personality traits.
- Automate candidate assessment.
- Support recruitment decisions.
- Reduce manual screening effort.

---

### Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-Learn
- Jupyter Notebook

---

### Machine Learning Techniques

- TF-IDF Vectorization
- Text Preprocessing
- Tokenization
- Stop Word Removal
- Multinomial Naive Bayes Classification

---

### Features

- Resume Analysis
- CV Text Processing
- Personality Prediction
- Automated Candidate Assessment
- NLP-Based Classification
- HR Analytics

---

### Dataset

**resumes.csv**

Dataset contains resume text and corresponding personality labels.

Dataset Columns:

- Resume
- Personality

---

### Personality Traits

The system predicts personality based on the following categories:

- Openness
- Conscientiousness
- Extraversion
- Agreeableness
- Emotional Stability

---

### Workflow

1. Load Resume Dataset
2. Clean Resume Text
3. Convert Text into Numerical Features using TF-IDF
4. Train Machine Learning Model
5. Predict Personality
6. Evaluate Model Performance

---

### Output

The model predicts the most suitable personality trait from the provided resume.

---

### Real-World Applications

- HR Recruitment Systems
- Resume Screening
- Employee Assessment
- Talent Acquisition
- Career Guidance Systems

---

# Project 3: Malaria Detection using Machine Learning

### Description

Malaria Detection is a healthcare Machine Learning project that predicts whether a blood sample is infected with malaria parasites using numerical features extracted from microscopic blood images.

The model learns the differences between infected and healthy blood samples and performs automated disease classification.

---

### Objective

- Detect malaria infection.
- Assist healthcare professionals.
- Improve diagnosis speed.
- Support early treatment.
- Demonstrate Machine Learning in healthcare.

---

### Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

### Machine Learning Algorithm

- Random Forest Classifier

---

### Features

- Medical Data Analysis
- Disease Classification
- Feature Analysis
- Confusion Matrix
- Classification Report
- Accuracy Evaluation
- Disease Prediction

---

### Dataset

**malaria.csv**

Dataset Size:

- 27,000+ Samples

Target Classes:

- Parasitized
- Uninfected

Example Dataset Columns:

- Label
- area_0
- area_1
- area_2
- area_3
- area_4

---

### Workflow

1. Load Dataset
2. Data Cleaning
3. Label Encoding
4. Train-Test Split
5. Model Training
6. Prediction
7. Performance Evaluation
8. Disease Prediction

---

### Output

The model predicts whether the blood sample is:

- Parasitized
- Uninfected

---

### Real-World Applications

- Healthcare Analytics
- Disease Detection
- Medical Decision Support
- Rural Healthcare Systems
- AI-Based Medical Diagnosis

---

# Repository Structure

```text
HexSoftwares_ML_Task3/
│
├── Task3_Project1_News_Article_Summarization/
│   ├── Task3_Project1_News_Article_Summarization.ipynb
│   ├── Articles.csv
│   ├── requirements.txt
│   └── README.md
│
├── Task3_Project2_Personality_Prediction_System/
│   ├── Task3_Project2_Personality_Prediction_System.ipynb
│   ├── resumes.csv
│   ├── requirements.txt
│   └── README.md
│
├── Task3_Project3_Malaria_Detection/
│   ├── Task3_Project3_Malaria_Detection.ipynb
│   ├── malaria.csv
│   ├── requirements.txt
│   └── README.md
│
└── README.md
```

---

# Machine Learning Skills Demonstrated

- Machine Learning
- Natural Language Processing (NLP)
- Text Classification
- Text Summarization
- Feature Engineering
- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Classification Models
- Healthcare Analytics
- Predictive Analytics
- Model Training
- Model Evaluation
- Confusion Matrix
- Data Visualization

---

# Python Libraries Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Learning Outcomes

By completing Task 3, the following Machine Learning concepts were implemented:

- Natural Language Processing
- Text Cleaning
- Tokenization
- Stop Word Removal
- TF-IDF Vectorization
- Text Classification
- Frequency-Based Text Summarization
- Healthcare Data Analysis
- Classification Algorithms
- Model Evaluation
- Prediction Systems
- Data Visualization

---

# Real-World Domains Covered

- News & Media
- Human Resources
- Recruitment Analytics
- Healthcare
- Medical Diagnosis
- Artificial Intelligence
- Natural Language Processing

---

# Conclusion

Task 3 demonstrates the practical implementation of Machine Learning and Natural Language Processing to solve real-world challenges across multiple domains.

### Projects Completed

- News Article Summarization using NLP
- Personality Prediction System Through CV Analysis
- Malaria Detection using Machine Learning

These projects highlight how Machine Learning can automate text understanding, improve recruitment processes, and support healthcare professionals in disease diagnosis.

The repository showcases end-to-end Machine Learning development, from preprocessing and feature engineering to model training, evaluation, and prediction.

---

# Future Improvements

- Integrate Deep Learning models for improved prediction accuracy.
- Deploy projects as web applications using Flask or Streamlit.
- Use larger datasets for better generalization.
- Add model persistence using Joblib or Pickle.
- Build interactive user interfaces for real-time predictions.

---

## Author

**Armi Sherathiya**

**B.Tech Computer Engineering**

**HexSoftwares Machine Learning Projects**

---

⭐ **If you found this repository useful, consider giving it a Star on GitHub!**