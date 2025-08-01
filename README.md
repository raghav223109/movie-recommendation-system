# movie-recommendation-system
This is a content-based movie recommender system built using Python, Pandas, and Streamlit. It suggests movies similar to the one selected by the user, based on a precomputed similarity matrix.
# How It Works
The app loads a dataset of movies and their features.
A similarity score between movies is precomputed (using cosine similarity or similar metric).
When a user selects a movie, it recommends the top 5 similar movies.
# Files
movie_dict.pkl – Preprocessed dictionary containing movie metadata
similarity.pkl – Precomputed similarity matrix
app.py – Main Python script that runs the Streamlit app
# Features
.Movie Selection Dropdown
Choose any movie from a list of titles in an interactive dropdown.
.Content-Based Recommendation
Uses a similarity matrix to find and recommend the most similar movies.
.Instant Recommendations
Get top 5 similar movies instantly upon clicking "Recommend".
.Pretrained Similarity Model
Uses precomputed similarity scores for fast performance.
.Streamlit Web Interface
Clean and responsive interface that runs locally in your browser.
# Technologies Used
Python
Pandas
Pickle (for loading saved models)
Streamlit (for the web interface)
# data set link
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download

