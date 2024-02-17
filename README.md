#      Visualizing Netflix Dataset

### Report Link :https://app.powerbi.com/links/qq-hezRtDN?ctid=77255288-5298-4ea5-81aa-a13e604c30ac&pbi_source=linkShare

## Problem Statement

Given a dataset named as “1910_m4_assign_dataset_v1.0”. Connect to the dataset and perform the following tasks for data modeling. Do an analysis of the dataset by cleaning and modifying the dataset, thus drawing relevant insights.

## Data Description

#### Credits table :

person id: Person id.

Id: Team Id while working on a movie.

Name: Name of the person.

Character: The character they have played in the movie.

Role: Their role in making a movie.

#### Title Table:

Id: Team Id while working on a movie.

Title: Movie/web series name 

Type: Movie/Web series

Release_year: The release year when the movie was released.

Age_certification: Certificate based on content allowed to watch by age.

Runtime: Total screen time of content

Genres: Movie type based on Action/Comedy/Scifi 

Production_countries: Origin of content

Seasons: The count of sequel/prequel number of any content

Imdb_id: Registered ID on IMDB website 

Imdb_score: Average rating by all users

Imdb_votes: The no of people has given their vote

Tmdb_popularity: TMDB popularity score

Tmdb_score: TMDB rating 



### Steps followed 

- Step 1 : Load the HR1910_m4_assign_dataset_v1.0 data set into Power BI Desktop, dataset is a excel file.
- Step 2 :Open the power query editor and perform the data cleaning task..
- Step 3 :Open the data model and make relationships among all tables.
- Step 4 : Create measures for “total content” and “Runtime hours” formulas using DAX:

              Total Content = COUNTROWS(titles)


              Runtime Hours = SUM(titles[runtime])/60

- step 5 : create the report in Power BI.
     - Show bar plot for most available content for top 5 genres by type.  
     - Show line chart for a count of released content by each year by their type.
     - Show line chart for a count of released content by each year by their type.
     - Show the total distribution of content types using the donut chart.
     - Create cards for the total runtime, the total count of movies and tv shows, and the average rating of IMDB.
     - Add slicer for genres, release year, and title.
     - Add the Netflix logo and a little introduction to Netflix (use text box).

# Snapshot of Dashboard (Power BI Service)

![1](https://github.com/shroukhm/Sales-Analysis-Report/assets/134003439/e82edfa1-a6a0-4a2e-860f-16af2aac2633)


 
