# HexSoftwares Machine Learning Internship - Task 1

## Overview

This repository contains the implementation of three Machine Learning projects completed as part of the HexSoftwares Machine Learning Internship.

The projects demonstrate applications of Machine Learning, Natural Language Processing (NLP), Recommendation Systems, and Deep Learning.

---

# Project 1: Sentiment Analysis

## Objective

Sentiment Analysis is a Natural Language Processing (NLP) technique used to determine the emotional tone behind text.

The goal of this project is to classify customer reviews into:

* Positive
* Negative
* Neutral

## Technologies Used

* Python
* Pandas
* Scikit-Learn
* NLP

## Algorithm Used

* CountVectorizer
* Multinomial Naive Bayes

## Features

* Text Classification
* Sentiment Prediction
* Customer Review Analysis

## Dataset

A custom dataset containing customer reviews and sentiment labels.

## Output

The model predicts whether a review expresses a Positive, Negative, or Neutral sentiment.

---

# Project 2: Music Recommendation System

## Objective

A Music Recommendation System suggests songs to users based on similarities in music data and user preferences.

The system recommends songs with similar characteristics and genres.

## Technologies Used

* Python
* Pandas
* Scikit-Learn

## Algorithm Used

* CountVectorizer
* Cosine Similarity

## Features

* Song Recommendation
* Genre-Based Filtering
* Similar Music Suggestions

## Dataset

A custom dataset containing song names, artists, and genres.

## Output

The system recommends songs that are similar to the selected song.

---

# Project 3: Image Classification

## Objective

Image Classification involves assigning labels to images based on their visual content.

This project uses a Convolutional Neural Network (CNN) to classify images into predefined categories.

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib

## Deep Learning Model

* Convolutional Neural Network (CNN)

## Dataset

CIFAR-10 Dataset

### Classes

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

## Model Performance

* Test Accuracy: Approximately 69%

## Note

The CIFAR-10 dataset contains low-resolution images of size 32×32 pixels. Therefore, images may appear blurry when displayed. This is a characteristic of the dataset and not an issue with the implementation.

Despite the low image resolution, the CNN model successfully learns visual patterns and performs image classification effectively.

## Future Improvements

* Increase training epochs
* Apply Data Augmentation
* Add additional CNN layers
* Use Transfer Learning
* Train on higher-resolution datasets

---

# Project Structure

Task1

├── Project1_Sentiment_Analysis

│ ├── Task1_Project1_Sentiment_Analysis.ipynb

│ ├── reviews.csv

│ └── README.md

│

├── Project2_Music_Recommendation_System

│ ├── Task1_Project2_Music_Recommendation_System.ipynb

│ ├── songs.csv

│ └── README.md

│

├── Project3_Image_Classification

│ ├── Task1_Project3_Image_Classification.ipynb

│ ├── model.h5

│ └── README.md

│

└── Main README.md

---

# Skills Demonstrated

* Machine Learning
* Deep Learning
* Natural Language Processing (NLP)
* Recommendation Systems
* Data Preprocessing
* Feature Engineering
* Classification Models
* TensorFlow & Keras
* Model Evaluation

---

# Conclusion

This task successfully demonstrates the implementation of Machine Learning and Deep Learning techniques across multiple domains:

1. Sentiment Analysis using NLP.
2. Music Recommendation using Content-Based Filtering.
3. Image Classification using Convolutional Neural Networks.

These projects provide practical experience in building intelligent systems capable of analyzing text, recommending content, and recognizing images.
