# Coldplay Music Analysis

An exploratory data analysis (EDA) of Coldplay's discography using Spotify audio features. This project investigates how the band's musical style has evolved over time, which characteristics are associated with song popularity, and how diverse their music is.

## Objectives

This project aims to answer three questions:

1. How has Coldplay's music evolved throughout their career?
2. Which audio features are associated with a song's popularity?
3. How diverse is Coldplay's discography, and in what ways is it consistent?

## Dataset

The dataset used was taken from the following website: https://www.kaggle.com/datasets/faizalkarim/coldplay-albums-and-live-shows. 

The website also includes descriptions of each feature in the dataset. The dataset includes a comprehensive set of their studio albums (except *Moon Music*, as the dataset is from 2023) and live albums. 

The dataset originates from data collected by Spotify, which includes many different features for each song, including the album name, popularity, duration, tempo, and many others.

## Project Structure

```
├── data/
│   ├── raw/
│   └── cleaned/
├── notebooks/
├── requirements.txt
└── README.md
```

## Tools Used

- Python
- pandas
- Matplotlib
- Seaborn

## Key Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Data visualization
- Correlation analysis
- Statistical summaries
- Communicating insights from data

## Key Findings

- Coldplay's musical style has evolved across their albums, generally becoming less acoustic, more energetic, and less fast in tempo.
- No single Spotify audio feature strongly predicts song popularity.
- Some features are remarkably diverse, such as song's energy level, while others are centered on certain values, such as the music volume.

## Limitations

- The analysis focuses only on Coldplay's catalog and is not intended to generalize to other artists.
- Certain Spotify audio features are machine-generated estimates and may not perfectly reflect human perception.