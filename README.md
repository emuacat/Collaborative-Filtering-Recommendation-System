# Collaborative Filtering Recommendation System

## Overview
In this project, I create a recommendation system using collaborative filtering. Utilizing Jupyter Notebook, a web-based integrated development environment for Python, and various Python libraries, the system recommends movies based on user similarity. The dataset, containing sufficient ratings from users to make quality recommendations, is available in the same directory as the Jupyter file.

## Tasks and Implementation

### Interaction Matrix
To create a collaborative filtering recommendation system, an interaction matrix is formed to represent the relationship of every user with every movie in terms of ratings. The density of this matrix directly impacts the quality of the recommendations.

- **Task**: Calculate the sparsity of the interaction matrix.

### User-User Collaborative Filtering
User-user collaborative filtering is implemented by finding the similarity among users.

- **Task**: Use cosine similarity to find the similarity among users.

### Movie Recommendations
With the cosine similarity matrix, the system recommends movies to users according to their taste.

- **Task**: Create a function that:
  1. Receives a user's ID.
  2. Finds the 10 most similar users (k=10).
  3. Finds the average rating of the movies rated by these k users.
  4. Returns the top 10 rated movies.

### Function Execution
Run the function created in the previous task to view the recommendations provided to a user.

- **Task**: Ensure the arguments provided to the function have the required data type to call the function.

## Application
This project aims to create an application that receives a User ID and provides all the recommendations for that specific user. For this, the recommendation function created in the Jupyter Notebook should be callable in a Python file via a wrapper function.

## Dataset
The dataset used in this project is included in the repository and is vital to making meaningful recommendations.

## Running the Project
Instructions for setting up and running the project locally will depend on the specific implementation and requirements.

## Contributing
Feel free to contribute to the project by opening issues or submitting pull requests.

## License
Include information about the license here, if applicable.
