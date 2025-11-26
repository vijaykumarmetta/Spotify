**Project Documentation – Spotify Analytics Dashboard (Power BI)**

📌 1. Project Overview

The Spotify Analytics Dashboard is an end-to-end Power BI solution built to analyze the performance of songs, artists, and albums using Spotify’s daily Top 50 charts.
The objective is to give stakeholders—music analysts, playlist curators, and marketing teams—actionable insights through data visualization and trend analysis.

📌 2. Business Problem

Spotify provides raw Top-50 lists, but they lack summarization, trend visibility, and comparative analytics. Stakeholders struggle to identify patterns such as:

Which artists consistently dominate the charts

Trends across months and years

Explicit vs non-explicit content performance

Distribution of singles vs albums

Seasonal spikes in popularity

Song duration and popularity patterns

This project solves these problems by building a centralized analytical dashboard.

📌 3. Project Objectives
✔ Business-Level Objectives

Provide a unified dashboard summarizing KPIs

Analyze artist & song performance across time

Identify patterns useful for playlist creation and promotions

Monitor explicit vs non-explicit song performance

Understand album type contribution (single/album/compilation)

✔ Technical Objectives

Clean and model Spotify Top-50 data

Build a star-schema optimized Power BI data model

Create DAX measures for KPIs, trends & segmentation

Develop drill-down pages for Artist and Song analysis

Implement interactive slicers and dynamic visuals

📌 4. Data Source & Schema
Dataset: Spotify Daily Top-50 Dataset
File Format: CSV
Columns Used
Column Name	Description
date	Chart date
position	Top 50 ranking
song	Track name
artist	Artist(s)
popularity	Popularity score
duration_ms	Song duration
album_type	album / single / compilation
total_tracks	Tracks in the album
release_date	Release year
is_explicit	True/False
album_cover_url	Cover art
📌 5. Data Cleaning & Transformation

Performed in Power Query:

Converted date formats

Extracted year from release_date

Converted duration (ms to minutes)

Removed duplicates and nulls

Split multiple artists where required

Categorized album types

📌 6. Data Modeling
Model Type: Star Schema

Fact Table:

Fact_Songs (song metrics)

Dimension Tables:

Dim_Artists

Dim_Album

Dim_Date

Relationships:

Date → Fact (1:Many)

Artist → Fact (1:Many)

Album → Fact (1:Many)

📌 7. DAX Measures Developed

Examples include:

Total Songs

Distinct Artists

Avg Popularity

Avg Duration (Min)

Count of Explicit Songs

Songs by Album Type

Monthly Trend Measures

Year-wise Distinct Song Count

📌 8. Dashboard Pages & Features
🔹 1. Overview Page

Total Distinct Songs

Total Artists

Avg Popularity

Avg Duration

Explicit vs Non-Explicit Breakdown

Album Type Distribution

Songs by Year

Monthly Trends

Top Artists

Top Songs

🔹 2. Artist Page

Total Songs by Artist

Artist Album Count

Explicit Songs Count

Popularity Contribution

Artist Data Table (song, year, popularity, duration)

Artist-level drill-through capability

🔹 3. Songs Page

Top Songs by Popularity

Songs by Album Type

Explicit vs Non-Explicit at Song Level

Monthly Song Count

Detailed Table (song, artist, release date, duration, popularity)

📌 9. Key Insights Identified

Singles dominate the Top-50 lists

Explicit songs have high representation but slightly lower average popularity

Peak chart activity occurs around July–September

A small group of artists produce the majority of hits

Duration sweet spot lies around 3–3.5 minutes

Certain months show significant drops in song popularity

📌 10. Business Impact

With this dashboard, Spotify teams can now:

Quickly identify high-performing songs & artists

Understand content trends across months and years

Align marketing campaigns with seasonal patterns

Optimize playlist creation

Promote artists based on data-backed insights

Track the performance of explicit vs clean versions

📌 11. Tools & Technologies

Power BI Desktop

DAX

Power Query

Excel / CSV

Spotify Dataset

📌 12. How to Use

Download the .pbix file

Place the dataset in the same folder

Refresh data source path in Power BI

Explore visuals with slicers and drilldowns

📌 13. Future Enhancements

Connect to Spotify API for live data

Add Genre-wise analytics

Integrate AI Insights using Fabric

Playlist recommendation model

📌 14. Screenshots

**Dashboard Preview**
  <img width="1252" height="719" alt="Screenshot 2025-11-26 102632" src="https://github.com/user-attachments/assets/2d90a72f-ca1d-46d3-b214-32f03e5f9e45" />
  <img width="1325" height="744" alt="Screenshot 2025-11-26 102710" src="https://github.com/user-attachments/assets/fb1fe531-0c05-4bd5-8901-ce9f62387ee2" />
<img width="1324" height="737" alt="Screenshot 2025-11-26 102658" src="https://github.com/user-attachments/assets/7e3f2586-d1d9-4c03-978a-47cd5a60c54e" />

<img width="1326" height="746" alt="Screenshot 2025-11-26 102646" src="https://github.com/user-attachments/assets/6adc5a43-30f4-4650-a26a-20f5cf409e87" />



📌 15. Author

Vijay Kumar Metta
Power BI Developer 



  
