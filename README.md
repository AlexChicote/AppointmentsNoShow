# AppointmentsNoShow
Let's try to figure out who is a no-show in a medical center.
I am trying to find out if a patient will showup to an appointment in Vitoria, Brazil. Vitoria being a city of almost 2 million people (Greater Vitoria) on the Atlantic Coast of Brazil.
I would like to show my gratitude to those that make this data available for all of us to practice and learn. This dataset and its goal got my interest from the beguinning.

All the information is obtained from a competition launcehd in Kaggle where you can finnd two sets of data.

The FIRST ONE and MORE RECENT includes over 110k appointments that took palce between late April of 2016 and early June of 2016. This set includes some extra fields that are not included in the first set.
The SECOND ONE and OLDEST ONE consists on 300k appointments during 2014 and 2015.
 
 I also obtained weather data from ghe airport of Vitoria that I will add to this project

This is the POA:

1. Collect data. I have two sources: Kaggle with the already mentioned 110k rows and the weather for the smae period that I obtained scraping the web. I am applied the same criteria for the second set of data. There is a process of combining and merging dataframes.
2. EDA. This phase includes the common tasks during featuring engineering: getting rid of nuls, dummies, outliers, errors and creation of new features.
3. Desing and application of the model. I am open to all classifiers but I am actually pretty curios to see how XGBoost works. I will develop one model for the 2016 set and then will try to find out another one for 2014-2015 in case the key features are the ones that are not present in the second one.
4. Analysis and exposition of the results.

With no more delay, I am proceeding. I will publish my notebooks following the same order than my POA. the titles of my notebooks should be self-explanatory.
