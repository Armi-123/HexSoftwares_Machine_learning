# Movie Recommendation System using Machine Learning

## Overview

The Movie Recommendation System is a Machine Learning project that suggests movies to users based on content similarity and movie attributes. The system analyzes movie genres, descriptions, and other metadata to recommend films that closely match a user's interests.

Recommendation systems are widely used by streaming platforms such as Netflix, Amazon Prime Video, Disney+, and YouTube to provide personalized content and enhance user engagement.

This project demonstrates how Machine Learning techniques can be used to build an intelligent recommendation engine that helps users discover new movies based on their preferences.

---

## Objective

The primary objective of this project is to develop a content-based movie recommendation system that suggests similar movies using textual information such as genres and movie overviews.

The project aims to improve user experience by providing personalized movie recommendations based on similarity analysis.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Jupyter Notebook

---

## Machine Learning Techniques

### TF-IDF Vectorization

TF-IDF (Term Frequency-Inverse Document Frequency) converts textual movie descriptions into numerical vectors that can be processed by Machine Learning algorithms.

### Cosine Similarity

Cosine Similarity measures the similarity between movie vectors and identifies movies with comparable content.

### Content-Based Filtering

Content-Based Filtering recommends movies based on similarities in genres, descriptions, and other movie features rather than relying on user ratings.

---

## Dataset

**File:** `movies.csv`

### Dataset Attributes

| Column            | Description       |
| ----------------- | ----------------- |
| id                | Movie Identifier  |
| title             | Movie Title       |
| genre             | Movie Genres      |
| original_language | Language          |
| overview          | Movie Description |
| popularity        | Popularity Score  |
| release_date      | Release Date      |
| vote_average      | Average Rating    |
| vote_count        | Number of Votes   |

### Sample Movies

* The Shawshank Redemption
* The Godfather
* Schindler's List
* Spirited Away
* Dilwale Dulhania Le Jayenge

Dataset Size:

* 10,000+ Movies

---

## Project Workflow

1. Load movie dataset.
2. Clean and preprocess movie information.
3. Combine relevant text features.
4. Convert text into TF-IDF vectors.
5. Calculate similarity scores using Cosine Similarity.
6. Build recommendation engine.
7. Recommend similar movies based on user input.
8. Visualize top-rated movies.

---

## Features

* Personalized Movie Recommendations
* Content-Based Filtering
* Similarity Analysis
* Genre-Based Recommendations
* Movie Metadata Processing
* Top-Rated Movies Visualization
* User-Friendly Recommendation Engine

---

## Recommendation Process

The system:

1. Accepts a movie title as input.
2. Finds the selected movie in the dataset.
3. Calculates similarity scores with all other movies.
4. Sorts movies based on similarity.
5. Returns the most relevant movie recommendations.

---

## Example Recommendation

### Input Movie

```text
The Godfather
```

### Recommended Movies

```text
The Godfather: Part II
Goodfellas
Casino
Once Upon a Time in America
Scarface
```

---

## Data Visualization

The project includes visualizations such as:

* Top Rated Movies
* Most Popular Movies
* Genre Distribution
* Movie Rating Analysis

These visualizations provide insights into movie trends and dataset characteristics.

---

## Applications

* Movie Streaming Platforms
* Personalized Entertainment Systems
* Content Recommendation Engines
* OTT Platforms
* Online Video Services

---

## Project Structure

```text
Task2_Project3_Movie_Recommendation_System/
│
├── Task2_Project3_Movie_Recommendation_System.ipynb
├── movies.csv
├── requirements.txt
└── README.md
```

---

## Tools and Libraries

* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Jupyter Notebook

---

## Learning Outcomes

Through this project, the following concepts were implemented:

* Recommendation Systems
* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Cosine Similarity
* Content-Based Filtering
* Data Preprocessing
* Feature Engineering
* Similarity Analysis

---

## Future Enhancements

* Collaborative Filtering
* Hybrid Recommendation Systems
* User Rating Integration
* Real-Time Recommendations
* Web Application Deployment
* Deep Learning-Based Recommendations

---

## Conclusion

The Movie Recommendation System successfully demonstrates how Machine Learning can be used to create intelligent recommendation engines. By leveraging TF-IDF Vectorization, Cosine Similarity, and Content-Based Filtering, the system provides personalized movie suggestions based on content similarity.

This project highlights the importance of recommendation systems in modern entertainment platforms and showcases the practical application of Machine Learning in enhancing user experience.

---

## Author

**Armi Sherathiya**

HexSoftwares Machine Learning Internship

2025
