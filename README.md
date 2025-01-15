## Overall Description

- This project aims to analyze and compare music trends and user preferences for various genres in 2023 and 2024. By leveraging track-level features and popularity metrics, the analysis will provide insights into how music styles evolve over time, as well as highlight top tracks and artists for each year. The findings will be particularly useful for musicians, singers, and entertainment companies to understand and adapt to shifting audience preferences.

## Objectives 

* Examine trends in music styles using track features (e.g., tempo, danceability, energy, etc.).
* Provide actionable insights for musicians, singers, and entertainment companies about the trending music styles.
* Identify top tracks and artists of 2023 and compare them with those in 2024.
* Highlight any significant changes in user preferences or genre popularity between the two years.

## Data Summary

### Data Source

* https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023

* https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024

### Data Description

* These datases present a list of most famous songs of 2023 and 2024 as listed on Spotify. They provide insights into each song's features, popularity and their presence on audio streaming platforms like Apple Music, Soundcloud,... or other platforms like YouTube or TikTok. 

#### Dataset Structure

* 2023 dataset: 953 rows and 24 columns, which include track names, artists, presence in audio streaming platforms, and features of songs (danceability%, valence%, ...). The following shows a sample of the data:

<p align="center">
    <img src="data/2023_sample1.png"/>
</p>

<p align="center">
    <img src="data/2024_sample2.png"/>
</p>

* 2024 dataset: 4600 rows and 29 columns. This dataset has more records and more information regarding songs' presence in different platforms, but doesn't have the data regarding songs' features (danceability%, valence%, ...). The following shows a sample of the data:

<p align="center">
    <img src="data/2024_sample1.png"/>
</p>

<p align="center">
    <img src="data/2024_sample2.png"/>
</p>

## Insights and Conclusions

#### Problem 1: What are trending music genres this year and last year?
- 2023 music trend:
    + Tempo and Vibe: In 2023, medium-high tempo songs with neutral vibes were the top choices among users. It sugguests that genres like Rock or Pop  were trending in 2023. However, from the acousticness and instrumentalness, we can see that people didn't prefer the soft, acoustic or traditional music.

    + Instead, modern music with meidum to high danceability or positive energy was favored. However, people didn't really prefer music with extremely danceability (e.g EDM,...). They seemed to prefer songs with a balanced, neutral, or slightly higher energy level

    + Regarding the emotional tone, look at the analysis on the valence, people enjoy songs with neutral vibes. They don't really too "sad" or too "happy" song. This result aligns with real-life trends, as young people are mostly listening these music types.

    + For liveness and speechiness: People didn't listen songs that have high liveness or speechiness. It suggests that they mostly list the audio version, not the live version. However, most of versions on music platforms are audio version; therefore, this didn't suggest people prefer audio version than live version

    + This result aligns with real-life trends, as young people are mostly listening these music types.

    + Read this article for some other analysis on popular music genre among gen Z: https://www.wokewaves.com/posts/what-genre-of-music-is-most-popular-with-gen-z

- 2024 music trend:

    + In 2024, we didn't see the significant change in music genre trend among tracks that appear in both dataset. However, for many other tracks, we don't have enough information to make any conclusion about music genre trends.

    + 1/2 of tracks appear in 2023 didn't appear in 2024 dataset. It suggests that maybe trend has changed since most of the songs appear in 2023 were no longer appear in 2024

    + 1/2 of tracks appeared in 2023 didn't appear in 2024 dataset. It can also suggest that there are currently a lot of "instant" hits - which are only viral for a short time due to elements like catchy hook. After half of the year or a year, these songs tend to be forgotten. These tracks are mostly viral on short videos on TikTok or YouTube short.

    + Read this article: https://www.miamistudent.net/article/2023/11/tiktok-effect-on-popular-music

#### Problem 2: What are the trending artists this year and last year?

- 2023:
    + Popular artists in 2023 are Taylor Swift, The Weeknd, Bad Bunny, Ed Sheeran, Olivia Rodrigo, ... Most of them have R&B, pop or dance-pop songs, punk songs or rap songs, which support the conclusion about the trending music style in 2023
    + This conclusion once again suggest that the trending music genres in 2023 were R&B, Rock, Pop with medium-high tempo, high energy, and medium positivity.

- 2024:

    + On audio streaming service providers, top artists were mostly the same as in 2024, except some new noticeable names such as Drake or Arinana Grande. Their music genres are also pop, rock, R&B, or Latin. There is no significant change compared to 2023. Therefore, we can conclude that the trends of music genres didn't change a lot in 2024 compared to 2023. The reason why there are only 1/2 tracks which appeared on 2023 still appear on 2024 list is maybe as described in the previous question: many songs are only viral on a short time since they are attractive only due to a short hook, which are usually used in short videos on TikTok or YouTube short.

    + On TikTok, we can see there are a lot of new artists in high ranking. They could be both artists and full-time content creators, who focus on making music tracks which are have only one or two short attractive hook and then make them viral through their videos and reups.

    + Again, this article is really helpful for this idea. 
    https://www.miamistudent.net/article/2023/11/tiktok-effect-on-popular-music

## Reference

#### Spotify Charts

https://support.spotify.com/us/artists/article/charts/

#### Datasets:

https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023

https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024

#### The Evolving Music Tastes of Gen Z: A Diverse Landscape
https://www.wokewaves.com/posts/what-genre-of-music-is-most-popular-with-gen-z

#### The ‘Tiktokification’ of modern pop music: How Tiktok changed the music industry
https://www.miamistudent.net/article/2023/11/tiktok-effect-on-popular-music





