# Kaggle_competition - Spaceship Titanic :rocket:

Welcome to the year 2912, where your data science skills are needed to solve a cosmic mystery. We've received a transmission from four lightyears away and things aren't looking good.

The Spaceship Titanic was an interstellar passenger liner launched a month ago. With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants from our solar system to three newly habitable exoplanets orbiting nearby stars.

While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!

## Objective 🎯
In this competition my task is to predict whether a passenger was transported to an alternate dimension during the Spaceship Titanic's collision with the spacetime anomaly.

## Description Of Dataset 📊

The dataset considered for this project is taken from Kaggle dataset (https://www.kaggle.com/competitions/spaceship-titanic/overview).

All the informations about passengers were in 3 csv files:

train.csv - Personal records for about two-thirds (~8700) of the passengers, to be used as training data.
	
test.csv - Personal records for the remaining one-third (~4300) of the passengers, to be used as test data.
	
sample_submission.csv - A submission file in the correct format.

## Methodology ⚙️
To predict if people were transported, I performed a train-val split of 80:20 on training data. I used 3 classifiers CatBoostClassifier, LGBMClassifier and XGBClassifier. All of them were tuned with optima to find optimal hyper-parameters. All the classifiers gives accuracy about 81% on val data.
Appropriate graphs and metrics were generated for the analysis and performance of the different models were compared.
