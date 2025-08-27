# Netflix Data Analysis

A data-driven exploration of Netflix’s content catalog — uncovering trends in content types, release timing, genres, countries of origin, and more.

---

##  Overview  
This project delves into Netflix’s movie and TV show data using Python (Pandas, NumPy, Matplotlib, Seaborn). The goal is to clean the data, perform exploratory data analysis (EDA), and extract meaningful insights into content distribution and trends over time.

---

##  Dataset  
- **Primary data source:** A file named `netflix_titles.csv` located in the `dataset/` folder.  
- **Key fields include:** `show_id`, `title`, `type`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`.

---

##  Project Structure  
Netflix-Data-Analysis/
├── dataset/ 
├── src/ 
│ └── analysis.ipynb
├── result/ 
├── README.md 
└── requirements.txt


---

##  Setup & Installation  
1. Clone the repository:  
   ```bash
   
   git clone https://github.com/aary20/Netflix-Data-Analysis.git

2. Navigate into the directory and install dependencies:
   ```bash
   
   cd Netflix-Data-Analysis
   pip install -r requirements.txt
3. Launch the analysis notebook:
   ```bash
   
   jupyter notebook src/analysis.ipynb

##  Analysis Highlights

- Content Distribution: Comparison of movies vs. TV shows over time.

- Genre Trends: Identification of the most common genres and how they evolve.

- Country Contributions: Highlighting top content-producing countries like the US, India, UK.

- Release Patterns: Trends in content addition by month or year.

- Ratings & Demographics: Analysis of content ratings (TV-MA, TV-14, etc.) and audience targeting.


## Result
<img width="400" height="250" alt="movie_duration_histogram" src="https://github.com/user-attachments/assets/e5a89f05-1a44-445e-b3e0-29c634c37e0e" />
<img width="600" height="250" alt="movies_tv_shows_comparison" src="https://github.com/user-attachments/assets/922b605b-30dc-474b-8d89-68c7f7c5cc90" />
<img width="400" height="250" alt="movies_vs_tvshows" src="https://github.com/user-attachments/assets/15545252-3e5d-4164-a4cc-30583bf064ec" />
<img width="400" height="250" alt="release_year_Scatter" src="https://github.com/user-attachments/assets/dbb478fe-fd27-4bde-8bc6-60703423b674" />
<img width="400" height="250" alt="top10_countries" src="https://github.com/user-attachments/assets/2e5d55da-d367-4fb3-b7a1-563d8c5c8f9e" />
