# Popular Movies Dataset

# Project Overview
**The Popular Movies Dataset EDA project focuses on exploring and analyzing a dataset containing information about 1,000 popular movies collected from TMDB (The Movie Database). The goal is to extract meaningful insights from the data related to genres, ratings, popularity, and viewer engagement.**

# Important Libraries
**1.pandas**       :  Data manipulation and Data loading .          

**2.numpy**       :  Numerical operations .                   

**3.matplotlib** :  Basic plotting .                          

**4.seaborn**  :     advanced Statistical visualizations .              

**5.plotly**    :    Interactive visualizations .              

**6.ydata-profiling** : create profile report. 

# Features
- **1.title**:	Name of the movie
- **2.genre** : 	Primary genre of the movie (e.g., Action, Comedy, Drama)
- **3.release_year** : 	Year the movie was released
- **4.vote_average** : 	Average user rating (typically on a scale from 1 to 10)
- **5.vote_count** : 	Total number of votes submitted by users
- **6.popularity** : 	Popularity score assigned by TMDB (based on views, likes, etc.)
- **7.original_language** : 	Language in which the movie was originally made (e.g., 'en' for English)
- **8.overview** : 	Short description or summary of the movie plot
- **9.runtime**	Duration of the movie in minutes
- **10.tagline** : 	Catchy promotional phrase used for the movie
- **11.production company** : Name of production company.
- **12.overview** : Get short info about movie.
- **13.budget** : Total budget for movie.

# steps in EDA
- Data Import & Setup
  - Loaded the dataset using Pandas
  - Imported all required libraries (NumPy, Seaborn, Matplotlib, Plotly, YData Profiling)
- Data Cleaning:
  - Handled missing and duplicate values.
  - Converted data types.
  - convert the release_date to datetime.
  - create extra column for profit.
- Bivariate & Multivariate Analysis:
  - Relationship between year and popularity
  - also find this relation ship between  most popular movie by there vote average
  - Find top most popular movies.
  - Find correlation between vote_count,revenue and budget column.
# Recommendations
- Focus production and marketing on high-rated, high-popularity genres (e.g., action, drama, thriller).
- Track how genre popularity shifts over time to predict future audience interests.
- Understand audience sentiment to guide tone, messaging, and emotional appeal in content.















