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
1. What is the most expensive app on the Play Store?
2. Which genre has the highest number of apps?
3. What is the average size of free vs. paid apps?
4. What are the top 5 most expensive apps with a perfect rating (5)?
5. How many apps have received more than 50K reviews?
6. What is the average price of apps, grouped by genre and number of installs?
7. How many apps have a rating higher than 4.7, and what is their average price?
8. What is Google's estimated revenue from apps with 5,000,000+ installs?
   (Assuming Google takes a 30% cut from app sales)
9. What are the maximum and minimum sizes of free vs. paid apps?
10. Is there a correlation between an app’s rating, number of reviews, size, and its price?
11. How many apps exist for each type (free/paid) across different content ratings?
12. How many apps are compatible with Android version 4.x?
   
## Visualizations:
- Histograms and box plots for numerical columns like Rating, Size, and Price.
- Bar charts for categorical columns like Category and Content Rating.
  
> Here are some of the visualizations generated during preprocessing:

- Rating Distribution: Histogram showing the cleaned app ratings.
- App Sizes: Box plot displaying the distribution of app sizes.
- Content Ratings: Bar chart visualizing the count of apps by age group.
