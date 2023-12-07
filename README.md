# Netflix TV Shows & Movies Analysis


## Introduction
This Python data analysis project focuses on exploring and understanding a Netflix dataset containing information about TV shows and movies available on Netflix until 2021. The dataset was obtained from Flixable, a third-party Netflix search engine, and is freely accessible on Kaggle. The primary goal of this analysis is to gain insights into the content available on Netflix, such as the distribution of shows and movies across different categories, release years, and countries.

## Dataset Overview
The dataset comprises 7789 rows and 11 columns, covering aspects like show ID, category (TV show or movie), title, director, cast, country, release date, rating, duration, type, and description. Basic information about the dataset, including the first and last few rows, its shape, size, column names, and data types, is obtained using Pandas functions like `head()`, `tail()`, `shape`, `size`, `columns`, `dtypes`, and `info()`.

## Data Cleaning and Exploration
The initial steps involve checking for duplicate records and handling missing values. Duplicate records are identified using the `duplicated()` function, and any duplicates are removed with the `drop_duplicates()` method. The presence of null values is explored using `isnull()`, and a seaborn heatmap is utilized to visualize the distribution of missing values.

## Key Analysis Tasks
1. Determining the show ID and director for the TV show 'House of Cards.'
2. Identifying the year with the highest number of TV shows and movies released, presented using a bar graph.
3. Analyzing the distribution of movies and TV shows in the dataset, visualized with a count plot.
4. Listing all movies released in the year 2020.
5. Displaying titles of TV shows released exclusively in India.
6. Identifying the top 10 directors with the highest number of contributions to Netflix.
7. Retrieving records for movies or shows categorized as "Comedies" or released in the United Kingdom.
8. Counting instances where Tom Cruise was cast.
9. Exploring unique ratings defined by Netflix, and finding the number of 'TV-14' rated movies in Canada.
10. Determining the maximum duration of a movie or show on Netflix.
11. Identifying the country with the highest number of TV shows.
12. Sorting the dataset based on the release year in descending order.
13. Extracting instances where the category is 'Movie' and the type is 'Dramas,' or the category is 'TV Show' and the type is 'Kids TV.'

This analysis provides a comprehensive understanding of Netflix content, enabling insights into trends, preferences, and patterns within the available dataset.
