# SQL Investigation of Top Spotify Songs and Personal Streaming History Data

## Overview

This project is an in-depth SQL investigation into the top songs on Spotify in August 2019, utilizing external data available on Kaggle. Additionally, personal Spotify streaming history data from the year 2023 was incorporated for a comprehensive analysis. The project encompasses various aspects of song characteristics, including artist statistics, genre preferences, and audio features, all analyzed using SQL queries.

## Data Sources

* The top songs dataset for August 2019 can be downloaded here.
* Personal Spotify streaming history data for 2023 was used to derive insights.

## Project Structure

1. Data Preprocessing: The project begins by importing necessary Python libraries and reading the 'top50.csv' file as a Pandas data frame. This step involves modifying headers to ensure compatibility with SQL queries.
2. Database Connection: A database is created and connected to, with a cursor established for executing SQL queries.
3. Data Conversion: The Pandas data frame is converted into a SQL table, named 'TopSongs,' within the database.
4. Exploratory Analysis:
     * Artist Analysis: Identification of artists with multiple songs in the top 50 list.
     * Featured Artists: Analysis of songs featuring other artists.
     * Genre Analysis: Examination of prevalent genres and genres containing the term 'pop' or 'rap.'
     * Beats Per Minute (BPM): Calculation of average BPM and categorization of songs relative to this average.
     * Energy Analysis: Calculation of average energy levels and categorization of songs.
     * Danceability Analysis: Calculation of average danceability scores and categorization of songs.

## Key Findings

* Artist Analysis: Ed Sheeran had the most songs (4) in the top 50, followed by nine other artists with two songs each.
* Featured Artists: Approximately 26% of the top Spotify songs featured other artists.
* Genre Analysis: Dance pop was the top genre, followed by pop and Latin. Nearly half of the songs had 'pop' in their genre.
* BPM Analysis: The average BPM was approximately 120.06, with no clear pattern indicating its significance.
* Energy Analysis: Songs with energy levels close to the average (64.06) were prevalent in the top 50.
* Danceability Analysis: Danceability scores close to the average (71.38) were common among the top songs.

## Personal Streaming History Data Analysis

In addition to the top Spotify songs analysis, personal streaming history data from 2023 was used to gain insights into listening habits. The following aspects were explored:

* Most Favorite Song: Identifying songs with the highest play count.
* Most Favorite Artist: Determining the artist with the most songs played.
* Most Favorite Album: Identifying the album from which the most songs were played.
* Platform Usage: Determining the most frequently used platform for streaming.
* Most Skipped Song: Identifying songs with the highest skip count.

## Conclusion

This project combines an in-depth investigation of top Spotify songs with personal streaming history data analysis, showcasing proficiency in SQL querying and data exploration. It offers insights into music preferences, genre popularity, and song characteristics. The results provide a valuable perspective on trends in top songs and personal listening habits.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
* Kaggle for providing the top songs dataset.
* Spotify for the personal streaming history data.
