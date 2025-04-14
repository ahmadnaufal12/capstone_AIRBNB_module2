# Overview

This repository contains an analysis of Airbnb listings in Bangkok, Thailand. The project explores various aspects of the dataset, including data understanding, cleaning, and visualization to uncover insights about pricing, neighborhood trends, and property types.

# Dataset

The dataset used in this analysis is Airbnb Listings Bangkok.csv, which contains information about Airbnb properties in Bangkok. Key features include:

Property details (name, ID, host information)
Location data (neighborhood, latitude, longitude)
Pricing and availability
Room types and minimum stay requirements
Review statistics
Key Findings

# Data Quality Issues:
Missing values in columns like name, host_name, last_review, and reviews_per_month
Anomalies in pricing (some listings show 0 price while others show extremely high values)
Unusual values in minimum_nights (up to 1125 nights)
Descriptive Statistics:
Average price: ~3,217 THB
Most common room type: "Entire home/apt" (8,912 listings)
Most popular neighborhood: "Vadhana" (2,153 listings)
Visualizations:
Distribution plots for numeric variables
Analysis of price distribution and outliers
Examination of review patterns and availability
Notebook Structure

# The analysis is conducted in the Jupyter notebook AirBNB.ipynb which includes:

Data Loading: Importing necessary libraries and loading the dataset
Data Understanding:
Initial exploration with head(), tail(), and info()
Descriptive statistics
Identification of unique values
Data Cleaning:
Handling missing values
Addressing outliers and anomalies
Visual Analysis:
Distribution plots for numeric variables
Examination of categorical variables
Insights and Conclusions
Requirements

# To run this notebook, you'll need:

Python 3.x
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Usage

# Clone this repository
Install required packages: pip install -r requirements.txt
Open and run AirBNB.ipynb in Jupyter Notebook
Future Work

Potential areas for further analysis:

Correlation between price and location/amenities
Seasonal trends in pricing and availability
Comparison with other cities' Airbnb markets
Predictive modeling for pricing
Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or additional analyses.
