STREAMING ANALYSIS: ETL + Power BI

This project presents a complete analysis of movies and TV shows available on major streaming platforms, covering all stages of the data lifecycle: Python ETL, data modeling, exploratory data analysis, and the creation of professional dashboards in Power BI.



🔧 ETL (Python)

The data pipeline was built in a modular structure and includes:

* Import of public datasets (Catalog + IMDb)
* Standardization of titles and production years
* Normalization of genres and platform indicators
* Integration with IMDb using a title + year key
* Removal of inconsistencies and duplicates
* Creation of derived metrics (quality, popularity, decade, etc.)
* Generation of BI-ready fact and dimension tables

The full code is available in the notebooks/ folder.



📈 Dashboards (Power BI)

The dashboard is organized into 6 pages:

1. Cover
2. Overview — catalog distribution and average quality
3. Catalog \& Evolution — analysis based on production year
4. Genres — presence, average rating, and audience engagement
5. Quality \& Popularity — ratings, votes, and content type
6. Key Insights — executive summary of the analysis



⭐ Key Results

* More than 15,000 titles analyzed
* TV shows have higher average ratings than movies
* Drama is the most common genre
* Documentary, Biography, and History have the highest average ratings
* Titles with more votes tend to also have higher ratings
* Strong production growth between 2016 and 2020



📂 Repository Structure

/

&nbsp;├── background/

&nbsp;├── dashboard/

&nbsp;├── data/

&nbsp;│    ├── raw/

&nbsp;│    └── processed/

&nbsp;├── docs/

&nbsp;├── img/

&nbsp;├── notebook/

&nbsp;├── README.md

&nbsp;└── README-en.md



🛠 Technologies Used

* Python (Pandas, NumPy, Jupyter)
* Power BI Desktop
* IMDb Datasets (TSV)
* Public streaming datasets (CSV)



📬 Contact

If you’d like to talk about the project or suggest improvements, feel free to reach out!

