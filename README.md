# World Happiness Report Analysis Project

## Overview
This project analyzes the World Happiness Report dataset from 2015 to 2019, exploring factors that contribute to national happiness scores across different countries and regions.

## Dataset
The analysis uses World Happiness Report data from 2015 to 2019. The dataset includes:
- Happiness scores for different countries
- Various contributing factors like GDP, social support, etc.
- Regional classifications
- Yearly trends

Files required:
- `2015_.csv`
- `2016_.csv`
- `2017_.csv`
- `2018_.csv`
- `2019_.csv`

## Requirements

python
pandas==2.0.0
numpy==1.24.0
matplotlib==3.7.0
seaborn==0.12.0

## Project Structure
The analysis is conducted in a Jupyter notebook (`eda.ipynb`) and follows these steps:

1. **Data Loading and Preparation**
   - Import required libraries
   - Load datasets from multiple years
   - Combine datasets with year tracking

2. **Exploratory Data Analysis (EDA)**
   - Initial data exploration
   - Summary statistics
   - Missing value analysis
   - Duplicate detection

3. **Data Cleaning**
   - Handle missing values
   - Remove duplicates
   - Column renaming (if needed)
   - Outlier detection

4. **Data Analysis**
   - Statistical summaries
   - Distribution analysis
   - Correlation analysis
   - Time series analysis

5. **Visualizations**
   - Histograms of happiness scores
   - Correlation heatmaps
   - Box plots for outlier detection
   - Pair plots for variable relationships
   - Regional comparison plots

## How to Use
1. Clone this repository
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Place the CSV files in the project directory
4. Open and run `eda.ipynb` in Jupyter Notebook:
   ```bash
   jupyter notebook eda.ipynb
   ```

## Key Features
- Comprehensive data cleaning and preparation
- Detailed statistical analysis
- Multiple visualization techniques
- Regional and temporal trend analysis
- Correlation studies between happiness factors

## Results
The analysis provides insights into:
- Global happiness trends from 2015-2019
- Regional variations in happiness scores
- Key factors influencing national happiness
- Correlation between different variables
- Outlier countries and special cases

## Author
Vansh Chaturvedi

## Acknowledgments
- World Happiness Report for providing the dataset
- Contributors to the pandas, numpy, matplotlib, and seaborn libraries
