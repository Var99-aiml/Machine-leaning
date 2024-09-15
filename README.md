🎬 Movie Recommendation System

This contains a Movie Recommendation System that suggests movies based on a user's favorite movie. It employs content-based filtering to find similar movies by comparing feature similarity. The system ranks movies by their similarity score and provides a list of recommendations.

🎥 About the Project

The Movie Recommendation System takes a movie title as input and returns a list of movies similar to the given title. The system uses the following steps:

It matches the user-provided movie title with the closest match from the dataset.
It calculates the similarity score between the chosen movie and all other movies in the dataset.
It sorts movies based on their similarity scores and recommends the top matches.
The goal of this system is to provide personalized movie recommendations based on content similarity.

✨ Features

Content-based filtering: Recommends movies similar to the input movie based on feature comparison.
Top-N recommendations: Displays the top 30 most similar movies.
Interactive CLI: Users can input their favorite movie title via the command line.

🛠️ Technologies Used

Python for the core programming.
Pandas for data manipulation.
scikit-learn for handling vectorization and similarity computation.
difflib for string matching to find the closest movie title match.
