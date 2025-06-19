# A machine learning project that predicts movie ratings using Random Forest Regressor based on various movie features.

Features
Predicts movie ratings based on:
Year of release
Duration
Genre
Director
Actors
Number of votes
Visualizes movie data with various plots
Provides model performance metrics
Requirements
Python 3.x
Required Python packages:
pandas
numpy
matplotlib
seaborn
scikit-learn
Installation
Clone this repository
Install required packages:
pip install pandas numpy matplotlib seaborn scikit-learn
Usage
Place your movie dataset (CSV file) in the project directory
Run the script:
python rating.py
Dataset
The project uses the IMDb Movies India dataset. Make sure your dataset contains the following columns:

Name
Year
Duration
Genre
Director
Actor 1
Actor 2
Actor 3
Votes
Rating
Output
The script will:

Display data analysis and visualizations
Show model performance metrics
Provide feature importance analysis
Allow you to predict ratings for new movies
Example
# Example prediction
predicted_rating = predict_movie_rating(
    year=2020,
    duration=112,
    genre='Drama',
    director='Sharan Sharma',
    actor1='Janvi Kapoor',
    actor2='Pankaj Tripathi',
    actor3='Angad Bedi',
    votes=36000
)
