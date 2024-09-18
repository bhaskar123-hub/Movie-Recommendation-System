# Movie Recommender System Using TMDB Dataset
Overview
This project implements a content-based movie recommender system that suggests similar movies to users based on their preferences. Utilizing the TMDB (The Movie Database) dataset, the system leverages various movie features such as genres, cast, and plot summaries to provide personalized recommendations.

Key Features
Dataset: Utilizes the TMDB dataset containing comprehensive movie details, including titles, genres, cast, and plot summaries.
Content Features: Extracts and vectorizes features like genres, keywords, and overviews using techniques such as Count Vectorization and TF-IDF.
Cosine Similarity: Employs cosine similarity to compute similarity scores between movie feature vectors, facilitating the recommendation process.
User Interface: Developed with Streamlit to provide an interactive web application where users can select a movie and view recommendations.
How It Works
Fetching Movie Posters: The application retrieves movie posters from the TMDB API based on movie IDs.
Recommendation Logic: Upon selecting a movie, the system calculates and returns the top similar movies using cosine similarity.
![image](https://github.com/user-attachments/assets/699f2042-18b1-4708-b2ed-91375e232ae7)
