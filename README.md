# IH_MIDTERM: Home price prediction using linear regression modeling

## Project Goal
---
Predict housing price using linear regression

## Data 
---

* Observations = 21,613
* Variables = 21
* Years = 2014-2015

| Variable      | Description |
| ----------- | ----------- |
| id  | 	Identification |
| date |	Date sold |
| price |	Sale price |
|bedrooms |	Number of bedrooms|
|bathrooms |	Number of bathrooms|
|sqft_liv |	Size of living area in square feet|
| sqft_lot | Size of the lot in square feet |
| floors | 	Number of floors |
| waterfront 	|‘1’ if the property has a waterfront, ‘0’ if not|
|view |	An index from 0 to 4 of how good the view of the property |
| condition | 	Condition of the house, ranked from 1 to 5|
| grade 	| Classification by construction quality. Buildings of better quality (higher grade) cost more to build per unit of measure and command higher value. |
|sqft_above | 	Square feet above ground |
| sqft_basmt | 	Square feet below ground |
| yr_built | 	Year built |
| yr_renov | 	Year renovated. ‘0’ if never renovated |
| zipcode |	5 digit zip code |
| lat |	Latitude |
| long |	Longitude |
| squft_liv15 |	Average size of interior housing living space for the closest 15 houses, in square feet |
| squft_lot15 |	Average size of land lots for the closest 15 houses, in square feet |
| Shape_leng |	Polygon length in meters |
| Shape_Area |	Polygon area in meters |


[Source Center for Spatial Data Science](https://geodacenter.github.io/data-and-lab/KingCounty-HouseSales2015/) 

## Procedure
* Cleaning 
- [ ] Check the data types of columns, fixing incorrect ones
- [ ] Filtering null values and zeros. 
- [ ] Removing duplicates
- [ ] Removing outliers
- [ ] Checking multicolinearity
* EDA 
- [ ] Check distribution of numerical variables
- [ ] Generate heat maps
- [ ] Box plots (filtering outliers)
- [ ] Data description (statistics for mean, stdev etc)
- [ ] Drop features that are correlated 
- [ ] Price vs. longitude and latitude
* Modeling 
- [ ] Split data into numerical and categorical columns
- [ ] Identify target variable and test and train data
- [ ] Transform the data when necessary (etc log transform)
- [ ] Build X,y regression model 
- [ ] Analyse results (R2, mse, etc)
