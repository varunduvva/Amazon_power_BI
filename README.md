#Amazon Prime Video Content Dashboard#


This Power BI dashboard project provides an in-depth analysis of Amazon Prime’s content catalog, visualizing various attributes related to shows and movies on the platform. It offers insights into content types, genres, release years, ratings, and more, enabling data-driven exploration of Amazon Prime's content library.

Project Overview
The dashboard was created using data from the amazon_prime_titles.csv file, containing detailed metadata on Amazon Prime’s available content. Key fields include titles, type (movie or TV show), genre, country of origin, release year, rating, and other relevant attributes. The goal was to present actionable insights through interactive visualizations.

Data Source
File: amazon_prime_titles.csv
Columns:
show_id: Unique identifier for each show.
type: Type of content (Movie/TV Show).
title: Title of the content.
director and cast: Information about the creators and actors.
country: Country of origin.
release_year: Year the content was released.
rating: Age-based rating for audience suitability.
duration: Duration of the content (in minutes for movies or seasons for shows).
listed_in: Genres or categories of the content.
description: Brief synopsis of the content.
Dashboard Components
Data Model
The data model was designed to integrate and relate key fields, allowing flexible filtering and drill-down options. Data transformations were applied to clean and prepare the dataset for analysis, including handling missing values, parsing dates, and categorizing content.

Visualizations
Content Distribution by Type: Breakdown of movies vs. TV shows.
Genre Popularity: Representation of the top genres based on available content.
Release Year Trends: Visualization of content added over time to observe trends in release years.
Country Insights: Analysis of content origin by country, highlighting international content.
Audience Ratings: Distribution of content by age ratings for audience suitability.
Content Duration: Average duration of movies and seasons, providing insights into content length.
Theming and Design
The dashboard includes Amazon Prime branding elements, including color themes and the Prime Video logo, to create a visually cohesive presentation.

Usage
To view the dashboard:

Open the .pbix file in Power BI Desktop.
Interact with filters and slicers to explore various dimensions of the data, including type, genre, country, release year, and ratings.
Project Files
Amazon_shows.pbix: Power BI dashboard file.
amazon_prime_titles.csv: Source data file.
Prime_video_logo.png: Amazon Prime branding logo for the dashboard.
