# YouTube Views Prediction Project

## 1. Description
This project aims to predict the number of views on YouTube videos using machine learning algorithms. By analyzing data such as video titles, descriptions, upload times, and user interactions (likes, comments, and shares), the model can help content creators and marketers optimize their content strategies.

## 2. Background
YouTube is one of the largest video platforms, offering creators and marketers opportunities to reach a wide audience. Video view count is an important metric of success. This prediction model is designed to help understand the factors influencing video popularity and aid in designing more effective content.

## 3. Problem
The main challenge is accurately predicting the number of views on YouTube videos using attributes such as title, likes, comments, and other factors that influence user engagement and video popularity.

## 4. Method
### Data Preprocessing
- Cleaning data
- Handling missing values
- Removing duplicates
- Converting data types
- Managing outliers through log transformation and Z-score filtering

### Feature Extraction
- New features, such as “Time to Trending,” “Engagement Rate,” and “Social Activity,” are created to capture key factors that influence video popularity.

### Modeling
- The data is split into 70% training and 30% testing sets.
- Linear Regression and Random Forest algorithms, with hyperparameter tuning, are then applied for prediction.
