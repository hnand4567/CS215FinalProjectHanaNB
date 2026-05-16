
# Spotify Audio Features & Song Popularity Analysis

## Project Overview
This project uses Spotify audio feature data to understand patterns behind song popularity.

---
## Dataset

The dataset contains approximately 114,000 songs with the following features:

- track name, artist, genre  
- popularity score (0–100)  
- audio features:
  - danceability  
  - energy  
  - tempo  
  - valence  
  - acousticness  
  - instrumentalness  
  - speechiness  
  - liveness  

Source: Spotify audio feature dataset (Kaggle)

---

## Research Questions
1. Which audio features are most associated with song popularity?  
2. Do more danceable or energetic songs tend to be more popular?  
3. How do different genres differ in their musical characteristics?  

---

## Methods
The following data analysis techniques were used:

- Data cleaning and preprocessing (removal of unused columns, handling missing values)
- Correlation analysis between numerical features
- Data visualization (scatterplots, bar charts, heatmaps)
- K-Means clustering to group similar songs based on audio features

---

## New Technique
K-Means clustering, an unsupervised machine learning method, was used to group songs based on similarities in their audio features, including danceability, energy, valence, tempo, and acousticness. This technique helped reveal natural groupings of songs with similar musical characteristics, allowing for a better understanding of how different styles of music relate to one another within the dataset.

---

## Key Findings
- No single audio feature strongly determines popularity  
- Danceability and energy show weak relationships with popularity  
- Songs naturally cluster into groups with similar musical characteristics  
- Music preference appears to be multi-dimensional rather than driven by one factor  

---

## Key Visualizations
(edit me)
<!-- commenting this out for now, will fix later
![Correlation Heatmap](assets/correlation_heatmap.png)-->

---

## Tools Used
- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- Scikit-learn (K-Means clustering)

---

## Files
(edit me)
<!-- will finish this and edit it
- `notebook.ipynb` — full analysis
- `spotify_tracks.csv` — dataset used
-->

---

## Reflection
This project showed that music data is highly multi-dimensional, and simple assumptions (like “more energetic songs are more popular”) do not fully explain trends in popularity. The most interesting insight was how clearly songs form clusters based on audio similarity.

---

## Future Work
- Incorporate lyrics analysis (NLP)
- Explore trends over time more deeply
- Test additional clustering methods
