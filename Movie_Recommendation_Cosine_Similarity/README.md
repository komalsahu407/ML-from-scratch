# Movie Recommendation System

This project is a simple **Movie Recommendation System** that recommends similar movies based on user ratings.

## Project Overview

The project creates a movie-user rating matrix and uses **Cosine Similarity** to find movies that are similar to a selected movie.

## Algorithm / Technique

* Cosine Similarity
* Similarity-based Recommendation

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

## Dataset

The project uses:

* Movie dataset
* User ratings dataset

## How It Works

1. Load movie and ratings datasets.
2. Merge the datasets using `movieId`.
3. Select relevant movie rating information.
4. Create a movie-user rating matrix.
5. Calculate similarity between movies using Cosine Similarity.
6. Recommend the top 5 similar movies.

## Example

For **Toy Story (1995)**, the system recommends 5 similar movies based on rating similarity.

## Author

**Komal Sahu**
