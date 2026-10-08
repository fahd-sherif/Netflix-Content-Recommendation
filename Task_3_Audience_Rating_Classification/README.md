# Netflix Audience Rating Classification

## Project Overview

This project uses machine learning to predict the audience rating category of Netflix titles.

The project includes data preprocessing, feature encoding, classification models, hyperparameter tuning, and model evaluation.

## Dataset

The dataset contains Netflix titles with information such as:

- Type
- Title
- Country
- Rating
- Release Year
- Duration
- Genres

## Technologies Used

- Python
- Pandas
- Scikit-learn
- OneHotEncoder
- Decision Tree
- Random Forest
- GridSearchCV

## Project Workflow

1. Load the dataset
2. Analyze rating categories
3. Create rating categories
4. Select features and target
5. Encode categorical features
6. Split the data into training and testing sets
7. Train classification models
8. Tune the Random Forest model
9. Evaluate and compare model performance

## Models Used

### Decision Tree

Accuracy: 58.59%

### Random Forest

Accuracy: 61.55%

### Tuned Random Forest

Accuracy: 62.06%

## Results

| Model | Accuracy |
|---|---:|
| Decision Tree | 58.59% |
| Random Forest | 61.55% |
| Tuned Random Forest | 62.06% |

The Tuned Random Forest achieved the best accuracy among the tested models.

## Conclusion

The project successfully built a machine learning classification system for predicting Netflix audience rating categories.

After comparing different models and tuning the Random Forest parameters, the Tuned Random Forest achieved the best test accuracy of 62.06%.

## Author

Fahd Sherif