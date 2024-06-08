# ABOUT
**This Python script** is designed to provide movie recommendations based on similarities between movies. It begins by preprocessing the movie dataset, merging relevant columns, handling missing values, and preparing text data for analysis by combining features like genres, keywords, cast, crew, and overview into a new 'tagline' column. *Text data* is then converted into numerical vectors using **CountVectorizer**, with stemming applied to normalize words. Cosine similarity is calculated between movies based on their feature vectors, allowing for the determination of similarity scores for each pair of movies. The recommendation function takes a movie title as input, identifies the index of the movie in the dataset, retrieves similarity scores with other movies, sorts them based on similarity, and selects the top recommendations, which are then printed. The script demonstrates a content-based recommendation system that suggests similar movies based on textual features, offering a practical application of natural language processing techniques in movie recommendation.

# 🎬 Movie Recommendation System

Welcome to the Movie Recommendation System! This project provides personalized movie recommendations based on various metadata such as genres, keywords, cast, and crew. It's built using Python and several popular libraries.

## 🚀 Features

- **Data Merging:** Combines data from multiple sources to create a comprehensive dataset.
- **Text Processing:** Cleans and processes textual data to ensure accurate recommendations.
- **Similarity Calculation:** Uses cosine similarity to find and recommend movies similar to a given title.
- **Easy to Use:** Simple function call to get recommendations.

## 📊 Data Sources
TMDB 5000 Credits Dataset: Contains information about movie credits.
TMDB 5000 Movies Dataset: Contains metad![image](https://github.com/Aayu-1011/Movie-Recommendation/assets/134579511/57b6fe6f-3b43-4aca-ad01-4e0f17c082a4)
ata for 5000 movies.

