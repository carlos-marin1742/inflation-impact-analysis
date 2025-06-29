#  Spotify Music Recommendation system using Spotify API

<img src="https://i.pcmag.com/imagery/reviews/042FW7hC9vrGnoDea9LArXI-35.fit_scale.size_1028x578.v1674253030.png" width=700 height=500 />

## Background

A Music Recommendation System is an application of Data Science that aims to assist users in discovering new and relevant musical content based on their preferences and listening behaviour. Personalized music recommendations have become an essential tool in the digital music landscape, enabling music streaming platforms like Spotify and Apple Music to offer personalized and engaging experiences to their users. 




## Business Problem

We are building a music recommendation system using Spotify API.

Why?
    
Data is constantly changing, a CSV file for analysis may not always be available.
    
Being Able to pull data using API, allows you to do analysis without the need for a CSV or data file.

## Data

Playlist is created by me, on Spotify, which is accessible after obtaining access using Spotify API.

Any Playlist on Spotify, is eligible for analysis.


## Methods

Using Spotify Developer, obtained credentials.

With credentials, were then encoded to create secure representation of credentials using base64 encoding.

Token Access was requested using Spotify API.

Using Spotify's Python library, Spotipy, created function that allowed us to pull Spotify Music Data

Created Music Recommendation System using Cosine Similarity based on music Audio Features.


## Results

The created function created using cosine similarity provides list of similar songs based on audio features, into a pandas Dataframe.



## Conclusions / Summary of Findings

By using API to access data, we can create ongoing recommendation systems without the need ongoing creating CSV/data files. 





### Overview of Github structure

├── README.md : project information and repository structure


