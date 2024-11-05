# An Exploratory Data Analysis on Most Streamed Spotify Songs of 2023
Explore the world of music trends through Spotify's most-streamed tracks of 2023. This analysis dives into the data behind popular songs to understand patterns and characteristics of highly streamed music. From genre insights to trends over time, this project sheds light on what drives streams and who the top artists are.
***
## Overview
This exploratory data analysis (EDA) investigates the attributes of Spotify's top songs in 2023. Using a comprehensive dataset from [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023/data), we examine trends, track performance, and correlations between various musical characteristics and popularity. The project provides insights into the composition of top tracks and evaluates the influence of different platforms like Spotify and Apple on track popularity. This analysis highlights patterns in streaming data, genre-specific trends, and examines how factors like danceability, tempo, and energy impact track popularity.

## What Makes a Track Popular?
Ever wondered what it takes for a song to top the charts? This analysis delves into the attributes that make a track stand out. From beats per minute (bpm) to danceability and energy levels, we explore how these factors correlate with streaming numbers. Discover the secrets behind the most streamed tracks and see if your favorite songs have what it takes. Dive into the data to find out more!

## Highlights
The notebook contains the following:
1. **Overview of the Dataset**
   - contains rows and columns count, data types of each column, and an assessment of missing values. <br>

2. **Basic Descriptive Statistics**
   - Mean, median, and standard deviation of the `streams` column.
   - Distribution analysis for `released_year` and `artist_count` to identify trends or outliers.

3. **Top Performers**
   - Analysis of the top 5 most streamed tracks and the most frequent artists.

4. **Temporal Trends**
   - Examination of track release trends over time, including yearly and monthly patterns.
   - Identification of which month sees the most releases and potential patterns in release timing.

6. **Genre and Music Characteristics**
   - Correlations between streams and musical attributes like `bpm`, `danceability`, and `energy`.
   - Analysis of relationships among attributes, such as `danceability_%` and `energy_%`.

6. **Platform Popularity**
   - Comparison of track numbers across Spotify playlists, Spotify charts, and Apple playlists, analyzing which platform supports popular tracks the most.

8. **Advanced Analysis**
   - Pattern analysis for tracks with similar `key` or `mode` (Major vs. Minor).
   - Examination of artists and genres that frequently appear in playlists or charts.

Each section provides a thorough exploration of these aspects, revealing interesting takeaways about the music that defined 2023. ​

## Installation and Setup
To get started with this analysis, you’ll need to have the following Python libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Here is a step-by-step process on how to access the notebook:
1. Install Jupyter Notebook through [Anaconda Navigator](https://www.anaconda.com/download) or directly from their [website](https://jupyter.org)
2. Run the following command in the terminal to start Jupyter Notebook:
```
jupyter notebook
```
4. Download `spotify-2023.csv`.
5. Download `MSSS2023_EDA.ipynb` within the same file directory as `spotify-2023.csv`.
6. Open the notebook then execute the codes

## The "spotify-2023" Dataset
This dataset contains a detailed list of the most popular songs of 2023 on Spotify. It includes extensive features that provide insights into each song’s attributes, popularity, and presence across multiple music platforms. Key information includes **track name, artist(s), release date, and streaming statistics, along with presence on Spotify, Apple Music, Deezer, and Shazam charts**. Additionally, the dataset offers various audio features such as **BPM, key, mode, danceability, valence, energy, acousticness, instrumentalness, liveness, and speechiness**. This comprehensive dataset is valuable for analyzing trends and patterns in music popularity and characteristics.

In handling this kind of dataset, the analysis is broken down to key steps:
1.	**Data Preparation**: Importing essential libraries and reading the dataset.
2.	**Initial Data Exploration**: Viewing the structure and characteristics of the data.
3.	**Data Cleaning**: Handling missing values and ensuring data consistency.
4.	**Descriptive Statistics**: Summarizing the data using basic statistical methods.
5.	**Visualization**: Creating plots to visually represent patterns and trends.
6.	**Insights and Conclusions**: Highlighting significant observations from the analysis.

## Data Findings and Visualizations
Here are some of the data visualizations obtained from the dataset:
#### Density Distribution of Released Years
![Density Distribution of Released Year](https://i.pinimg.com/1200x/5b/ca/e0/5bcae0f599989bac9d6f8add9f4f5f82.jpg)

#### Number of Released Tracks Per Year
![Number of Released Tracks Per Year](https://i.pinimg.com/1200x/9b/57/1d/9b571ddb1b025fa694f3089183df5042.jpg)

#### Number of Released Tracks Per Month
![Number of Released Tracks Per Month](https://i.pinimg.com/1200x/fb/af/40/fbaf40787ccc0babfaf1937bfe410327.jpg)

#### Streams vs. Key by Mode
![Streams vs. Key by Mode](https://i.pinimg.com/1200x/0d/f8/e6/0df8e60d3c4b554053253813c24ed5df.jpg)

#### Top 10 Artists by Playlist/Chart Appearances
![Top 10 Artists by Playlist/Chart Appearances](https://i.pinimg.com/1200x/f5/15/bd/f515bde761911717ecb6ed27c8b5c6ac.jpg)

## Challenges and Limitations
Dealing with this 

## Key Takeaways

## Insights and Recommendations

## Contact Information
For any questions or feedback, please reach out to:<br>
- Email: johnmarkaparicio.eng@ust.edu.ph <br>
- GitHub: https://github.com/merkjunnie

## Relative External Links
