# Earthquake Data Analysis Project

## Overview

This project focuses on analyzing earthquake data using Python and popular data analysis libraries such as Pandas and Matplotlib.

## Tasks

### Task 1: Data Cleaning
- Columns with empty values are dropped from the dataset.

### Task 2: Categorization of Magnitude
- The 'Magnitude' field is divided into three categories: Low Magnitude, Medium Magnitude, and High Magnitude.

### Task 3: Data Reshaping
- The data is reshaped using the melt() and pivot() functions to provide insights into the relationship between earthquake coordinates and time.

### Task 4: Visualization
- Four different types of graphs are constructed: a line chart showing the magnitude over time, a bar chart displaying earthquake types, a scatter chart depicting earthquake locations, and additional visualizations based on individual preferences.

### Task 5: Date Processing
- The 'Date' column is converted to datetime format, and year and month information is extracted for further analysis.

## How to Use

1. Install the required libraries by running `pip install pandas matplotlib`.

2. Run the Python script `Quiz3&4.ipynb`.

3. The script loads the earthquake dataset, performs the specified tasks, and generates visualizations.

4. The cleaned data is saved to a new CSV file named 'cleaned_earthquake_data.csv'.