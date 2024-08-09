# Spotify Eploratory Data Analysis & Songs Recommendation

## Situation:

I was working with a large dataset of Spotify tracks containing 113,550 unique songs with 20 different features. The dataset included information on track characteristics, popularity, and audio features.

# Task:

My main objectives were to:

1. Conduct exploratory data analysis to understand the dataset's structure and characteristics.
2. Investigate how different genre-related characteristics affect song popularity.
3. Analyze how artists should choose their music genres.
4. Develop a song recommendation system based on user preferences.

## Action:

1. Data Exploration and Preprocessing:
    - Imported necessary libraries and loaded the dataset.
    - Cleaned the data by removing duplicates and handling missing values.
    - Analyzed the distribution of numerical and categorical variables.
    - Investigated correlations between different audio features.
2. Genre Analysis:
    - Identified top genres based on popularity and number of songs.
    - Examined the relationship between genre characteristics (e.g., explicit content, liveness) and popularity.
    - Compared popular genres with those favored by top artists.
3. Artist Strategy Analysis:
    - Investigated the impact of genre specialization vs. diversification on artist popularity.
    - Analyzed the distribution of genre counts among all artists and top artists.
4. Recommendation System Development:
    - Implemented a similarity-based recommendation system using Euclidean distance.
    - Identified the K-nearest neighbors for a given track based on audio features.

## Result:

1. Data Insights:
    - Identified key trends in popular music, such as the dominance of pop genres and the correlation between energy and loudness.
    - Discovered that explicit content and live performances vary significantly across genres.
2. Genre Impact on Popularity:
    - Found that genres like pop-film, K-pop, and chill tend to be more popular.
    - Observed that top artists often produce music in popular genres, but also explore unique genres.
3. Artist Strategy Findings:
    - Determined that both genre specialization and diversification can lead to success, with no clear advantage to either approach.
    - Noted that most artists, including top performers, tend to focus on 1-3 genres.
4. Recommendation System:
    - Successfully developed a system that can suggest similar tracks based on a user's current listening preferences.
    - Demonstrated the system's ability to recommend the top 5 most similar tracks for a given input song.

This project provided valuable insights into the Spotify music ecosystem and created a functional tool for personalized music recommendations, potentially enhancing user experience on the platform.
