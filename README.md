# Movie Recommendation System

## Description

The Movie Recommendation System is a Machine Learning project that recommends movies based on the user's selected movie using a **Content-Based Filtering** approach. Instead of relying on user ratings, the system analyzes the content of movies such as **overview, genres, keywords, cast, and crew** to identify similarities between movies.

The recommendation engine preprocesses movie metadata, extracts important textual features, converts them into numerical vectors using **TF-IDF Vectorization**, and computes similarity scores using **Cosine Similarity**. Based on these similarity scores, the system recommends the **Top 10 most relevant movies** that closely match the selected movie.

This project demonstrates the practical application of **Natural Language Processing (NLP)** and **Machine Learning** techniques in building an intelligent recommendation system.

---

# Objectives

- Build an intelligent movie recommendation engine.
- Recommend movies similar to the user's interests.
- Learn feature extraction from textual data.
- Understand Content-Based Recommendation Systems.
- Implement Machine Learning techniques for real-world applications.

---

# Technologies Used

- Python
- Machine Learning
- Natural Language Processing (NLP)
- Jupyter Notebook

---

## Libraries Used

- **Pandas** – For loading, cleaning, and manipulating movie datasets.
- **NumPy** – For numerical computations and array operations.
- **Scikit-learn** – For implementing machine learning algorithms and similarity calculations.
- **TF-IDF Vectorizer** – Converts textual movie information into numerical feature vectors.
- **Cosine Similarity** – Measures the similarity between movies based on their feature vectors.
- **AST (Abstract Syntax Trees)** – Converts string representations of lists and dictionaries into Python objects for data preprocessing.
- **Jupyter Notebook** – Used for developing, testing, and analyzing the recommendation system.

---

# Machine Learning Concepts

- Content-Based Recommendation System
- Natural Language Processing (NLP)
- Text Preprocessing
- Feature Engineering
- TF-IDF Vectorization
- Cosine Similarity

---

# Dataset

The project uses the **TMDB 5000 Movie Dataset**, which contains detailed information about thousands of movies.

### Dataset Files

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

The datasets include:

- Movie Title
- Overview
- Genres
- Keywords
- Cast
- Crew
- Movie ID
- Popularity
- Release Date

---

# Project Workflow

### Step 1: Import Required Libraries

Import all necessary Python libraries for data processing and machine learning.

### Step 2: Load Dataset

Load the Movies and Credits datasets into Pandas DataFrames.

### Step 3: Merge Datasets

Merge both datasets using the movie title to create a single dataset.

### Step 4: Select Important Features

Extract only the relevant columns:

- Movie ID
- Title
- Overview
- Genres
- Keywords
- Cast
- Crew

### Step 5: Data Preprocessing

- Handle missing values
- Convert JSON-like strings into Python objects
- Extract useful information from genres, cast, crew, and keywords
- Clean and normalize textual data

### Step 6: Feature Engineering

Combine all important movie features into a single text column (tags).

### Step 7: Text Vectorization

Convert the textual data into numerical feature vectors using **TF-IDF Vectorizer**.

### Step 8: Similarity Calculation

Calculate movie similarity using **Cosine Similarity**.

### Step 9: Movie Recommendation

When a user selects a movie, the system identifies the most similar movies based on similarity scores and recommends the **Top 10 movies**.

---

#  Features

-  Content-Based Movie Recommendation
-  Search movies by title
-  Uses genres, keywords, cast, crew, and overview
-  Machine Learning powered recommendations
-  Fast similarity computation
-  TF-IDF Vectorization
-  Cosine Similarity algorithm
-  Data preprocessing and feature engineering
-  Simple and easy-to-understand implementation

---

#  Recommendation Algorithm

The recommendation system begins by loading the movie dataset and performing data cleaning to remove missing or unnecessary information. Important movie features such as genres, cast, crew, keywords, and overview are extracted and combined into a single text field. This text is then converted into numerical feature vectors using **TF-IDF Vectorization**. Finally, **Cosine Similarity** is applied to compare movies and recommend the top 10 most similar movies based on the selected movie.

---

# Advantages

- Personalized movie recommendations
- Fast recommendation generation
- No user ratings required
- Easy to extend with additional datasets
- Suitable for beginners learning recommendation systems

---

# Skills Demonstrated

- Python Programming
- Machine Learning
- Natural Language Processing
- Data Cleaning
- Feature Engineering
- Text Mining
- Recommendation Systems
- Data Analysis
- Scikit-learn
- Pandas
- NumPy

