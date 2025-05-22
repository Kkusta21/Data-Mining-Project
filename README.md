# Data-Mining-Project
# 🎧 Spotify Audio Features 

This data mining project explores the relationships between Spotify songs' audio characteristics and their popularity using statistical analysis and machine learning models. The dataset includes audio features of thousands of tracks retrieved from the Spotify API.

## 📌 Objectives

The primary goals of this project are:

1. **Descriptive Analysis:**  
   Understand the distribution and variation of audio features like energy, valence, tempo, etc.

2. **Diagnostic Analysis:**  
   Identify statistically significant relationships between audio features and song popularity.

3. **Predictive Analysis:**  
   Build models (Decision Tree, Logistic Regression, Neural Network) to predict if a song surpasses a popularity threshold.

4. **Prescriptive Analysis:**  
   Derive recommendations for artists and marketers based on predictive model results.

## 📊 Dataset

- Source: Spotify API / Kaggle Dataset
- Records: ~16,000 songs
- Features:  
  `acousticness`, `danceability`, `duration_ms`, `energy`, `instrumentalness`, `key`, `liveness`, `loudness`, `mode`, `speechiness`, `tempo`, `valence`, `popularity`, `explicit`, `artist`, `track_name`, etc.

## 📁 Project Structure

```plaintext
/spotify-audio-mining
├── data/
│   ├── spotify_audio_features.csv
│   └── cleaned_dataset.csv
├── notebooks/
│   └── analysis.ipynb
├── visuals/
│   └── plots and graphs
├── models/
│   └── decision_tree.pkl
│   └── logistic_regression.pkl
├── report/
│   └── DataMining_Final_Report.pdf
├── README.md
└── requirements.txt

