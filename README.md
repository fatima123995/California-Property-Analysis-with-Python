# California Property Analysis with Python

This project explores and analyzes California property data using Python. The goal is to clean, process, and visualize the dataset to gain insights into property prices, features, and trends across the state.

## Project Overview
The project focuses on understanding single-family property data, performing data preprocessing, exploratory data analysis (EDA), and generating visualizations to highlight key patterns. It demonstrates practical Python skills in data manipulation, analysis, and visualization.

## Dataset
- **Source:** Single-family property dataset  
- **Records:** 9,582  
- **Features include:** Price, area (sqft), bedrooms, bathrooms, year built, property type, and property descriptions.

## Data Cleaning & Preprocessing
The dataset underwent a structured cleaning process in Python to ensure accurate analysis:

1. **Handling Missing Values**  
   - Removed rows with critical missing data such as price or area  
   - Filled non-critical missing values with median or mode where appropriate  

2. **Data Type Conversion**  
   - Converted price, area, bedrooms, bathrooms, and year built to numeric types  
   - Standardized categorical columns like property type  

3. **Removing Duplicates**  
   - Identified and removed duplicate entries to avoid skewed analysis  

4. **Outlier Detection & Correction**  
   - Visualized distributions using boxplots and histograms  
   - Filtered extreme values in price and area to focus on realistic property listings  

5. **Feature Engineering**  
   - Created additional columns such as price per square foot  
   - Extracted key information from property descriptions  

6. **Data Formatting**  
   - Standardized text formatting in categorical columns  
   - Removed unnecessary whitespace and special characters  

This preprocessing ensured the dataset was clean, consistent, and ready for analysis.

## Exploratory Data Analysis (EDA)
- Studied price distributions and trends  
- Investigated relationships between property features and pricing  
- Compared properties by bedrooms, bathrooms, and area  
- Created correlation matrices to identify key drivers of property value  

## Visualizations
- Histograms, boxplots, and scatter plots for numeric insights  
- Correlation heatmaps to show feature interactions  
- Graphs highlighting property trends across different regions  

## Technologies & Libraries
- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

