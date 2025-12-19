# Netflix Movies and TV Shows Analysis

![Netflix Logo](https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg)

---

## Project Overview

This project explores the Netflix Movies and TV Shows dataset to uncover insights about content availability, trends, and distributions on the platform. Using Python, pandas, and visualization libraries, this analysis demonstrates **data cleaning, exploratory data analysis (EDA), and visualization best practices**.  

**Key Goals:**  
- Understand the distribution of Movies vs TV Shows  
- Identify top countries producing Netflix content  
- Analyze common content ratings  
- Explore duration trends for Movies and TV Shows  
- Track the number of titles added over the years  

This project is organized for clarity and reproducibility, making it perfect for showcasing **data analysis skills on GitHub or a CV**.

---

## Project Structure

```
Netflix-EDA/
├── data/                   # CSV files
│   └── netflix_titles.csv       # Original dataset
│   └── netflix_titles_cleaned.csv  # Cleaned dataset
├── notebooks/              # Jupyter notebook
│   └── netflix_analysis.ipynb
├── images/                 # Saved plots
├── README.md               # Project overview
├── requirements.txt        # Python dependencies
└── .gitignore              # Ignore unnecessary files
```

---

## Dataset

**Source:** [Kaggle – Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)  

**Description:**  
- 8,807 entries (Movies and TV Shows)  
- 12 columns including: `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, and `description`  

**Sample Columns:**
- `type`: Movie or TV Show  
- `duration`: Minutes for movies, Seasons for TV shows  
- `rating`: Content rating (e.g., TV-MA, PG-13)  

---

## Features

1. **Data Cleaning**  
   - Handle missing values in categorical columns (`director`, `cast`, `country`, `rating`)  
   - Convert `date_added` to datetime  
   - Split `duration` into numeric value and unit (`duration_int`, `duration_unit`)  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of Movies vs TV Shows  
   - Top countries producing content  
   - Most common content ratings  
   - Duration trends for Movies and TV Shows  
   - Number of titles added per year  

3. **Visualizations**  
   - All plots saved in the `images/` folder for easy reference  

4. **Cleaned Data**  
   - Saved as `data/netflix_titles_cleaned.csv` for future analysis  

---

## How to Run

1. Clone the repository:  
```bash
git clone <your-repo-url>
```

2. Install dependencies (if not already installed):  
```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter Notebook:  
```bash
jupyter notebook notebooks/netflix_analysis.ipynb
```

4. Run the notebook cells to reproduce the analysis and plots.

---

## Key Insights

- **Movies dominate Netflix content**, but TV Shows have been increasing in recent years.  
- **United States** produces the most Netflix titles, followed by **India** and the **United Kingdom**.  
- Most content is rated **TV-MA** and **TV-14**.  
- Movie durations mostly cluster around **90-120 minutes**, while TV Shows have **1-3 seasons** typically.  
- Content added per year shows a **steady increase**, peaking around **2019-2021**.

---

## Folder of Saved Plots

- `images/movies_vs_tv.png` – Movies vs TV Shows distribution  
- `images/top_countries.png` – Top 10 producing countries  
- `images/top_ratings.png` – Most common ratings  
- `images/duration_distribution.png` – Duration analysis  
- `images/titles_added_per_year.png` – Titles added per year  

---

## Why This Project is Cool

- Demonstrates **real-world data cleaning and analysis skills**  
- Well-structured and **CV-ready**  
- Saves outputs in organized folders (`images/` and `data/`)  
- Fully reproducible and easy for recruiters to explore  

---

## Author

**Daniel Akinbankole**  
- Python | Data Analysis | EDA | Visualization  
```

