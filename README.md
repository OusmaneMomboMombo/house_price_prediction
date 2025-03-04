# House Price Prediction

This repository contains a project for predicting house prices using a regression model based on various features.

## Data Source
The dataset used in this project is from Kaggle: [KC House Data](https://www.kaggle.com/datasets/shivachandel/kc-house-data). It is stored in the `kc_house_data.csv` file and contains the following columns:

- `id`: Unique ID for each house.
- `date`: Date of the house sale.
- `price`: Sale price of the house.
- `bedrooms`: Number of bedrooms.
- `bathrooms`: Number of bathrooms.
- `sqft_living`: Square footage of the living area.
- `sqft_lot`: Square footage of the lot.
- `floors`: Number of floors.
- `waterfront`: Whether the house has a waterfront view (1 = Yes, 0 = No).
- `view`: Quality of the view from the house.
- `condition`: Condition rating of the house.
- `grade`: Overall grade given to the housing unit.
- `sqft_above`: Square footage of the house excluding basement.
- `sqft_basement`: Square footage of the basement.
- `yr_built`: Year the house was built.
- `yr_renovated`: Year the house was renovated (if applicable).
- `zipcode`: Postal code of the house location.
- `lat`: Latitude coordinate.
- `long`: Longitude coordinate.

## Project Description
This project utilizes machine learning techniques to predict house prices based on the given dataset. The model is implemented in a Jupyter Notebook using regression algorithms.

## Usage
Make sure you have Python installed on your system.

1. Clone this repository.
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open and run the `Regression_Model.ipynb` notebook to train and evaluate the model.

## Code
The project implements regression models to predict house prices based on historical data and various features.

## Requirements.txt
This project uses:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

## Author
Ousmane MOMBO MOMBO

## Contributing
Feel free to fork this repository and contribute by submitting pull requests.