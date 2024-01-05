# Letterboxd Sentiment Analysis

## Project Overview

This project undertakes a sentiment analysis to compare the audience's emotional responses towards movies directed by Christopher Nolan and Yorgos Lanthimos. The aim is to explore how the sentiments differ for a famous director like Nolan and an indie director like Lanthimos.
## Data Sources

The analysis is based on audience reviews and ratings for movies directed by Christopher Nolan and Yorgos Lanthimos. The data has been sourced from over 100 pages of letterboxd reviews for each movie, ensuring a diverse and comprehensive collection of audience opinions.

## Methodology

1. **Data Collection**: Gathering a large dataset of movie reviews and ratings for both directors from various online sources.

2. **Sentiment Analysis**: Using natural language processing techniques to analyze the sentiment of each review. This involves processing the text data, extracting relevant features, and classifying sentiments as positive, negative, or neutral.

3. **Comparative Analysis**: Comparing the sentiment distributions for Nolan's and Lanthimos' movies to identify notable differences or trends. Particular attention is given to understanding how the directors' status influences audience sentiment.

4. **Statistical Analysis**: Employing statistical methods to validate the findings and assess the significance of observed trends.

## Key Objectives

- To analyze the sentiments expressed in movie reviews for both directors.
- To compare the audience's emotional response to a mainstream, famous director (Nolan) versus an indie, less mainstream director (Lanthimos).
- To explore the role of directorial style and status in shaping audience perceptions and sentiments.

## Technologies Used

- Python for data processing and analysis.
- Libraries like Pandas, NLTK, and Scikit-learn for handling data and performing sentiment analysis.
- Visualization tools such as Matplotlib and Seaborn to illustrate findings.

## Results

We display below as an example the sentiment score for Interstellar. After filtering comments with invalid characters or in different languages:

![Christopher Nolan Comments](https://raw.githubusercontent.com/thatguysilva/LetterboxdSentiment/main/nolan-comment.png)

We reach:

![Christopher Nolan Score](https://raw.githubusercontent.com/thatguysilva/LetterboxdSentiment/main/nolan-score.png)

