# AppointmentsNoShow
Let's try to figure out who is a no-show in a medical center.
I am trying to find out if a patient will showup to an appointment in Vitoria, Brazil. Vitoria being a city of almost 2 million people (Greater Vitoria) on the Atlantic Coast of Brazil.
I would like to show my gratitude to those that make this data available for all of us to practice and learn. This dataset and its goal got my interest from the beguinning.

All the information is obtained from a competition launcehd in Kaggle where you can finnd two sets of data.

The FIRST ONE and MORE RECENT includes over 110k appointments that took palce between late April of 2016 and early June of 2016. This set includes some extra features that are not contained in the set launched before.
The SECOND ONE and OLDEST ONE consists on 300k appointments during 2014 and 2015.
 
 I also obtained weather data from the airport of Vitoria that I will add to this project

This is the POA:

1. Collect data. I have two sources: Kaggle with the already mentioned 110k plus 300k rows and the weather for the same period that I obtained scraping the web. Once done, I combined both datasets to obtained oa final one with the weather info for everyday.
2. EDA. This phase includes the common tasks during featuring engineering: getting rid of nuls (none), dummies, outliers, errors and creation of new features. Interesting part
3. Design and application of the model. I tried most of the classifiers available to me just for fun. I selected 2 of them as a finallist: Neural Networks(Keras) and Gradient Boost Classifiero. 
4. Tunning and tweaking the model. I tried SMOTE, PCA and gridsearch through hyperparameters to try to improve my score.
4. Analysis and exposition of the results. THe metrics are accuracy and the False Positive Rate

With no more delay, I am proceeding. I will publish my notebooks following the same order than my POA. the titles of my notebooks should be self-explanatory but I will also numbered them just in case.
