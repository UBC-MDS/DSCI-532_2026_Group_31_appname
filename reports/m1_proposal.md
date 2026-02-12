# Chartify: Spotify Dashboard Analytics

## Section 1: Motivation and Purpose

**Our Role**: Data Scientists at Spotify

Music is universal. It has the ability to transcend language, age & culture to reach audiences from all corners of the globe. More importantly, music has the ability to stimulate the mind and alter your brain chemistry. Needless to say, understanding the qualities of "good" music is an important need for anyone in the music industry. 

As Data Scientists at Spotify, we aim to utilize Spotify's unique song attributes such as Acousticness, Valence, Tempo etc to create a dashboard that visualizes the qualities of "good" music. We are using song popularity as the analogy for "good" music. We see the application of our dashboard to a variety of audiences. For example, this dashboard can be used by music artists and producers to understand what song attributes resonate the most with listeners. This information can be used to refine the musical journey by adjusting the song's respective attributes. As well, given our dataset contains a feature `most_playedon` describing what platform listened to the songs most, we aim to use this as a differentiating attribute to understand how songs perform on different platforms. 

## Section 2: Description of the Data

We will be visualizing a dataset of 20594 music tracks originally retrieved from the Spotify Web API (deprecated) and compiled by Sanjana Chaudhari (2023) found [here](https://www.kaggle.com/datasets/sanjanchaudhari/spotify-dataset/data). Each track has 24 associated features which we have categorized into the following:

- Metadata and identification: Artist, Track, Album, Album_type, Title
- Acoustic profile: Danceability, Energy, Loudness, Speechiness, Acousticness, Instrumentalness, Liveness, Valence, EnergyLiveness
- Technical song attributes: Tempo, Duration
- Engagement metrics: views, Likes, Comments, Stream, most_playedon
- Distribution contexts: Channel, Licensed, official_video

