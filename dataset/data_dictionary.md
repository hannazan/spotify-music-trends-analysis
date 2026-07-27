# Data Dictionary

This document describes the variables used in the **Spotify Music Trends Analysis (2009–2023)** dataset.

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| Album Id | String | Unique identifier for each album. |
| Album Name | String | Name of the album where the track appears. |
| Album Release Date | Date | Official release date of the album. |
| Album Type | String | Type of album (Album, Single, or Compilation). |
| Album Total Tracks | Integer | Total number of tracks contained in the album. |
| Artist Name | String | Name of the artist performing the track. |
| Artist Followers | Integer | Total number of followers the artist has on Spotify. |
| Artist Genres | String | Music genres associated with the artist. |
| Artist Popularity | Integer | Spotify popularity score of the artist (0–100). |
| Track Id | String | Unique identifier for each track. |
| Track Name | String | Name of the track. |
| Track Number | Integer | Position of the track within its album. |
| Track Duration Ms | Integer | Duration of the track in milliseconds. |
| Track Popularity | Integer | Spotify popularity score of the track (0–100). |
| Explicit | Boolean | Indicates whether the track contains explicit content (`TRUE`) or not (`FALSE`). |

---

## Data Types

| Data Type | Description |
|-----------|-------------|
| String | Text values such as names or identifiers. |
| Integer | Whole numerical values. |
| Date | Calendar date in YYYY-MM-DD format. |
| Boolean | Logical values (`TRUE` or `FALSE`). |

---

## Notes

- The analysis focuses on tracks released between **2009 and 2023**.
- Album IDs and Track IDs serve as unique identifiers and were not used directly in the dashboard visualizations.
- Track Popularity and Artist Popularity are Spotify metrics ranging from **0 (least popular)** to **100 (most popular)**.
- Artist Followers represents the total number of followers for each artist on Spotify.
- Track Duration is stored in **milliseconds (ms)**.