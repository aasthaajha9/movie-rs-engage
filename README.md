# BUILDING MOVIE  RECOMMENDATION SYSTEM USING STREAMLIT AND DEPLOYING ON HEROKU 
 
In this challenge , we will build the movie recommendation system using collaborative filtering with Streamlit, the k-Nearest Neighbours machine learning model and using classification technique of recommending . Lastly we will deploy our website using Heroku cloud server. 

## TECK STACKS- 

HEROKU
https://www.heroku.com/platform

PYTHON 
3.10 WINDOWS VERSION

STREAMLIT
 https://streamlit.io/

JUPYTER LAB  
https://jupyter.org/

 DATASET 
https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset
 

## DATASET 

 Link- https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset 

## DATASET PREPROCESSING AND MODEL BUILDING 

 I have packed the final model in Json which is in built after which I have created custom data set by creating new Data framework using  movie name , genre name, imdb score to predict the similarity. 
After extraction I worked on  K nearest neighbour Model by implementing K nearest algorithm. 

## APPLICATION BUILDING- 
 
Now that we have the pre processed dataset, we can start building our main application. We will be using Streamlit , a Python web framework for building web apps for Machine Learning and Data Science. 
We can start building our machine learning model to recommend movies. There are many ways to approach this. A simple approach is to use a k Nearest Neighbour model to get the top movies that are closest in distance with the set of feature inputs selected by the user. These “feature inputs” include the genre of interest, Imdb scores and favourite movies . 

### To run the streamlit application on localhost, you can run: 
streamlit run app.py 

## DEPLOYMENT- 
When it comes to web deployment, there are a ton of options to choose. Streamlit Cloud supports its own deployment service, but I personally found Heroku very easy to use in the past, so this is what I will use. 
Create Necessary Files 
Here are the files you need to deploy on Heroku

•	requirements.txt: a text file containing a list of all dependencies and their versions needed for the application 
  
•	setup.sh: Shell file for setting up the app on Heroku 
  
•	Procfile: The entry point that Heroku uses to run and start the app 

## DEPLOYMENT LINK-
https://movie-rs-engage.herokuapp.com/


