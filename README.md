# GCU_ML_PHW2
## 1. Objective Setting
We would like to show different combinations of algorithms to analyze a dataset. We will create a program structure with a single major function “AutoML” that will automatically run different combinations of the following : 
-	Data Scaling, Data Encoding
-	Various Clustering Algorithms
-	Various quality measuring tools
-	Various values of parameters and hyperparameters
-	Various subsets of the features of the dataset

We will use the California Housing Prices Dataset to test the algorithm in the end-to-end process as used in Data Science.
The function “AutoML” will be capable of getting inputs of various combinations and tell the user if the algorithm / scaler / encoder and so on is supported.
We will explain the meaning of the clustering results, in terms of the features used in clustering the dataset.
+	we will also try to combine some attributes to make a new attribute and analyze the difference in the results.

## 2. Data Curation
Dataset Name : California Housing Prices
Source : https://www.kaggle.com/datasets/camnugent/california-housing-prices 

## 3. Data Inspection
- Number of Instances: 20640
- Number of Attributes: 10
- Attribute Information: 
-------------------
1. longitude: A measure of how far west a house is; a higher value is farther west
2. latitude: A measure of how far north a house is; a higher value is farther north
3. housingMedianAge: Median age of a house within a block; a lower number is a newer building
4. totalRooms: Total number of rooms within a block
5. totalBedrooms: Total number of bedrooms within a block
6. population: Total number of people residing within a block
7. households: Total number of households, a group of people residing within a home unit, for a block
8. medianIncome: Median income for households within a block of houses (measured in tens of thousands of US Dollars)
9. medianHouseValue: Median house value for households within a block (measured in US Dollars) // do not use in clustering
10. oceanProximity: Location of the house w.r.t ocean/sea

- Missing attribute values:  207 in attribute “totalBedrooms”

## 4. ** Full code in PHW2 docx and PHW2 ipynb. **
