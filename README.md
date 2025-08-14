Netflix Content Analysis
Overview

This project analyzes Netflix’s content catalog by cleaning, transforming, and visualizing data from a CSV file. The workflow ensures high-quality, standardized data for efficient analysis and includes a custom popularity classification based on user votes.

Features
Data Cleaning
  Detects and removes duplicate records.
  Handles missing (NULL) values appropriately.
  Standardizes inconsistent formats (e.g., converting dates to a single standard format).

Data Transformation
  Extracts only the fields necessary for analysis to reduce processing overhead.
  Converts date columns into a standard YYYY-MM-DD datetime format.
  Categorizes “Vote” counts into:
    Popular
    Average
    Below Average
    Not Popular

Visualization
  Generates a plot showing the distribution of Netflix content by genre.

Data

The dataset contains information about Netflix titles, including:
Title
Popularity
Vote count
Genre
Release Date

Other metadata


Results
Genre Distribution Plot

From the visualization, we can observe that certain genres (e.g., Dramas, Comedies, Thriller) dominate the Netflix library, while others appear less frequently.
