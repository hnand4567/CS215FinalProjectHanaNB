
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


This project uses multiple visualizations to explore relationships between Spotify audio features and song popularity.

Visualization 1: Correlation Heatmap (Audio Features)
A correlation heatmap was used to examine relationships between all numerical Spotify audio features, such as danceability, energy, tempo, valence, and acousticness. This helped identify which features are most closely related and how strongly they interact with each other.

(edit me, insert the image of the correlation heatmap)
<!-- commenting this out for now, will fix later
![Audio Feature Correlation Heatmap](assets/correlation_heatmap.png)-->


Visualization 2: Popularity vs Danceability
A scatterplot was used to examine whether more danceable songs tend to be more popular. This visualization shows a weak positive relationship, but with significant variation, suggesting that danceability alone does not strongly determine popularity.

(edit me, insert the image of the scatterplot)
<!-- commenting this out for now, will fix later
![Popularity vs Danceability](assets/correlation_heatmap.png)-->


Visualization 3: Energy vs Popularity (Optional)
A second scatterplot explores the relationship between energy and song popularity. The results show a similarly weak relationship, reinforcing the idea that popularity is influenced by multiple factors rather than a single feature.

(edit me, insert the image of the scatterplot)
<!-- commenting this out for now, will fix later
![Energy vs Popularity](assets/correlation_heatmap.png)-->


Visualization 4: Genre Comparison (Average Danceability)
A bar chart compares average danceability across different genres. This reveals clear stylistic differences between genres, with some genres consistently producing more danceable music than others.

(edit me, insert the image of the bar chart)
<!-- commenting this out for now, will fix later
![Genre vs Danceability](assets/correlation_heatmap.png)-->


Visualization 5: K-Means Clustering of Songs
K-Means clustering, an unsupervised machine learning method, was used to group songs based on similarities in their audio features. This visualization reveals natural clusters of songs with similar musical characteristics, helping uncover structure in the dataset without predefined labels.

(edit me, insert the image of the cluster)
<!-- commenting this out for now, will fix later
![K-Means Clustering](assets/correlation_heatmap.png)-->


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
