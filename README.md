## Prediction_of_Obesity_Levels
## Description
### Context

Dataset for estimation of obesity levels based on eating habits and physical condition in individuals from Colombia, Peru and Mexico

### Null hypothesis: 
There is no relationship between obesity levels and physical condition including eating habits

Explore the data for trends in the data to predict obesity levels or find any clear indications of relationships between the predictors.

### Content
The dataset contains data for the estimation of obesity levels in people from the countries of Mexico, Peru and Colombia, with ages between 14 and 61 and diverse eating habits and physical condition as mentioned by [1], data was collected using a web platform with a survey (see Table 1 in the attached paper) where anonymous users answered each question, then the information was processed obtaining 17 attributes and 2111 records, after a balancing process.

The attributes related with eating habits are: 
1. Frequent consumption of high caloric food (FAVC) 
2. Frequency of consumption of vegetables (FCVC)
3. Number of main meals (NCP), Consumption of food between meals (CAEC)
4. Consumption of water daily (CH20), and Consumption of alcohol (CALC). 
The attributes related with the physical condition are: 
5. Calories consumption monitoring (SCC) 
6. Physical activity frequency (FAF) 
7. Time using technology devices (TUE)
8. Transportation used (MTRANS)
other variables obtained were: 
9. Gender, Age, Height and Weight.

Finally, all data was labeled and the class variable NObesity was created with the values of: Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II and Obesity Type III, based on Equation  and information from WHO and Mexican Normativity. 

The data contains numerical data and continous data, so it can be used for analysis based on algorithms of classification, prediction, segmentation and association. 
See paper here: https://www.sciencedirect.com/science/article/pii/S2352340919306985?via%3Dihub
Data is available in CSV format and ARFF format to be used with the Weka tool..

