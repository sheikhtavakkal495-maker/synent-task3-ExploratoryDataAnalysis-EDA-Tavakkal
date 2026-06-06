# synent-task3-eda-yourname

## Problem Statement

Netflix has a large catalog of movies and shows and it is not immediately obvious what kind of content dominates the platform, which countries produce the most, or how the catalog has grown over time. The aim was to explore the dataset and pull out meaningful patterns from it.

## Dataset Details

- Dataset: Netflix Movies and TV Shows Dataset
- Source: Kaggle
- Contains titles, type (movie or show), country, release year, rating, duration, and genre information up to mid-2021.
- Format: CSV

## Approach

After loading the data I handled missing values in columns like director, cast, and country by filling them with unknown or dropping rows where needed. I then looked at the split between movies and TV shows, the distribution of content ratings, and which countries appear most frequently. I also converted the date added column to datetime and analyzed how many titles were added each year. For genres I split the listed_in column since most titles had multiple genres and counted the most common ones.

## Results

- Movies make up around 70 percent of the catalog
- The US, India, and UK are the top three content-producing countries
- Content additions grew steadily and peaked around 2019 to 2020
- Dramas and international movies are the most common genres on the platform
