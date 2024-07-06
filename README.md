# House Price Prediction

## Project Overview

This project aims to predict house prices using various features such as the number of bedrooms, square footage, location, and more. The project uses linear regression and gradient boosting regression to create predictive models. The dataset used is `house_price_data.csv`.

## Dataset

The dataset `house_price_data.csv` contains the following columns:

- `id`: Unique identifier for each house
- `date`: Date the house was sold
- `price`: Sale price of the house
- `bedrooms`: Number of bedrooms
- `bathrooms`: Number of bathrooms
- `sqft_living`: Square footage of the living space
- `sqft_lot`: Square footage of the lot
- `floors`: Number of floors
- `waterfront`: Whether the house has a waterfront view
- `view`: Number of times the house has been viewed
- `condition`: Condition of the house
- `grade`: Overall grade given to the housing unit
- `sqft_above`: Square footage of the house excluding basement
- `sqft_basement`: Square footage of the basement
- `yr_built`: Year the house was built
- `yr_renovated`: Year the house was renovated
- `zipcode`: Zip code of the house
- `lat`: Latitude coordinate
- `long`: Longitude coordinate
- `sqft_living15`: Square footage of the living space in 2015
- `sqft_lot15`: Square footage of the lot in 2015

## Installation

To run this project, you need Python 3.x and the following Python libraries:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
