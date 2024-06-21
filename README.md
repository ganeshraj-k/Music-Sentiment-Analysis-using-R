# Analyzing Music Emotions with Spotify API

## 🎯 Project Objective

The main objective of this project is to perform sentiment analysis on music using Natural Language Processing (NLP) techniques and external libraries. We aim to explore the sentiment of lyrics associated with a song or artist, as well as the sentiment of the audio features of the music. We also aim to investigate the relationship between audio elements and sentiment in music, using statistical techniques to identify patterns and correlations. The project involves data visualization using R to help interpret the results.

## 🎵 Dataset Source

The data for this project is sourced from the Spotify API. It is a tool provided by Spotify, which allows users to interact and access data from the Spotify Streaming Platform. The API provides various endpoints that enable developers to retrieve data from millions of artists worldwide and also to control music playback in applications. It also provides access to the Spotify recommendation engine that suggests music based on a user’s recently played songs. We will be using this API to pull data regarding the albums of a selected artist.

## 📊 Methodology

- The albums are scored for positivity and negativity using the AFINN lexicon.
- The ratio of positive words to negative words gives us another metric that indicates how positive or negative the song is.
- The words in each album have been analyzed using the NRC lexicon that separates them into eight basic emotions (anger, disgust, fear, anticipation, trust, sadness, joy, and surprise) and two sentiments (positive and negative) based on their association with the words in the lexicon.
- The proportion of each emotion can further be plotted for each album which gives us an idea of what the dominating emotion is in each album.

## 📈 Results

The results of this project will provide insights into the emotional content of music and how it relates to various audio features. This could potentially be used to predict listener reactions to new music, inform the creation of music recommendation systems, and more.

Thank you for visiting this repository!
****
