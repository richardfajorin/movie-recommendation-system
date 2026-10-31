# Movie Recommendation System Using Collaborative Filtering and SVD

## Project Overview

This project explores how recommendation systems can predict user preferences and suggest movies using historical rating patterns.

Using the MovieLens 100K dataset, I implemented three recommendation approaches: User-Based Collaborative Filtering, Item-Based Collaborative Filtering, and Singular Value Decomposition (SVD).

The project focuses on understanding recommendation algorithms, identifying patterns in user preferences, generating movie recommendations, and evaluating model performance.

## Dataset

The project uses the MovieLens 100K dataset.

- 100,000 movie ratings
- 943 users
- 1,682 movies

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Scikit-Surprise
- Google Colab

## Recommendation Algorithms

### 1. User-Based Collaborative Filtering
Identifies users with similar movie preferences and uses their ratings to recommend movies.

### 2. Item-Based Collaborative Filtering
Identifies movies with similar rating patterns and recommends movies related to those a user enjoys.

### 3. Singular Value Decomposition (SVD)
Uses matrix factorization to identify hidden patterns in user-movie ratings and predict user preferences.

## Model Evaluation

The dataset was divided into 80% training data and 20% testing data.

### Precision@10 Results

| Algorithm | Average Precision@10 |
|---|---:|
| User-Based | 70.76% |
| Item-Based | 65.78% |
| SVD | 72.48% |

SVD achieved the highest average Precision@10 in this experiment.

### SVD Rating Prediction Metrics

- RMSE: 0.9346
- MAE: 0.7376

## Key Learnings

- Understanding recommendation systems.
- Building user-item matrices.
- Applying cosine similarity.
- Implementing collaborative filtering.
- Understanding matrix factorization.
- Evaluating machine learning models.
- Comparing recommendation algorithms.

## Limitations

- Precision@10 was evaluated using held-out rated movies rather than the entire movie catalogue.
- The number of evaluated users differs slightly between algorithms.
- Recommendations are experimental and have not yet been deployed as a live application.

## Conclusion

This project provided practical experience implementing recommendation algorithms and understanding how machine learning can be used to personalize content recommendations.

It also provided an opportunity to compare different approaches and understand their strengths and limitations.

## Author

**Richard Fajorin**

Biomedical Engineering Student | Data Analytics | Machine Learning
