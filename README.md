# Anime Recommendation System
## Overview
With the wide offer of streaming services nowadays, we may think that it'd be easier than ever to get accurate recommendations when looking for an anime similar to the one we just watched and liked. 
Taking into consideration the multitudes of anime streaming services - with some animes being licensed with only one streaming service; 
some seasons separated across multiple streaming services, etc. - it can get quite challenging. This project therefore aimed to create a robust anime recommendation system.

This started as a project for a Big Data Analytics course; we had to choose a solved Kaggle Notebook and try to run it. 
The one we chose technically worked, but the data was scraped and wasn't up-to-date. 

## Goals
We wanted to:
- Have access to an updated and legal dataset while still using MyAnimeList API;
- Improve the recommendation system to base the recommendations on synopsis rather than genres;
- As some input animes were series with multiple seasons/movies/OVAs, etc., the top recommendations would be animes from the same series as their synopsis were so similar,
one of our goals was to fix that as well;
- And finally make sure the recommendations would be safe for children, e.g. we made sure that genres that might be considered as sensitive centent would only appear
if the input anime contained one of those specific genres.

## Implementation
This is a Jupyter Notebook. We built our Anime Recommendation System using:
- <b>Python</b> (for data processing and ML models)
- <b>Pandas & NumPy</b> (for dataset handling)
- <b>Scikit-Learn</b> (for TF-IDF and Cosine Similarity)
- <b>RapidFuzz</b> (for title matching and to handle typos)
- <b>MyAnimeList API</b> (to legally fetch updated anime data)

To be able to run this notebook, you'll have to obtain your own Client ID from MyAnimeList API.

## Licence
This project uses the MyAnimeList API in compliance with their terms of service. 
I do not condone or support any form of scraping, illegal use, or unauthorised access to MyAnimeList data. 
Please ensure that any use of this code adheres to MyAnimeList's official API terms and conditions.
