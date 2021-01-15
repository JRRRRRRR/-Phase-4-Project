# Movie Recommendation System
Phase-4-Project
# Introduction 
* Business problems: 
   Using the movie lens 100k data to analyze the movies’ rating and make a movie recommendation system.
* Outline:
1. Best Rating Movie
    * Count the total movie rating and rating times 
    * Sort the movies by mean rating
    * Determine the best movie base on mean rating and rating times
2. Best Movie Genre
    * Build a genre data frame for all movies
    * Fill the genre data frame with total rating and rating times
    * Sort the genre data frame and determine the best one
3. Recommendation System
    * Train a suitable algorithm
    * Tune hyper parameter for this model
    * Build a recommendation system

# Techniques
* Notebook link: https://github.com/JRRRRRRR/Movie-Recommendation-System/blob/main/final.ipynb
* Data collecting, Data cleaning, Exploratory data analysis, recommenation system and Visualization are all in the Jupyter Notebook.
* A PowerPoint and pdf for presentation
* A 5 minutes recording to review
* https://youtu.be/V2H_HSMK7Qw
* Blog: https://road2dataanalyst.blogspot.com/2020/12/movie-recommendation-system.html

# Recommendation
* For users: 
  Some best movies are in crime and drama genres. And these two genres both having around 3.68 mean rating which are the top five genres in our movies data.
  If you don’t have any idea what genre movies to watch,  film-noir will be your best choice because it has the highest mean rating(3.955702) with 1140 rating times.
  If you need more accuracy recommendation, you can use the recommendation system.    

* For analysts: 
  SVDpp is an accuracy algorithm in this case but the shortcoming is costing a long run time.
  GridsearchCV is a handy tool to help us tune model parameters, but the shortcoming also is costing a long run time.

# Future Work
* Algorithm: Try more algorithms from other packages
* Hyper Parameter Tuning: tune more parameters of the models and use random search before grid search
* Exploratory Data Analysis: Exploratory more characteristics from the dataset such as timestamp column

 
# Summary
From this project, I have a new overview of movie industry. I found some relationship between rating and genres. What's more, I had the experience that applying recommendation system in our real world. It provided me a chance to review my knowledge and skills. I found my weakness and make a plan to improve those. And the interesting recommendation system including information input and recommendation list attract me into this field.

