# Personality Prediction System Through CV Analysis using Machine Learning

## Overview

The Personality Prediction System Through CV Analysis is a Natural Language Processing (NLP) and Machine Learning project designed to predict personality traits from resume and CV content.

The system analyzes textual information present in resumes, including skills, achievements, work experience, education, certifications, and professional summaries. Based on the extracted patterns and language usage, the model predicts personality characteristics that may help recruiters better understand candidates.

This project demonstrates how Machine Learning and NLP can assist in recruitment processes by automating personality assessment and reducing manual evaluation efforts.

---

## Objective

The primary objective of this project is to build a Machine Learning model that predicts personality traits from resume text.

The system aims to:

* Automate candidate personality assessment
* Assist recruiters during screening
* Analyze professional profiles efficiently
* Support data-driven hiring decisions

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* NLTK
* Jupyter Notebook

---

## Natural Language Processing Techniques

### Text Preprocessing

Cleans resume text by removing unnecessary symbols, numbers, and formatting inconsistencies.

### Tokenization

Breaks text into meaningful words and phrases.

### Stopword Removal

Removes common words that contribute little information during analysis.

### TF-IDF Vectorization

Converts resume text into numerical feature vectors suitable for Machine Learning models.

### Feature Extraction

Extracts important textual patterns and keywords from resumes.

---

## Machine Learning Algorithm

### Multinomial Naive Bayes

Multinomial Naive Bayes is a probabilistic classification algorithm commonly used for text classification problems.

Advantages:

* Fast Training
* Efficient for Text Data
* Good Performance on NLP Tasks
* Lightweight and Scalable

---

## Dataset

**File:** `resumes.csv`

### Dataset Information

The dataset contains resume content and corresponding personality labels.

### Dataset Columns

| Column      | Description             |
| ----------- | ----------------------- |
| Resume      | Resume/CV Text          |
| Personality | Personality Trait Label |

---

## Personality Traits Predicted

The model predicts one of the following personality traits:

### Openness

Individuals who are creative, innovative, curious, and willing to explore new ideas.

### Conscientiousness

Individuals who are organized, disciplined, responsible, and goal-oriented.

### Extraversion

Individuals who are energetic, social, confident, and outgoing.

### Agreeableness

Individuals who are cooperative, friendly, empathetic, and supportive.

### Emotional Stability

Individuals who remain calm, balanced, and resilient under pressure.

---

## Project Workflow

1. Load resume dataset.
2. Perform text preprocessing.
3. Clean and normalize resume content.
4. Remove stopwords.
5. Convert text using TF-IDF Vectorization.
6. Split data into training and testing sets.
7. Train Multinomial Naive Bayes classifier.
8. Evaluate model performance.
9. Predict personality traits for new resumes.

---

## Features

* Resume Analysis
* Personality Prediction
* NLP-Based Text Processing
* Automated Candidate Assessment
* Text Classification
* Recruiter Support System
* Data-Driven Personality Evaluation

---

## Input

### Example Resume Text

```text
Experienced Software Engineer with expertise in Python, Machine Learning,
Data Analysis, Team Leadership, and Problem Solving.
Successfully managed multiple projects and collaborated with cross-functional teams.
```

---

## Output

### Predicted Personality Trait

```text
Conscientiousness
```

or

```text
Extraversion
```

depending on the resume content.

---

## Applications

* Recruitment and Hiring
* Human Resource Analytics
* Candidate Screening
* Talent Assessment
* Career Counseling
* Personality Analysis Systems
* Employee Evaluation

---

## Project Structure

```text
Task3_Project2_Personality_Prediction/
│
├── Task3_Project2_Personality_Prediction.ipynb
├── resumes.csv
├── requirements.txt
└── README.md
```

---

## Tools and Libraries

* Pandas
* NumPy
* NLTK
* Scikit-Learn
* Python

---

## Learning Outcomes

Through this project, the following concepts were implemented:

* Natural Language Processing (NLP)
* Text Preprocessing
* Feature Extraction
* TF-IDF Vectorization
* Text Classification
* Machine Learning for Recruitment
* Naive Bayes Classification
* Model Evaluation

---

## Future Enhancements

* Deep Learning-Based Personality Prediction
* Resume Parsing Automation
* BERT-Based Text Classification
* Multi-Trait Personality Scoring
* Web-Based Recruitment Dashboard
* Real-Time Resume Analysis

---

## Real-World Applications

* HR Technology Platforms
* AI Recruitment Systems
* Talent Acquisition Tools
* Candidate Assessment Platforms
* Corporate Hiring Solutions
* Career Guidance Applications

---

## Conclusion

The Personality Prediction System Through CV Analysis successfully demonstrates how Natural Language Processing and Machine Learning can be used to analyze resumes and predict personality traits.

By leveraging TF-IDF Vectorization and Multinomial Naive Bayes Classification, the system automates personality assessment and provides valuable insights that can support recruitment and talent management processes.

This project highlights the growing role of AI and NLP in modern human resource management and candidate evaluation.

---

## Author

**Armi Sherathiya**

HexSoftwares Machine Learning Project