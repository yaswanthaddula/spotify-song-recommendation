#  Spotify Song Recommendation System

##  Project Overview
This project is a **Spotify Song Recommendation System** built as part of my **Minor Project in Artificial Intelligence**.  
It uses **Machine Learning algorithms** to analyze audio features and playlist data, then recommends songs based on similarity and predicted popularity.

---

##  Technologies Used
- Python  
- Pandas, NumPy (Data Handling)  
- Matplotlib, Seaborn (Visualization)  
- Scikit-learn (Machine Learning Models)  
- Jupyter Notebook  

---

##  Dataset Information
The dataset includes Spotify tracks with features such as:  
-  Audio features: `danceability`, `energy`, `valence`, `tempo`, `acousticness`, etc.  
-  Playlist details: `playlist_name`, `playlist_genre`, `playlist_subgenre`  
-  Track popularity score  

---

## Steps in the Project
1. **Data Preprocessing**  
   - Handle missing values  
   - Convert release date to proper format  
   - Encode categorical columns  
   - Feature scaling  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution plots of audio features  
   - Correlation heatmap  
   - Popularity trends by genre and year  

3. **Clustering (Unsupervised Learning)**  
   - KMeans clustering on audio features  
   - Visualized clusters based on genres  

4. **Model Building (Supervised Learning)**  
   - Random Forest Regressor to predict song popularity  
   - Evaluation using MSE and R² Score  

5. **Recommendation System**  
   - Predicted popularity scores for all tracks  
   - Top 10 recommended songs generated  

---

## Results
-  Cleaned and preprocessed dataset with no missing values  
-  Clusters of songs by genres and features  
-  Random Forest model achieved good accuracy in predicting popularity  
-  Final recommendations: **Top 10 most popular tracks**  

---

##  How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/yaswanthaddula/spotify-song-recommendation
