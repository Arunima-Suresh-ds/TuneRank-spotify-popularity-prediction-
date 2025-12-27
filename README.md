#  TuneRank: Music Popularity & Performance Analysis

![Python](https://img.shields.io/badge/Python-3.8+-black?style=flat&logo=python)
![ML](https://img.shields.io/badge/Machine%20Learning-Classification-orange)
![Model](https://img.shields.io/badge/Models-RandomForest%20%7C%20XGBoost-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)



> Analyzing and ranking songs based on audio features to understand patterns behind music popularity using machine learning.

---

## Problem Statement

With the rapid growth of digital music platforms, thousands of songs are released daily. However, understanding **what makes a song popular** remains a challenge for artists, producers, and platforms.

Traditional ranking methods rely heavily on user engagement metrics, which are often unavailable or delayed. There is a need for a **data-driven approach** that leverages song-level audio characteristics to analyze and group music based on performance trends.

---

##  Project Overview

**TuneRank** is a machine learning project that analyzes music tracks using their **audio features** and applies **clustering techniques** to group songs into meaningful popularity segments.

The project focuses on:
- Exploring relationships between audio features and song performance
- Identifying patterns among high-, medium-, and low-performing tracks
- Ranking and segmenting songs without relying solely on user interaction data

This approach helps uncover **latent structures** in music data using unsupervised learning.

---

##  Dataset Description

The dataset consists of song-level information commonly available from music platforms and APIs.

### Key Features Include:
- **Popularity score** (numeric indicator)
- **Audio characteristics**:
  - Danceability
  - Energy
  - Loudness
  - Tempo
  - Valence
  - Acousticness
  - Instrumentalness
- **Song metadata**:
  - Duration
  - Mode
  - Key
  - Time signature

 The dataset primarily contains **numerical features**, making it suitable for clustering and exploratory analysis.

---

## Methodology Summary

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature scaling and transformation
- Application of **clustering algorithms** to group songs
- Interpretation of clusters as performance or popularity segments

---

##  Key Insights

- Songs naturally form clusters based on audio characteristics
- Certain feature combinations are more common in high-performing tracks
- Popularity is influenced by multiple interacting audio attributes rather than a single factor
- Clustering reveals trends not visible through raw popularity scores alone

---

##  Impact & Use Cases

This project demonstrates how machine learning can support decision-making in the music industry:

-  **Artists & Producers**  
  Understand which audio patterns align with successful tracks

-  **Music Platforms**  
  Improve recommendation systems and playlist curation

-  **Music Analysts**  
  Gain insights into trends across genres and popularity levels

-  **Data Science Applications**  
  Showcase unsupervised learning on real-world multimedia data

---

