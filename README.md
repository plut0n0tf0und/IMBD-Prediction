# IMBD-Prediction
This project uses machine learning to predict IMDb movie ratings. Leveraging IMDb data and various algorithms, it estimates a movie's rating based on its attributes. Valuable for filmmakers and movie enthusiasts.

## About the data set
The data set along with its description is defined here (https://www.kaggle.com/datasets/luiscorter/netflix-original-films-imdb-scores)

## Steps
* After preprocessing/cleaning the data there were around 2000 data points.    
* The main task was to predict the IMDB rating of a movie.  
* This was considered as a classification problem by taking 10 classes 1-10 i.e the rating.  
* There were initially many features which was then reduced using the domain knowledge finally only 9 features was taken into consideration, the filtered and processed data is saved in the after csv.csv file.  
* All the models are pickled in the models folder.

## Usage
To view the predictions run the main.py just change the filename of your data
