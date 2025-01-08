# Movie-Recommendation-System
This repository contains a Movie Recommendation System that provides personalized movie suggestions using three different approaches:
1. **Popularity-Based** Recommendation System
2. **Content-Based** Recommendation System
3. **Collaborative Filtering** Recommendation System

The system is built using the MovieLens dataset and includes features like genre filtering, rating-based recommendations, and the option to select the number of recommendations.

## Features
- **Popularity-Based Recommendations**: Recommends movies based on their average ratings and the number of ratings they have received.
- **Content-Based Recommendations**: Recommends movies based on genre similarity using cosine similarity.
- **Collaborative Filtering**: Recommends movies based on user-item interactions and user similarity.
- **Audit Logging**: Logs every significant event (like genre selections, recommendation generation) for traceability and debugging.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- logs (optional, for auditing)
