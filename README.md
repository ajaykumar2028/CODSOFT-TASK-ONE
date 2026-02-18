🎬 Movie Rating Prediction using Machine Learning
📌 Project Overview

This project builds a Machine Learning model to predict IMDb movie ratings based on categorical features such as:

Genre

Director

Actor 1

The project includes data preprocessing, feature encoding, model training using Linear Regression, performance evaluation, and data visualization to extract meaningful insights.

📂 Dataset Description

The dataset contains movie-related information including:

Genre – Category of the movie

Director – Director of the movie

Actor 1 – Lead actor

Rating – IMDb rating (Target Variable)

Votes – Number of user votes

Data Cleaning Steps Performed:

Removed rows with missing values in Rating, Genre, Director, and Actor 1

Converted Votes column from string to numeric

Replaced missing Votes values with median

Handled categorical features using One-Hot Encoding

🛠 Technologies Used

Python

Pandas

Matplotlib

Seaborn

Scikit-learn

🔄 Data Preprocessing

To handle categorical variables (Genre, Director, Actor 1), the following techniques were used:

ColumnTransformer

OneHotEncoder

Pipeline for combining preprocessing and model training

This ensures clean, scalable, and production-ready workflow.

🤖 Model Development
Model Used:

Linear Regression

Train-Test Split:

80% Training Data

20% Testing Data

Evaluation Metrics:

R² Score (Model Accuracy)

Mean Squared Error (MSE)

The model predicts IMDb ratings based on movie attributes.

📊 Visualizations Included

1️⃣ Actual vs Predicted Ratings

Scatter plot comparing true ratings with predicted ratings.

Helps evaluate model performance visually.

2️⃣ Distribution of IMDb Ratings

Histogram with KDE curve.

Shows overall rating distribution across movies.

3️⃣ Top 10 Movie Genres

Bar chart of most frequent genres.

Identifies popular categories.

4️⃣ Top 10 Directors by Average Rating

Bar chart showing directors with highest average IMDb ratings.

Highlights high-performing filmmakers.

Ajay Kumar S
B.Tech Student | Data Science Enthusiast
