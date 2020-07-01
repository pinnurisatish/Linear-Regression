# Linear-Regression
This repository contains linear regression models

# Linear Regression - House Price Prediction 
## Objective
We will be working on a dataset that has sales prices of houses in King County. As a data scientist, you are given a responsibility to create a machine learning model that would predict the sales price for each house in future based on certain input variables. The target variable in this dataset is 'price' and you are given a new unseen test dataset on which you will have to predict price of each house.

## Dataset
You can see the dataset here

To load the dataset in your jupyter notebook, use the below command:
```
import pandas as pd
house_data = pd.read_csv('https://raw.githubusercontent.com/dphi-official/Datasets/master/kc_house_data/kc_house_data.csv')
```
## Data Description
In this dataset the sales price of houses in King County (Seattle) are present. It includes homes sold between May 2014 and May 2015. Before doing anything we should first know about the dataset what it contains what are its features and what is the structure of data.
<ol>
<li>price: price of the house. This is our target variable.
<li>bedrooms: Number of bedrooms
<li>bathroooms: Number of bathrooms
<li>sqft_living: Square footage of house
<li>sqft_lot: Square footage of lot
<li>floors: Number of floors/ Level
<li>waterfront: 1 = Waterfront view; 0 = No waterfront view
<li>view: 1 = House been viewed; 0 = House has not been viewed
<li>condition: 1 indicates worn out property and 5 excellent
<li>grade: Overall grade given to the housing unit, based on King County grading system. 1 poor ,13 excellent
<li>sqft_above: Square footage of house apart from basement
<li>sqft_below: Square footage of the basement
<li>yr_built: Year of house built
<li>yr_renovated: Year of house renovated
<li>zipcode: Zip code
<li>lat: Latitude coordination
<li>long: Longitude coordination
<li>sqft_living15: Square footage of house in 2015 (implies-- some renovations)
<li>sqft_lot15: Square footage of lot in 2015 (implies-- some renovations)
