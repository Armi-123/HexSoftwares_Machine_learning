# Music Recommendation System using Machine Learning

## Overview

The Music Recommendation System is a Machine Learning project designed to recommend songs based on user preferences and music similarity. The system analyzes song attributes such as genres and identifies similar songs using content-based filtering techniques.

Recommendation systems are widely used by music streaming platforms to enhance user experience by suggesting relevant songs and helping users discover new music that matches their interests.

---

## Objective

The primary objective of this project is to build a recommendation engine that suggests similar songs based on their genre and content features.

The system helps users discover music aligned with their preferences while demonstrating the practical implementation of recommendation algorithms.

---


## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Jupyter Notebook

---

## Machine Learning Techniques

* Content-Based Filtering
* Count Vectorization
* Cosine Similarity

---

## Dataset

**File:** `songs.csv`

### Dataset Columns

| Column | Description |
| ------ | ----------- |
| Song   | Song Name   |
| Artist | Artist Name |
| Genre  | Music Genre |

### Sample Data

| Song            | Artist          | Genre |
| --------------- | --------------- | ----- |
| Shape of You    | Ed Sheeran      | Pop   |
| Believer        | Imagine Dragons | Rock  |
| Blinding Lights | The Weeknd      | Pop   |

---

## Project Workflow

1. Load the music dataset.
2. Perform data preprocessing.
3. Combine song features.
4. Convert text data into numerical vectors.
5. Calculate similarity scores using Cosine Similarity.
6. Recommend songs based on similarity.
7. Display top recommended songs.

---

## Features

* Music Recommendation Engine
* Genre-Based Similarity Analysis
* Content-Based Filtering
* Similar Song Discovery
* Personalized Suggestions

---

## Algorithm Used

### CountVectorizer

Converts text-based song features into numerical vectors that can be processed by Machine Learning algorithms.

### Cosine Similarity

Measures the similarity between songs and recommends songs with the highest similarity scores.

---

## Output

The system recommends songs similar to the selected song based on genre and content similarity.

### Example

**Input Song:**

```text
Shape of You
```

**Recommended Songs:**

```text
Blinding Lights
Levitating
Perfect
Stay
```

---

## Applications

* Music Streaming Platforms
* Personalized Music Suggestions
* Entertainment Applications
* Playlist Generation
* Music Discovery Systems

---

## Project Structure

```text
Task1_Project2_Music_Recommendation_System/
│
├── Task1_Project2_Music_Recommendation_System.ipynb
├── songs.csv
├── requirements.txt
└── README.md
```

---

## Tools and Libraries

* Pandas
* NumPy
* Scikit-Learn
* Matplotlib

---

## Learning Outcomes

Through this project, the following concepts were implemented:

* Recommendation Systems
* Content-Based Filtering
* Text Vectorization
* Similarity Measurement
* Data Preprocessing
* Machine Learning Applications

---

## Future Enhancements

* Collaborative Filtering
* User-Based Recommendations
* Mood-Based Recommendations
* Real-Time Recommendation Engine
* Integration with Music Streaming APIs

---

## Conclusion

The Music Recommendation System successfully demonstrates how Machine Learning can be used to recommend songs based on content similarity. By leveraging Count Vectorization and Cosine Similarity, the system provides personalized recommendations and enhances the music discovery experience for users.

This project showcases the practical implementation of recommendation systems, which are widely used in modern streaming platforms and entertainment applications.

---

## Author

**Armi Sherathiya**

HexSoftwares Machine Learning Project
