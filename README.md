# netflix-dataset-cleaning
Dataset cleaning and preprocessing of Netflix dataset using Python

This project is part of my Data Analyst Internship and focuses on cleaning and preprocessing the Netflix Movies and TV Shows dataset using Python and Pandas.
# Dataset
Source: [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
File: `Netflix_movies_and_tv_shows_clustering.csv`
#Tools Used
Python
#Libraries used
pandas
NumPy
Done in: Jupyter Notebook

Steps for cleaning:

Renamed all columns to lowercase and used underscores for consistency
Removed duplicate records
Filled missing values in:
 `director`, `cast`, and `country` with placeholders
 `rating` with the most frequent value (mode)
 `date_added` with 'Unknown' and converted to proper datetime format
 Standardized text formats for `type` and `rating` columns
 Saved cleaned data to a new CSV file
 #Files in this Repository

- Netflix_movies_and_tv_shows_clustering.csv – Raw dataset
- TASK_01.ipynb – Jupyter Notebook with all cleaning steps
- netflix_cleaned.csv – Final cleaned dataset
- README.md – Project overview and summary

 
