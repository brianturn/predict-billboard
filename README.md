# Hot or Not: Predicting Billboard HOT 100

## Summary

What makes a song catchy? Can we predict if a song will land on the Billboard HOT 100?

These are the questions I set out to explore for one of my projects while attending Metis, a full-time data science bootcamp in New York City, during the Spring of 2017.

For this problem, I built a binary classification model to predict whether or not a song will reach the Billboard HOT 100, based on the song’s audio features. Examples of song features include, tempo, key, energy, and “speechiness” (probability song is all spoken-word), plus nine additional features. 

## Data

- 10,000 song titles from a subset of the Million Song Dataset
- the entire history of HOT 100 songs scraped from billboard.com
- audio features acquired from the Spotify API. 

## Repo Contents

The IPython Notebooks are [here](https://github.com/brianturn/predict-billboard/tree/master/images)

The presentation is [here](https://github.com/brianturn/predict-billboard/blob/master/presentation/turner_presentation_billboard.pdf)

Matplotlib [visualizations](https://github.com/brianturn/predict-billboard/tree/master/images)

## Results

Gradient boosting classifier with decision trees performed the best, with an accuracy of 71% and an F1 score (ratio of precision and recall) of 41%. 

No single audio feature stood out as singularly being the most indicative (unfortunately), but the most important features included tempo and speechiness. Hint: write a song at 125 beats per minute. 

## Tools

- Scikit-learn: machine learning in Python
- BeautifulSoup
- Pandas
- Matplotlib
- APIs: Spotify



