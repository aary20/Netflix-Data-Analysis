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
