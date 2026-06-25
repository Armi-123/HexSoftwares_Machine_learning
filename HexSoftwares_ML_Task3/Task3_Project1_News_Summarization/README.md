# News Article Summarization using Natural Language Processing (NLP)

## Overview

News Article Summarization is a Natural Language Processing (NLP) project that automatically generates concise summaries from lengthy news articles. The system extracts the most important information from news content and presents it in a shorter, easy-to-read format while preserving the original meaning.

With the increasing volume of digital news content generated every day, automatic text summarization helps readers quickly understand key information without reading entire articles.

This project utilizes NLP techniques such as text preprocessing, stopword removal, word frequency analysis, and sentence ranking to create meaningful summaries.

---

## Objective

The primary objective of this project is to develop an automated text summarization system capable of converting long news articles into concise summaries.

The system aims to:

* Reduce reading time
* Highlight key information
* Improve information accessibility
* Assist in content analysis and management

---

## Technologies Used

* Python
* Pandas
* NumPy
* NLTK (Natural Language Toolkit)
* Scikit-Learn
* Jupyter Notebook

---

## Natural Language Processing Techniques

### Text Preprocessing

Prepares textual data for analysis by removing unwanted characters and formatting inconsistencies.

### Tokenization

Breaks text into individual words and sentences.

### Stopword Removal

Removes common words such as:

```text
the, is, are, was, were, and, of, in
```

which contribute little meaning to summarization.

### Word Frequency Analysis

Calculates the importance of words based on their occurrence within the article.

### Sentence Ranking

Assigns scores to sentences based on important keywords and word frequencies.

### Extractive Summarization

Selects the most important sentences from the original article to generate the final summary.

---

## Dataset

**File:** `Articles.csv`

### Dataset Information

* Total Records: 2,600+ News Articles
* Categories: Business, Sports, Politics, Technology, Entertainment, etc.

### Dataset Columns

| Column   | Description           |
| -------- | --------------------- |
| Article  | Complete News Article |
| Date     | Publication Date      |
| Heading  | News Headline         |
| NewsType | News Category         |

---

## Sample Dataset

| Heading                                          | News Type |
| ------------------------------------------------ | --------- |
| Sindh Govt Decides to Cut Public Transport Fares | Business  |
| Asia Stocks Rise in New Year Trading             | Business  |
| Hong Kong Stocks Open Lower                      | Business  |

---

## Project Workflow

1. Load news dataset.
2. Select article text.
3. Clean and preprocess text.
4. Perform tokenization.
5. Remove stopwords.
6. Calculate word frequencies.
7. Rank sentences based on importance.
8. Extract top-ranked sentences.
9. Generate final summary.

---

## Features

* Automatic News Summarization
* Text Cleaning and Processing
* Stopword Removal
* Word Frequency Analysis
* Sentence Ranking
* Extractive Summarization
* Fast Summary Generation
* NLP-Based Text Analytics

---

## Input

### Original News Article

```text
Long news article containing hundreds of words and multiple paragraphs.
```

---

## Output

### Generated Summary

```text
The Sindh government announced a 7% reduction in public transport fares following lower petroleum prices. Transport operators stated that fare reductions would depend on future decreases in CNG prices.
```

---

## Applications

* News Aggregation Platforms
* Digital Journalism
* Content Management Systems
* Information Retrieval
* Research and Analysis
* News Monitoring Systems
* Media Analytics

---

## Project Structure

```text
Task3_Project1_News_Article_Summarization/
│
├── Task3_Project1_News_Article_Summarization.ipynb
├── Articles.csv
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

Through this project, the following NLP concepts were implemented:

* Text Preprocessing
* Tokenization
* Stopword Removal
* Frequency Analysis
* Sentence Scoring
* Extractive Summarization
* Natural Language Processing
* Text Analytics

---

## Future Enhancements

* Abstractive Summarization using Transformers
* Hugging Face Integration
* BERT-Based Summarization
* Multi-Language News Summarization
* Real-Time News Summaries
* Web Application Deployment

---

## Real-World Applications

* Google News Summaries
* News Recommendation Systems
* AI Content Assistants
* Research Article Summarization
* Corporate News Monitoring
* Business Intelligence Systems

---

## Conclusion

The News Article Summarization System successfully demonstrates the application of Natural Language Processing techniques for automatic text summarization.

By utilizing text preprocessing, word frequency analysis, and sentence ranking, the model generates concise summaries that retain the most important information from lengthy news articles. This project highlights the practical use of NLP in information extraction, content management, and digital media applications.

---

## Author

**Armi Sherathiya**

HexSoftwares Machine Learning Internship

2025
