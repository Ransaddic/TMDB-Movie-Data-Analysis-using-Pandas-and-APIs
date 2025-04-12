# TMDB Data Analysis Project

## Overview
This repository contains a comprehensive analysis of movie data from The Movie Database (TMDB). The analysis explores various aspects of the film industry including financial performance, audience reception, genre trends, and production factors that contribute to a movie's success.

## Introduction
The film industry generates billions in revenue annually and understanding the factors that contribute to a movie's success is valuable for studios, investors, and content creators. This project analyzes TMDB data to identify patterns and insights that can inform strategic decisions in movie production and marketing.

## Project Objectives
- API Data Extraction: Fetch movie data from a movie database API.
- Data Cleaning & Transformation: Process and structure the data for analysis.
- Exploratory Data Analysis (EDA): Perform an initial exploration to understand trends.
- Advanced Filtering & Ranking: Identify the best and worst movies based on financial
and popularity metrics.
- Franchise & Director Analysis: Assess how franchises and directors perform over time.
- Visualization & Insights: Present key findings using visualizations

## Dataset
The analysis uses the TMDB dataset, which includes:
- Movie metadata (title, release year, runtime, etc.)
- Financial information (budget, revenue)
- Audience metrics (popularity, vote average, vote count)
- Production details (production companies, countries)
- Creative elements (cast, crew, genres) etc.

### Data Source
Data was collected from [The Movie Database API](https://developers.themoviedb.org/3/getting-started/introduction) using the TMDB API collecting movies with only id: [0, 299534, 19995, 140607, 299536, 597, 135397,420818, 24428, 168259, 99861, 284054, 12445,181808, 330457, 351286, 109445, 321612, 260513]


## Installation

# Install dependencies

```
pip install -r requirements.txt
```

## Project Structure
```

tmdb-data-analysis/
│
├── data/                      # Data directory
│   ├── clean_df.csv           # Cleaned and processed data
│   ├── extracted_df.csv       # data extracted using the API1
│   └── extracted_df1.csv      # data extracted using the API2
│
├── notebooks/                 # Jupyter notebooks
│   ├── data_collection.ipynb  # API data collection
│   ├── data_cleaning.ipynb    # Data preprocessing
│   ├── data_analysis.ipynb    # Data analysis and visualisation
│
│
├── requirements.txt           # Project dependencies
├── README.md                  # Project description
```


## Key Findings
### Best & Worst Performing Movies
1. Highest bugdeted movie is Avengers: Age of Ultron
2. Movie with the highest revenue is Avatar
3. Movie with the highest profit and ROI is Avatar
4. Movie with lowest profit and ROI is Avengers: Age of Ultron
5. The most popular movie is Avengers
6. Movie with the highest ratings is Avengers: Endgame


### Franchise vs. Standalone Movie Performance
1. Standalone movies have the highest average revenue, the highest median ROI and the high average popularity
2. Franchise movies have the highest average budget

### Most sucessful Franchise And Directors
1. The Franchise with the most number of movies is the Avengers Collection
2. The Franchise with the highest average and total budget is the Avengers Collection
3. The Franchise with the highest total and average revenue is the Avengers and the Avatar collection respectiveky
4. The Franchise with the highest average ratings is the Harry Potter collections
5. Diretors with highest number of movies are James Cameron, Joss Whedon, Anthony Russo, Joe Russo, Chris Buck, Jennifer Lee
6. The most sucessful director based on total revenue is James Cameron
7. The most succesful directors based on the average ratings are Joe Russo, Anthony Russo

