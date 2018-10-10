# MicrosoftChallenge
Among all the disasters that occur in India, floods and droughts are the most commonly occurring natural disasters due to the irregularities of the Indian monsoon. About 75% of the annual rainfall in India is concentrated in 3-4 months of the monsoon season. As a result, there is very heavy discharge from rivers during the period causing widespread floods. So it is important to monitor rainfall in particular areas so we can predict the such disaster and prevent damages.
So in this project we are going to predict flood and drought in selected area using ML algorithm (SVM, Logistic regression, Random forest etc) with following data -
1.	Location and altitude of selected area
2.	Location and Altitude of neighbor area
3.	Rainfall in selected area
4.	Rainfall in neighbor area
5.	Past flood record of area
6.	Past drought record of area
7.	Temperature 

We have collected above data for different days from weather forecasting websites, Kaggle and different data source for Indian cities. We are going to check for any interaction effect between rainfall, temperature and location, so that we can generate new features. We will also consider sequencing effect of above feature with days.
Neighbor area is also considered because high rainfall in that area may cause flood in selected area.  By using location coordinates and altitude we can geometrically analyze the flow of water during heavy rainfall. There is other parameter also present like urbanization which creating concrete structure so not letting water to go to ground.  
By using this data, we can cluster different regions as flooded or drought area so this can help for water transportation from flooded to drought area which may solve many issues.
Other than these features we are trying to collect for following dataset
1.	Wind speed
2.	Dam water level 
3.	Atmospheric Pressure
4.	Accelerometer readings from attached sensor to dam wall (we are trying to implement this).


