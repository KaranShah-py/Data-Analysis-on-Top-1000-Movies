# The following project is contributed by Karan Shah
Please Follow me on Linkedin :- https://www.linkedin.com/in/karan-shah2001/
Data Analysis On Top 1000 Movies Datasets.

About this Project :-
Note :- If you are looking to refer this project you need to have knowledge about :-
          1) Data Analytics
          2) Python Programming 
          3) Statistics
          4) Problem Solving

        Modules Used are :-
          1) Pandas 
          2) Numpy
          3) Matplotlib.pyplot 
          4) seaborn
          5) scipy
          6) collections

You need to download the dataset and upload in your google collab too.
Dataset Link :- https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows?resource=download


This is an Data Analytics Project using a predefined dataset from the internet.
In this project you will come across everything which is involved in any data science
project that is from Data collection to data analyzing stage.
Stages of the project are :-
  1) Data Collection Stage
      In this stage the given dataset is loaded in the program.

  2) Data Exploration.
      In this stage the loaded dataset is explored in detail that is 
      total number of data we have. What are the attributes present in the dataset.
      What are the datatypes of each and every attribute.

  3) Data Cleaning Stage
      After the data exploration stage it was concluded that there were 1000 rows and 16 attributes present 
      that is we had a data of 1000 movies.
      But, before starting any analytics we had to look if all the 1000 rows are filled with data or not.
      That is if there are any null values/wrong values present then we need to adjust it.
      After checking i found that there were 286 Null values present in the given dataset, so i decided to drop all the 
      rows which as the null values. 
      Also attributes "Poster Link" and "Overview" Were droped from the dataset.
      So, we were left with 714 rows and 16 attributes.

  4) Data Transformation Stage 
      In this stage many required changes were made in the dataset such as converting the 'Runtime' and 'Gross' Attribute 
      datatype from Str to int.
      Added a new column in the dataset 'Decade' which categorically divided all the movies in with respect in the decade 
      released.
    
  5) Data Analysis Stage 
      Finally, started with the data analysis stage which was first finding the questions about 
      What we want to analyze from the dataset or what are the questions or insights we are looking for.
      Questions Analyzed :-
      1. Decade wise change in IMDB Ratings.//
      2. IMDB rating and Gross collection (DECADE WISE)//
      3. Does Number of votes affect the Meta_score.
      4.a Number of Single and Multi Genre movies with respect to decades.//
      4.b Single Genre Movies vs Multi Genre Movies gross collection//
      4.c Display the number of movies made and it's the Genre count w.r.t IMDB Ratings.//
      5. How many movies are being made in a decade?
      6. Display the number of movies that exceed 2hrs of runtime
      7. The rise and fall of the number of votes in a decade
      9. Does the runtime of any film affect the number of votes.
      10. Analysis of Runtime and Gross w.r.t the Top 10 lengthy and shortest movies
      11. Display the Name of the least and most popular movie
      12. Classifying the ratings into their respective categories: Good, Very Good, Excellent
      13. Display the number of movies in each certificate rating
      14. The movies with most number of IMDB ratings w.r.t it's certification.
      15. Display the Top 10 actors who have appeared in most number of films
      16. Which is the most popular Genre?
      17. Votes to collection correlation
      
      From the above questions graphs, plots, diagrams were made and conclusions were concluded.



