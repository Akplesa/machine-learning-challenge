# Machine Learning Challenge 

the purpose of this exercise is to create machine learning models capable of classifying candidate exoplanets from the raw dataset.

Background
"The Kepler Space Observatory is a NASA-build satellite that was launched in 2009. The telescope is dedicated to searching for exoplanets in star systems besides our own, with the ultimate goal of possibly finding other habitable planets besides our own. The original mission ended in 2013 due to mechanical failures, but the telescope has nevertheless been functional since 2014 on a "K2" extended mission.

Kepler had verified 1284 new exoplanets as of May 2016. As of October 2017 there are over 3000 confirmed exoplanets total (using all detection methods, including ground-based ones). The telescope is still active and continues to collect new data on its extended mission." 
Background SOURCE: https://www.kaggle.com/nasa/kepler-exoplanet-search-results


## Model 1 - K nearest neighbors
My first model used the K nearest neighbor algorithm. 
This algorithim finds the distances between a query and all of the data examples. It selects the specified number examples "K" closest to the query and votes for the most frequent labels or averages the labels.

