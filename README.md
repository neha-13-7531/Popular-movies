# 🎬 Popular Movies Dataset – Exploratory Data Analysis

This repository contains an in-depth Exploratory Data Analysis (EDA) on a dataset of 1,000 popular movies collected from TMDB (The Movie Database). The goal is to uncover trends and extract meaningful insights related to movie genres, ratings, popularity, production companies, and viewer preferences.


## 📊 Project Overview

The analysis focuses on:
- Identifying the most popular and profitable movie genres.
- Exploring patterns in runtime, language, and production companies.
- Understanding what drives a movie's popularity and revenue.
- Delivering actionable recommendations for content creators and production studios.

---

## 📦 Dataset Features
- **1 title**   :  Name of the movie 
- **2.genre**    : Primary genre (e.g., Action, Comedy, Drama) 
- **3.release_year** :  Year the movie was released 
- **4.vote_average**  : Average user rating (1–10 scale) 
- **5.vote_count**   :    Number of user votes 
- **6.popularity** :   Popularity score (based on views, likes, etc.) 
- **7.original_language**  : Original language (e.g., 'en' for English) 
- **8.overview**      : Short plot summary 
- **9.runtime**  :  Duration in minutes 
- **10.tagline** :  Promotional tagline 
- **11.production company** : Name of the production company 
- **12.budget**        : Total budget for the movie 
- **13.profit** :   Calculated as revenue - budget 

## 🛠️ Libraries Used

- **pandas** – Data manipulation and loading  
- **numpy** – Numerical operations  
- **matplotlib** – Basic plotting  
- **seaborn** – Statistical visualizations  
- **plotly** – Interactive visualizations  
- **ydata-profiling** – For generating profiling reports  

## 📈 Steps in EDA

### 1. Data Import & Setup
- Loaded the dataset using **pandas**
- Imported required libraries

### 2. Data Cleaning
- Handled missing values and removed duplicates
- Converted **release_date** to datetime format
- Created a new column for **profit**

### 3. Bivariate & Multivariate Analysis
- Analyzed relationships between release year and popularity
- Identified top-rated and most-voted movies
- Visualized correlation between **vote_count**, **budget**, and **revenue**
- Explored how genre and runtime affect movie success

## 💡 Recommendations
- Focus production and marketing on high-rated, high-popularity genres (e.g., action, drama, thriller).
- Track how genre popularity shifts over time to predict future audience interests.
- Understand audience sentiment to guide tone, messaging, and emotional appeal in content.
- Normalize budget/revenue for inflation-adjusted insights.
- People loved to watch sequence movies because actors are known and excited to see what will happens next.
- Target runtimes within this window to maximize viewer satisfaction and retention while maintaining profitability in theaters and streaming platforms.
- Study their production strategies and storytelling frameworks.























