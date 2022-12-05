# Comparison of Amazon and Netflix Streaming Service
Authors: Asia Paige, Hyunwoo Kim, Malar Veerappan

## Motivation

Since the beginning of COVID, video and tv streaming increased worldwide changing the streaming landscape (MarketWatch). From March 2020 to December 2021, Netflix and Amazon Prime remained in the top 10 for streaming platforms with both holding the number one and two spots respectively based on the number of global subscribers (Hersko).
From this information, we wondered which of the two streaming platforms are more popular. Since popularity of shows and services are usually analyzed based on the amount of views and subscriptions, we wanted to explore popularity of the platforms through award recognition in conjunction with ratings to explore the following questions:

Which platform has higher rated shows/movies on IMDb and Rotten Tomatoes?
Which platform has more recent shows/movies that have been nominated and/or won an Emmy or Oscar?
Is there a distinction between top platform genres, number of awards, and IMDb and Rotten Tomatoes scores?

## Data and analysis
All data files are in the subfolder /data

Dataset Name
Description
Source Info
Movies on Netflix, Prime Video, Hulu, and Disney+
Information on movies available on four major streaming platforms. 
Created by Ruchi Bhatia.

Useful Variables: ‘Netflix’, ‘Prime Video’, ‘Rotten Tomatoes, ‘Age’
Size: 9,515 rows, 11 columns (506 KB)
Source URL: https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney 
Format/Access method: CSV/Download from Kaggle
Years Covered: 1914-2021
TV Shows on Netflix, Prime Video, Hulu, and Disney+
Information on tv shows available on four major streaming platforms. Created by Ruchi Bhatia.

Useful Variables: ‘Netflix’, ‘Prime Video’, ‘IMDb’, ‘Rotten Tomatoes’, ‘Age’
Size: 5,368 rows, 12 columns (313 KB)
Source URL: https://www.kaggle.com/ruchi798/tv-shows-on-netflix-prime-video-hulu-and-disney 
Format/Access Method: CSV/Download from Kaggle
Years Covered: 1914-2021
Movies on the Academy Awards (Oscars)
Information on nominees and winners of the Academy Awards. Created by Raphael Fontes.

Useful Variables: ‘film’, ‘winner’, ‘catergory’
Size: 10,395 rows, 7 columns (891KB)
Source URL: https://www.kaggle.com/unanimad/the-oscar-award
Format/Access Method: CSV/Download from Kaggle
Years Covered: 1928-2020
TV shows on the Emmy Awards
Information on nominees and winners of the Emmy Awards. Created by Raphael Fontes.

Useful Variables: ‘nominee’, ‘win’, ‘company’, ‘category’
Size: 21,503 rows, 8 columns (3.92MB)
Source URL: https://www.kaggle.com/unanimad/emmy-awards
Format/Access Method: CSV/Download from Kaggle
Years Covered: 1949-2019
Amazon Prime Movies and TV Shows
Contains 9,668 titles for movies and shows on Amazon Prime. Created by Shivam Bansai.

Useful Variables: ‘country’, ‘rating’, ‘duration’, ‘listed_in’
Size: 9,668 rows, 12 columns (3.78 MB)
Source URL: https://www.kaggle.com/shivamb/amazon-prime-movies-and-tv-shows  
Format/Access Method: CSV/Download from Kaggle
Years Covered: 1920-2021
Netflix Movies and TV Shows
Contains 8,807 titles for movies and shows on Netflix. Created by Shivam Bansai.

Useful Variables: ‘country’, ‘rating’, ‘duration’, ‘listed_in’
Size: 8,807 rows, 12 columns (3.24 MB)
Source URL: https://www.kaggle.com/shivamb/netflix-shows 
Format/Access Method: CSV/Download from Kaggle
Years Covered: 1925-2021
IMDb Datasets: title.basics.tsv,
title.ratings.tsv
Subsets of IMDb data that are available for access to customers for personal and non-commercial use.

Useful Variables: ‘runtimeMinutes’, ‘genres’, ‘averageRating’, ‘numVotes’
Size: title.basics.tsv (697 MB), data/title.ratings.tsv (19.7 MB)
Source URL: https://datasets.imdbws.com/
Format/Access Method: TSV/Download from the source
IMDb API (IMDbPY)
Python package for retrieving and managing the data of the IMDb movie database about movies, people, and companies.

Useful Variables: ‘certificates’, ‘rating’, ‘votes’, ‘countries’, ‘runtime’, ‘genres’
Size: size of the complete IMDb database is not known
Source URL: https://imdbpy.readthedocs.io/en/latest/index.html
Format/Access Method: Fetch data directly from IMDb web server



