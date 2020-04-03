# Allocation-of-Information-maps-in-Moscow-based-on-Analysis-of-tourist-behavior
This project is a research carried out during Urban Analytics master program at University of Glasgow. 
It analyses data of tourist density in Moscow area recorded during the one week in April 2018 and compare its patterns with the distribution of tourists attraction and facilities.  Data of tourist attractions and facilities was extracted from OSM database ( Overpass API) and Moscow Open data Portal (API)
Next, the strongest attractors were identified by running XGBoost regressor and more relient density distribution was predicted based on them.
As soon as the tourist density prediction was obtained, kmeans algorithm was trained to find clusters in this data and propose better location for information points and map.
Undertaken analysis has shown that the possible improvement can be a 60% increase of tourist area covered by information points 
