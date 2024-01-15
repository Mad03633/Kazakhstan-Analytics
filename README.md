# Data Analysis and Visualization Script

## Overview
This Python script utilizes the Pandas and Matplotlib libraries to analyze and visualize data from an Excel file. The script performs various data manipulations, filters, and creates different types of plots.

## Usage
1. Install the required libraries:
   ```
   pip install pandas matplotlib
   ```
2. Place your data file (Data.xlsx) in the same directory as the script.

## Contents
1. Data Loading and Filtering:
- Reads data from 'Data.xlsx'.
- Filters data for the Kazakh SSR and Kazakhstan.

2. Histogram:
- Displays a histogram for the 'Count_Person' column.

3. Line Plot:
- Displays a line plot for the 'Count_Person_Is_Internet_User_PerCapita' column over the years.

4. Hex Bin Plot:
- Displays a hex bin plot for 'Life_Expectancy_Person' against 'Year'.

5. Saving Filtered Data:
- Saves filtered data (life expectancy >= 72 and country is Kazakhstan) to a new Excel file.

# Requirements

- Python 3.x
- Pandas
- Matplotlib

Feel free to modify the script as needed for your specific data and analysis requirements