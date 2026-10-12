# Netflix Content Segmentation

## Project Overview

This project uses unsupervised machine learning to group Netflix titles into clusters based on their content features.

## Dataset

The dataset contains Netflix titles and information such as:

- Content Type
- Release Year
- Country
- Genres

## Technologies Used

- Python
- Pandas
- Scikit-learn
- K-Means Clustering
- OneHotEncoder
- StandardScaler
- PCA
- Matplotlib

## Project Workflow

1. Load the Netflix dataset.
2. Select relevant features.
3. Handle missing values.
4. Encode categorical features.
5. Scale numerical features.
6. Apply K-Means clustering with five clusters.
7. Analyze cluster sizes and content categories.
8. Visualize clusters using PCA.
9. Evaluate clustering performance using the Silhouette Score.

## Results

- Number of clusters: 5
- Silhouette Score: 0.142

The clustering results show some differences between content groups. However, the Silhouette Score indicates limited separation between clusters, so further improvements may be possible.

## Conclusion

The project demonstrates how K-Means can be used to explore and group Netflix titles using content-related features. PCA was used to visualize the clusters, and the Silhouette Score was used to evaluate their separation.

## Author

Fahd Sherif