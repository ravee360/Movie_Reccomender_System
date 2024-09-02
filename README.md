# Movie Recommendation System
This repository contains a movie recommendation system that predicts the next movie a user might want to watch based on their input. The system uses a dataset downloaded from The Movie Database (TMDB) and employs TMDB's API to fetch posters for the recommended movies. The recommendation engine leverages vectorization techniques to suggest similar movies.

## Features
- Movie Recommendations: Suggests movies based on the input movie name.
- Movie Posters: Fetches and displays posters of the recommended movies using TMDB API.
- Exploratory Data Analysis (EDA): Includes detailed EDA to understand the dataset.
= Vectorization Technique: Uses vectorization methods to compute similarities and recommend movies.
## Project Structure
- notebooks/: Jupyter notebooks for EDA, model building, and evaluation.
- scripts/: Python scripts for data preprocessing, model training, and inference.
- data/: Directory containing the original and processed datasets.
- app/: Streamlit application for the frontend.
- requirements.txt: List of all Python dependencies required for the project.
## Dataset
The dataset for this project is sourced from [Kaggle]('https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata'). It includes information about various movies such as genres, ratings, overviews, and more. The TMDB API is used to fetch movie posters for the recommendations.
## Usage
- Enter the name of a movie you like in the input box.
- The app will display a list of recommended movies along with their posters.
- Click on any recommended movie to get more details.
## Methodology
- Exploratory Data Analysis (EDA): Conducted EDA to gain insights into the dataset, such as the distribution of genres, ratings, and popularity.
- Vectorization: Used vectorization techniques (like TF-IDF) to convert text data into numerical format for similarity calculations.
- Cosine Similarity: Computed cosine similarity between movie vectors to recommend movies that are most similar to the input movie.
## Results
The recommendation model was able to suggest movies with high relevance based on user input. Below is a sample output of the movie recommendations:


## Future Work
- Integrate user ratings to improve the recommendation quality.
- Explore deep learning techniques for more advanced recommendations.
- Add support for recommending TV shows and other media types.
## Acknowledgments
- TMDB for providing the API and dataset.
- Streamlit for creating a simple and effective web application framework.

## Contact
For any questions or suggestions, please feel free to reach out at my linkedin as mentioned in my profile.
