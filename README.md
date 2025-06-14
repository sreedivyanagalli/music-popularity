-Music Popularity Analysis-

-Project Objective-
This project explores the relationship between various audio features and the popularity of music tracks, using data from Spotify. It aims to identify what makes a song popular using exploratory data analysis and machine learning.

-Tech Stack-
- Python
- Pandas / NumPy – Data preprocessing
- Matplotlib / Seaborn / Plotly – Data visualization
- scikit-learn – Regression modeling
- Jupyter Notebook

-Dataset-
- Source: Spotify API / Kaggle datasets
- Features:
  - `acousticness`, `danceability`, `energy`, `liveness`, `tempo`, `valence`, etc.
- Target: `popularity` score (0–100)

-Key Analyses Performed-
- Correlation matrix of audio features
- Distribution of popularity by genre and year
- Time-based trends in audio attributes
- Feature importance using regression models

-Models Built-
- Linear Regression
- Random Forest Regressor
- Evaluation: R² Score, MAE

-Result-
- Identified most influential features for popularity: `danceability`, `energy`, `valence`
- Achieved reasonable R² score (~0.75) on test data
- Visual insights reveal evolving music trends over time

-How to Use-
1. Clone the repository:
   ```bash
   git clone https://github.com/sreedivyanagalli/music-popularity.git
   cd music-popularity
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook music_analysis.ipynb
   ```
   
-Skills-
`EDA`, `Music Analytics`, `Spotify Dataset`, `Feature Engineering`, `Regression`, `Pandas`, `scikit-learn`, `Data Visualization`, `R² Score`
