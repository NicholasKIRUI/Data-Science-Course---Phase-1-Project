## Part Time Data Science 07 class: Phase 1 Project
### Date of Submission: 03 June 2024

## Project Overview
For this project, I will use exploratory data analysis to generate insights for a business stakeholder based on datasets provided.

### Business Problem
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

## The Data Understanding
The data was collected from various locations and the different files have different formats. 
1. compressed CSV (comma-separated values) files:
       - bom.movie_gross
       - tn.movie_budgets
       - tmdb.movies
2. TSV (tab-separated values) files:
       - rt.movie_info.tsv
       - rt.reviews.tsv
3. Data located in a SQLite database:
    - im.db  
    - entiry relationship diagram: movie_data_erd
    - Table Names
        - movie_basics
        - directors
        - known_for
        - movie_akas
        - movie_ratings
        - persons
        - principals
        - writers

    - Most relevant tables:
        - ## Movie_basics
            - Table contains the basic information of the movies including the genres
        - ## movie_ratings
            - Table shows the ratings of the movies