## 🎵 Musify: Aspect-Based Analysis & Visualization of Spotify Data
Musify is a data visualization and analysis application built to explore and interpret Spotify song data in-depth. By leveraging the Spotify Web API, data science tools, and visualization libraries, Musify uncovers trends, correlations, and insights about song characteristics, genres, artists, and the evolution of music over time.

**Musify was presented at the 4th International Conference on Artificial Intelligence and Speech Technology (AIST 2022) & published in IEEE**

## 📊 Overview
This project dives into:

- How Spotify recommends songs based on user behavior
- Statistical trends in song attributes (danceability, energy, loudness, etc.)
- Correlation between song popularity, artist popularity, followers, and other metadata
- Visualization of top genres, artists, and song attributes across years


## 🧠 Features
- 🔍 **Statistical Analysis:** Explore how features like tempo, energy, and valence vary across time or genre.

- 🔗 **Correlation Mapping:** Understand how different song parameters are related using heatmaps.

- 📈 **Visual Insights:** Interactive and static charts like pie, bar, and line plots to analyze genre distribution, artist popularity, and more.

- 🎧 **Artist-Specific Views:** See how specific artists perform in terms of popularity and number of charted songs.

- 🧬 **Aspect Analysis:** Deep dives into how Spotify's recommendation system might weigh various track attributes.

## 🛠️ Tech Stack

- Technology	Role
- Python	Core programming language
- Jupyter Notebook	Development environment
- Spotipy	Spotify Web API access
- Pandas & NumPy	Data manipulation
- Matplotlib & Seaborn	Data visualization
- Urllib	Fetching album covers

## 🧪 Methodology
- **Data Extraction:** Used the Spotify Developer API to fetch song-level data using Spotipy.
- **Data Preprocessing:** Cleaned and structured the data into meaningful categories: genres, features, artists, etc.
- **Feature Analysis:** Explored relationships between song characteristics and their impact on popularity.
- **Visualization:** Created pie charts, bar charts, heatmaps, and scatter plots to represent insights.

## 📌 Key Insights
- Artists with higher followers generally produce more popular songs.
- Acoustic tracks tend to have lower energy and loudness.
- Danceability positively correlates with energy and loudness.
- Rap and Pop dominate as the most frequent genres in top charts.
- Despite lower followers, artists like Billie Eilish rank high in chart appearances.

## 📥 Installation & Setup
Clone the repository:
```bash
Copy
Edit
git clone https://github.com/your-username/musify.git
cd musify
Create a virtual environment and install dependencies:
pip install -r requirements.txt
python musify.ipynb
```

## Set up your Spotify Developer credentials:
- Visit Spotify Developer Dashboard
- Create an app and get your Client ID and Client Secret
- Set up environment variables or paste credentials in the notebook.

## 👩‍💻 Authors 
Kanika Kamalhans <br/>
Anushka Gupta <br/>
Indira Gandhi Delhi Technical University for Women

**December 2022 <br/>
DOI:10.1109/AIST55798.2022.10065226 <br/>
Conference: 2022 4th International Conference on Artificial Intelligence and Speech Technology (AIST)**

