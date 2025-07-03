# Movie_recommendation_sys
This project builds a Content-Based Movie Recommender System using TF-IDF vectorization and cosine similarity. It recommends movies similar to a user-input movie based on their genres, cast, director, keywords, and tagline.


## Features

- Recommends movies based on content similarity
- Handles approximate user input using `difflib`
- Displays top 7 similar movie suggestions
- Uses cosine similarity for measuring closeness

## How It Works

1. **Data Preprocessing**
   - Loads movie metadata (title, genre, cast, director, etc.)
   - Handles missing values and combines key features into a single string

2. **Feature Extraction**
   - Converts combined text features into TF-IDF vectors

3. **Similarity Calculation**
   - Calculates cosine similarity between movies

4. **Movie Suggestion**
   - Finds the closest match to the input title
   - Sorts and displays top 7 most similar movies

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn (TfidfVectorizer, cosine_similarity)
- Difflib

## Getting Started

### Prerequisites

Install required libraries:

```bash
pip install pandas numpy scikit-learn
