# BMW Worldwide Sales Records (2010–2024) – Data Analysis & Visualization
This project explores BMW vehicle sales data from 2010 to 2024, providing insights into pricing trends, fuel types, regional performance, and overall market dynamics.
It was developed using Python in Google Colab, leveraging Pandas, Seaborn, Matplotlib, and Plotly for data cleaning, analysis, and visualization.

# Overview
The dataset contains worldwide BMW sales records from 2010–2024, covering various features such as model, region, color, fuel type, engine size, transmission, mileage, and sales volume.
The analysis focuses on understanding how vehicle attributes influence price and sales performance over time and across regions.

# Objectives
Perform data cleaning and preprocessing for accurate analysis
Explore trends in BMW pricing and sales volume over the years
Analyze the influence of fuel type and engine size on pricing
Compare regional sales performance across global markets
Create visual and interactive charts to highlight key insights

# Dataset Description
Column	Description
Model	BMW car model name
Year	Manufacturing or sales year (2010–2024)
Region	Global region of sale
Color	Exterior color of the vehicle
Fuel_Type	Fuel category – Petrol, Diesel, Hybrid, Electric
Transmission	Manual or Automatic
Engine_Size_L	Engine capacity in liters
Mileage_KM	Distance driven (km)
Price_USD	Price of the vehicle in USD
Sales_Volume	Total units sold
Sales_Classification	Categorized sales performance (High, Medium, Low)

# Tools & Libraries Used
Python 3
Pandas & NumPy – Data preprocessing and manipulation
Matplotlib & Seaborn – Static data visualizations
Plotly – Interactive charts
ipywidgets – Interactive filters (region & year)
Google Colab – Development environment

# Project Workflow
Setup & Library Imports
Initialize all required Python libraries in Google Colab.
Data Loading
Import the BMW dataset using Pandas.
Data Preprocessing
Handle missing values, format data types, and remove duplicates.
Exploratory Data Analysis (EDA)
Statistical summary
Price and fuel-type distributions
Regional and yearly trend analysis
Visualization
Seaborn plots for static insights
Plotly charts for interactive exploration
Insights & Reporting
Identify best-selling year, region, and model trends
Export cleaned dataset

# Key Insights
Petrol vehicles dominate overall sales globally.
Automatic transmission became standard after 2015.
The Asia-Pacific region leads in BMW sales volume.
Electric models saw price surges post-2020.
Higher mileage directly correlates with lower resale value.

# Output
BMW_Cleaned_Data.csv – processed and cleaned dataset
Visual reports and insights displayed in Colab notebook
Interactive charts for region/year exploration

# Future Enhancements
Add predictive modeling to forecast BMW sales and prices.
Build Power BI or Tableau dashboard for advanced visualization.
Integrate machine learning insights for market prediction.
