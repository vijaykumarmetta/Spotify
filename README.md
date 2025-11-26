# Spotify
This repository contains a visually rich, fully functional Spotify Analytics Dashboard built using Power BI, leveraging a cleaned dataset derived from Spotify's daily Top-50 charts.
This project presents a fully interactive Spotify Analytics Dashboard built in Power BI using the Top-50 global streaming dataset.
The goal of the dashboard is to help music analysts, playlist managers, and marketing teams easily monitor performance indicators across Spotify songs, artists, and albums.

The dashboard transforms raw daily Top-50 ranking data into meaningful KPIs, trends, segmentations, and drill-downs—empowering stakeholders to make data-driven decisions on music promotion, curation, and market strategy.

📄 README.md
🎧 Spotify Analytics Dashboard – Power BI

This repository contains a visually rich, fully functional Spotify Analytics Dashboard built using Power BI, leveraging a cleaned dataset derived from Spotify's daily Top-50 charts.

🚀 Features
1️⃣ Overview Page

Provides a high-level snapshot of Spotify’s music performance:

🎵 Total Distinct Songs

👥 Total Artists Count

⭐ Average Popularity Score

⏱️ Average Song Duration

🔞 Explicit vs Non-Explicit Song Share

💿 Songs by Album Type (single, album, compilation)

📅 Songs & Popularity by Release Year

📈 Monthly Trends

Avg Popularity by Month

Distinct Songs by Month

🏆 Top Artists & Top Songs

2️⃣ Artist Insights Page

Drill-down analytics focused on individual artists:

📊 Total Songs by Artist

🎼 Artist Album Counts

🔥 Count of Explicit Songs per Artist

⭐ Popularity Score Contribution

📋 Artist-Level Data Table:

Song name

Album type

Release year

Avg popularity

Max popularity

Avg duration

3️⃣ Song Insights Page

Song-level deep analysis:

🏆 Top Songs by Popularity

🎧 Song Count Across Album Types

🔞 Explicit/Non-Explicit Distribution

📅 Song performance by month

📋 Detailed Record Table:

Song

Artist(s)

Album type

Song age

Release date

Popularity (avg & max)

Duration

📊 Dataset Schema
Column Name	Description
date	Chart date
position	Spotify Top-50 rank
song	Track name
artist	Artist(s)
popularity	Popularity score (0–100)
duration_ms	Song duration in milliseconds
album_type	album / single / compilation
total_tracks	Total tracks in the album
release_date	Release year
is_explicit	True / False
album_cover_url	Album artwork
🧠 Business Requirements Solved
✔ KPI Monitoring

Instant view of total songs, artists, popularity, and durations.

✔ Explicit vs Non-Explicit Analysis

Shows how explicit content performs compared to non-explicit.

✔ Album Type Distribution

Helps identify whether singles or albums dominate charts.

✔ Trend Analysis

Monthly and yearly shifts in song popularity and distinct song count.

✔ Connected Insights

Overview → Artist page → Song page
Creates a complete analysis flow from macro to micro level.

✔ Actionable Insights for Spotify Teams

Identify trending artists

Understand what type of music performs best

Support playlist creation decisions

Recognize seasonal patterns

Detect high-performing explicit/non-explicit songs

🛠️ Technologies Used

Power BI Desktop

DAX (Data Analysis Expressions)

Power Query

Spotify Dataset (Top-50 Daily Data)

Excel / CSV Data Processing


  **Dashboard Preview**
  <img width="1252" height="719" alt="Screenshot 2025-11-26 102632" src="https://github.com/user-attachments/assets/2d90a72f-ca1d-46d3-b214-32f03e5f9e45" />
  <img width="1325" height="744" alt="Screenshot 2025-11-26 102710" src="https://github.com/user-attachments/assets/fb1fe531-0c05-4bd5-8901-ce9f62387ee2" />
<img width="1324" height="737" alt="Screenshot 2025-11-26 102658" src="https://github.com/user-attachments/assets/7e3f2586-d1d9-4c03-978a-47cd5a60c54e" />

<img width="1326" height="746" alt="Screenshot 2025-11-26 102646" src="https://github.com/user-attachments/assets/6adc5a43-30f4-4650-a26a-20f5cf409e87" />


