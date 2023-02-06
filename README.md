# King County Real Estate Analysis  

## Summary
We fit a least squares linear regression model to housing price data taken from the market in one of the most sought after counties in the 
United States, King County Washington. King County, which is named after the famous civil rights leader M.L. King, is located in the state of Washington and contains the Seatle metropolitan area.  The King County population, which lands about 2.3 million in total, includes a number of the nations richest people such as billionares Bill Gates and Jeff Bezos.  
 Due to its unique geography and reputation as a residence for the extremely wealthy, its houses push into the upper registers of price and it provides an interesting case study. 
 
The repo contains a Jupyter notebook and Tableaux workbook featuring an interactive heat map showing the spatial variations in price, several visualizations of the data,  and a model which captures about 85% of the variability in the price with respect to input features. 

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

