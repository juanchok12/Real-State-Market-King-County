# Seattle Real Estate Market Analysis

## Overview
This project is a comprehensive analysis of the real estate market in Seattle. Using a Jupyter Notebook, we explore various trends, pricing factors, and the impact of economic indicators on the housing market.

## Objectives
- To identify patterns and trends in the real estate prices in Seattle.
- To analyze the relationship between housing features and market prices.
- To provide insights into the best times to buy or sell properties.

## Data
The analysis is conducted using a dataset that includes information on housing features, sale prices, and dates of transactions. The dataset contains the following key columns:
- `Price`: Sale price of the home
- `Date`: Date of the sale
- `Bedrooms`: Number of bedrooms
- `Bathrooms`: Number of bathrooms
- `Sqft_Living`: Square footage of the living space
- `Sqft_Lot`: Square footage of the lot
- `Floors`: Number of floors
- `Waterfront`: Whether the home is on the waterfront
- `View`: Quality of the view from the home
- `Condition`: Overall condition of the home
- `Grade`: Overall grade given to the housing unit
- `Sqft_Above`: Square footage of the house apart from the basement
- `Sqft_Basement`: Square footage of the basement
- `Year_Built`: Year when the house was built
- `Year_Renovated`: Year when the house was renovated
- `Zipcode`: Zip code area
- `Lat`: Latitude coordinate
- `Long`: Longitude coordinate

## Methodology
The notebook starts with data cleaning and preprocessing, followed by exploratory data analysis (EDA) to understand the distribution and relationship of variables. We use visualizations to support our analysis and employ statistical methods to draw conclusions.

## Tools Used
- **Jupyter Notebook**: For interactive data analysis and visualization.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib/Seaborn**: For creating static, interactive, and informative visualizations.

## How to Run the Project
To run this analysis, you will need to have Python installed along with the necessary libraries. Clone the repository and launch Jupyter Notebook to view and interact with the analysis:

## Main Findings:

Assuming all other factors remain constant, this function means that the house price in King County increases by approximately $268.47 per each additional square foot of space above the ground level. The relationship between home price and above square footage can be modeled by the following function:

_f(x)=268.47x+59953.19_
![afb46a0c-425d-467e-b49c-0d3c8bae3963](https://github.com/juanchok12/Real-State-Market-King-County/assets/116334702/f46e7232-a761-43c8-aaec-ca93fdb02b22)

R^2=49.29% suggests that the variability in the house prices can be explained by the square footage of the home (independent varaible 'sqft_living'). In other words, the squre footage of the living space accounts for nearly half of the observed varaition in house prices. 

