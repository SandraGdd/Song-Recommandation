### Song Recommender Project

## Objective

This project aims to create a Python-based song recommendation system that enhances user experience by providing recommendations based on two main approaches:

Global Popularity: Suggesting songs that are widely recognized and trending.
Musical Similarity: Recommending songs acoustically similar to a user’s input.
The solution was designed as part of an initiative for Gnod, a platform providing personalized recommendations for music, art, and literature.

## Methodology

For this project, data on popular songs was scraped from sources such as the Billboard Hot 100. Additionally, detailed audio features of the songs were 
collected using the Spotify API to get acoustic properties like tempo, energy, and valence. Unsupervised learning techniques were applied to group 
songs based on their audio characteristics. The K-Means clustering algorithms was utilized.
The resulting clusters were used to identify songs with similar acoustic profiles, enabling tailored recommendations based on musical similarity.
