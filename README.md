# Data Preprocessing Project

This project is a comprehensive data preprocessing pipeline for cleaning and analyzing the Google Play Store dataset. The steps cover handling missing values, fixing inconsistencies, addressing outliers, and visualizing the results for better insights.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Workflow](#project-workflow)
- [Visualizations](#visualizations)

## Overview
The goal of this project is to preprocess the Google Play Store dataset for meaningful insights. The tasks include:
1. Cleaning and transforming columns like Rating, Size, Price, Category, and more.
2. Handling missing values and outliers.
3. Visualizing data distributions for better understanding.

## Features
- Fixes invalid entries in columns like Rating, Size, and Price.
- Handles missing values and fills them appropriately.
- Detects and addresses outliers in numerical columns.
- Provides visualizations for each step in the pipeline.
- Uses Python libraries like Pandas, NumPy, Matplotlib, Seaborn, and Plotly.

## Requirements
Ensure you have the following installed:
- Python 3.7 or higher
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

## Installation
```bash
# Clone the repository
git clone https://github.com/MarwanAhmed2100902/Data-Preprocessing-Project.git

# Navigate to the project directory
cd Data-Preprocessing-Project
```
## Usage
```bash
# Open the Jupyter Notebook file
jupyter notebook "Data Preprocessing Project.ipynb"

# Run the cells sequentially to execute the preprocessing pipeline.
# Visualizations and insights will be displayed as part of the notebook.
```
## Project Workflow
### Analytical Questions Addressed:
1. Fix Rating: Removed outliers and filled missing values.
2. Fix Size: Unified size units and handled non-numeric values.
3. Fix Price: Converted price data to numeric format.
4. Fix Category: Validated and visualized app categories.
5. Fix Android Version: Ensured consistency and visualized version requirements.
6. Content Rating: Analyzed the target age group for apps.
   
## Visualizations:
- Histograms and box plots for numerical columns like Rating, Size, and Price.
- Bar charts for categorical columns like Category and Content Rating.
  
> Here are some of the visualizations generated during preprocessing:

- Rating Distribution: Histogram showing the cleaned app ratings.
- App Sizes: Box plot displaying the distribution of app sizes.
- Content Ratings: Bar chart visualizing the count of apps by age group.
