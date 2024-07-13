# Investigating-Netflix-Movies
Description:

This project aims to investigate whether the average duration of movies on Netflix has been declining over the years. Using a dataset containing various details about Netflix shows, including movies, we perform exploratory data analysis (EDA) to examine movie lengths and identify any trends.

Dataset:

Filename: netflix_data.csv
Columns:
show_id: The ID of the show
type: Type of show (Movie or TV Show)
title: Title of the show
director: Director of the show
cast: Cast of the show
country: Country of origin
date_added: Date added to Netflix
release_year: Year of Netflix release
duration: Duration of the show in minutes
description: Description of the show
genre: Show genre
Project Steps:

Data Loading: Read the dataset using pandas.
Data Subsetting: Filter the data to include only movies.
Data Cleaning: Select relevant columns for analysis.
Duration Analysis: Filter and analyze movies with a duration of less than 60 minutes.
Genre-Based Coloring: Assign colors to different movie genres for visualization.
Visualization: Create a scatter plot to visualize the duration of movies by their release year.
Conclusion: Assess whether movie durations are actually getting shorter.
Key Findings:

We plot the movie durations over the years and color-code them based on their genre.
Initial observations suggest that movie durations have not been consistently declining.
Technologies Used:

Python
Pandas
Matplotlib
How to Use:



Conclusion:
The analysis shows no definitive trend of decreasing movie lengths. Various factors, such as genre and production choices, could influence the durations observed. Further analysis with more sophisticated statistical methods could provide deeper insights.
