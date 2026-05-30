# Music Recommendation System

## Overview

The Music Recommendation System is a Machine Learning project that recommends songs based on their audio characteristics and musical similarity. The system uses Spotify track data and recommends songs similar to the user's selected track using content-based filtering techniques.

This project demonstrates the use of Machine Learning for recommendation systems by analyzing song features such as danceability, energy, tempo, popularity, and mood.

---

## Features

* Music recommendation based on song similarity
* Content-based filtering approach
* Uses Spotify audio feature dataset
* Nearest Neighbors algorithm with cosine similarity
* Fast and memory-efficient recommendation model
* Interactive song recommendation system

---

## Dataset

The project uses the Spotify Tracks Dataset containing:

* Track name
* Artist
* Genre
* Popularity
* Danceability
* Energy
* Loudness
* Speechiness
* Acousticness
* Instrumentalness
* Liveness
* Valence
* Tempo

---

## Machine Learning Workflow

### 1. Data Collection

Spotify tracks dataset is loaded using Pandas.

### 2. Data Preprocessing

* Removed missing values
* Removed duplicate records
* Selected important audio features
* Applied MinMax Scaling

### 3. Model Building

The recommendation system is built using:

* Nearest Neighbors Algorithm
* Cosine Similarity
* Content-Based Filtering

### 4. Recommendation Process

When a user enters a song name:

1. The system finds the selected song.
2. Extracts its audio features.
3. Compares it with other songs.
4. Returns the most similar songs.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## Project Structure

Music-Recommendation-System/
│
├── dataset/
│ └── spotify_tracks.csv
│
├── notebook/
│ └── Music_Recommendation_System.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore

---

## Installation

Clone the repository:

```bash
git clone <your-repository-link>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook and open:

```bash
Music_Recommendation_System.ipynb
```

---

## Example Usage

```python
recommend_music('Hold On')
```

Sample Output:

| Track Name | Artist   | Genre |
| ---------- | -------- | ----- |
| Song 1     | Artist 1 | Pop   |
| Song 2     | Artist 2 | Indie |
| Song 3     | Artist 3 | Rock  |

---

## Future Improvements

* Web application integration
* Spotify API integration
* Hybrid recommendation model
* Personalized user profile recommendations

---

## Author

Mohamed Riyaz
