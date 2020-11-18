# Titanic
The sinking of the Titanic is one of the most infamous shipwrecks in history.
On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after
colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in
the death of 1502 out of 2224 passengers and crew. While there was some element of luck involved in
surviving, it seems some groups of people were more likely to survive than others. In this challenge, the
goal is to build a predictive model that answers the question: “what sorts of people were more likely to
survive or die?” using passenger data (i.e. name, age, gender, socio-economic class, etc.)


The goal of the project was to predict the survival of passengers based off a set of data. I used Kaggle competition "Titanic: Machine Learning from Disaster" (see https://www.kaggle.com/c/titanic/data) to retrieve necessary data and evaluate accuracy of predictions. The historical data has been split into two groups, a 'training set' and a 'test set'. For the training set, provided with the outcome (whether or not a passenger survived). And used this set to build the model to generate predictions for the test set. For each passenger in the test set, and had to predict whether or not they survived the sinking. The score was the percentage of correctly predictions.
