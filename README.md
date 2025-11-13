# 🎧 Spotify Data Analysis

Author: **Seth Frandsen**  
Date: **November 2025**  

This project explores data from the **Spotify Web API** to analyze the **popularity** of the songs in my playlists, and whether explicit content has any relationship to that popularity.  
All data was gathered ethically using Spotify’s public API and the [Spotipy](https://spotipy.readthedocs.io/en/2.25.1/) library.

---

## 🧠 Motivation

I wanted to better understand the music I listen to — specifically:
- How popular are the songs in my playlists?
- Does explicit content influence a song’s popularity?

Spotify collects a large amount of metadata for every track (popularity, duration, explicit content, artist, etc.). This project uses that information to perform exploratory data analysis on my own listening data.

---

## 🧰 Tools and Libraries

| Purpose | Library / Tool |
|----------|----------------|
| API Access | [Spotipy](https://spotipy.readthedocs.io/en/2.25.1/) |
| Authentication | [SpotifyOAuth](https://spotipy.readthedocs.io/en/2.13.0/?highlight=oauth#authorization-code-flow) |
| Data Analysis | [Pandas](https://pandas.pydata.org/) |
| Visualization | [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/) |
| Environment | Python 3.10+ |

---

## 🔐 Setup & Authentication

1. Go to the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/).
2. Create a new app to obtain your:
   - `Client ID`
   - `Client Secret`
   - `Redirect URI`
3. Create a `.env` file (or similar config file) in your project directory:

   ```bash
   SPOTIPY_CLIENT_ID='your-client-id'
   SPOTIPY_CLIENT_SECRET='your-client-secret'
   SPOTIPY_REDIRECT_URI='your-redirect-uri'


## ⚠️ Cautions ⚠️
  -When scraping or using the API, make sure to use proper ettiqutte and follow the robots.txt. have sufficient time between your requests,     even when using an API. 
  
  -Do not share you Client ID or Client Secret as they are tied to you.
  
  
