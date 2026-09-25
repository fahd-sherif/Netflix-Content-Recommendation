# Netflix Content Recommendation System

## Project Overview

This project is a content-based recommendation system for Netflix movies and TV shows.

The system recommends similar titles based on their content features.

## Dataset

The dataset contains Netflix titles and information such as:

- Type
- Title
- Director
- Country
- Rating
- Genres

## Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF
- Cosine Similarity
- Jupyter Notebook

## Project Workflow

1. Load the Netflix dataset.
2. Explore the dataset.
3. Select the content features.
4. Combine the selected features into one content column.
5. Convert text data into numerical values using TF-IDF.
6. Calculate similarity using Cosine Similarity.
7. Generate recommendations for selected titles.
8. Evaluate the recommendations using shared genres.

## Results

The recommendation system was tested using different Netflix titles such as:

- Breaking Bad
- Stranger Things
- The Crown

The tested recommendations achieved a 100% simple evaluation score based on the presence of at least one shared genre between the original title and each recommended title.

## Conclusion

The project demonstrates how content-based recommendation systems can be built using text features, TF-IDF, and Cosine Similarity.

## Author

Fahd Sherif