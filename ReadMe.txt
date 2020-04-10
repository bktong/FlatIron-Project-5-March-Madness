
# Overview
I split this project into multiple large sections. Data / Model / Execution and those are the 3 phases relevant to the actual mod 5 project.
There are two other notebooks.  The "Searching for Cinderella" notebook which is essentially a cleaned up version of my data exploration. The second is a logloss notebook where I was playing around with the Logloss scoring metric kaggle uses to score the tournament.


# How to Run Model
1. First run "Project 5 - March Madness Data Prep.ipynb" Jupyter Notebook to create our dataset.

2. If you want to run the model, "Project 5 - Model.ipynb" to run the classification model.  

3. We took our optimal model and parameters and used those to test our predictions in "Project 5 - Prediction Testing.ipnyb"



#Hardware:   
This code was run with the following computer specs.  
Intel Core I5-6200U CPU at 2.5GHz, 2400 Mhz, 4 Core, 8GB RAM, Windows 10

#Software:   
This project used Python 3.7 and incorporated multiple python packages available at www.anaconda.com

#Data:
- Kaggle Dataset:  www.kaggle.com
A lot of the data files provided by Kaggle were very large.  This repo only kept datasets we used for this project.
- The larger unused files can still be found at kaggle.com
- Sponsorship data:   scraped off internet, multiple sources, primarily from google images taken during the current season.  It should be noted that multiple teams have switched sponsors when their contracts are up.  The data available is ONLY up to date as of March 2020.
- Additional Notebooks were created for my personal exploration, and not necessary for the project itself.

#Side Effects:
Running the code will overwrite the existing files.

#Assumptions: 
We are only using the men's data as play styles between the two leagues are different.   For a future exercise it would be interesting to catalogue the weight differences between the features in our model.

We only use our regular season data to test our tournament results since the goal of the exercise is to use all data available to use to predict matchup winners in this years Tournament.

That said, I'll assume I had a perfect model until proved otherwise.

#License:  
Free for all to use.

