# Ukraine Used Car Sales Analysis 
### Project Overview
This repository contains a comprehensive Exploratory Data Analysis (EDA) of over 9,500 car sales advertisements in Ukraine. By leveraging Python's data science stack, this project uncovers the factors that drive car pricing in a secondary market, focusing on mileage, engine types, and registration status.
## Dataset Description
The dataset provides a detailed snapshot of the Ukrainian automotive market with 10 key features:
- Car: Brand and Model.
- Price: Sale price in USD.
- Body: Vehicle body type (Sedan, SUV, Crossover, etc.).
- Mileage: Total distance traveled (in thousands of km).
- EngV: Engine volume.
- EngType: Fuel type (Petrol, Diesel, Gas, Other).
- Registration: Logical indicator of Ukraine-based registration.

## Key Objectives
- Data Integrity: Clean and transform raw data using Pandas to handle missing values and duplicates.
- Price Analysis: Identify how mileage and year correlate with the final asking price.
- Market Segmentation: Visualize the popularity of different body types and fuel types across the region.
- Registration Impact: Quantify the price difference between cars already registered in Ukraine vs. those that are not.
## Technical Implementation
- Wrangling: Standardized strings, handled EngV outliers, and removed redundant entries.
- Visualizations: Used Seaborn's jointplot to show the density of price vs. mileage and Matplotlib for categorical distributions.
- Correlation: Generated a Correlation Heatmap to isolate the most influential numeric features.
