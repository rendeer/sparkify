# Sparkify project

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Files Description](#files)
4. [Result](#Result)

## Installation <a name="installation"></a>

This project uses the following software and Python libraries:

python==3.6.3 
pyspark==2.4.3 
pandas==0.23.3 
matplotlib==2.1.0
seaborn==0.8.1

You will also need to have software installed to run and execute a Jupyter Notebook.

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. And for Spark, you can do this using AWS or IBM Cloud.

## Project Motivation<a name="motivation"></a>

This is udacity's capstone project, using spark to analyze user behavior data from music app Sparkify.

Sparkify is a music app, this dataset contains two months of sparkify user behavior log. The log contains some basic information about the user as well as information about a single action. A user can contain many entries. In the data, a part of the user is churned, through the cancellation of the account behavior can be distinguished.

## Files Description<a name="files"></a>

**Sprakify .ipynb** Main file of the project, it demonstrates the process of using pyspark to explore the data and build the model.

## Result

The top 1 relevant feature is the life time, which is actually already an indirect indicator of if the user like the app or platform or not. The users who like the app will definitely stay longer. 

The second important feature is count of roll advert, which is as expected. As analyzed in churned vs stayed Analysis 1, if a user have to roll advertisement a lot, it might give them bad experience. 

The third important feature is count of adding friends. It shows the power of a friendship. The more people a user can find who share the same music taste, the more possible the user will stay.

I post a blog about the detail, you can find it [here]().