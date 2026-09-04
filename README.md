# Netflix TV Shows Data Analysis with Python

## 📌 Project Overview

This project analyzes a dataset of Netflix TV Shows using Python to discover trends, patterns, and insights related to TV show releases, countries, languages, ratings, popularity, votes, and duration.

The project focuses on data cleaning, exploratory data analysis (EDA), feature engineering, statistical analysis, and data visualization.

## 🎯 Objectives

* Analyze the Netflix TV Shows dataset
* Clean and prepare the data for analysis
* Explore TV show release trends
* Identify the top countries producing TV Shows
* Analyze the most common languages
* Understand rating distribution
* Analyze show popularity and vote counts
* Explore TV show duration and number of seasons
* Identify relationships between numerical variables
* Create meaningful visualizations and insights

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📊 Dataset

The dataset contains approximately 16,000 Netflix TV Show records with information such as:

* Show ID
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Language
* Popularity
* Vote Count

## 🔍 Analysis Performed

### Data Cleaning

* Removed duplicate records
* Converted date columns into datetime format
* Handled missing values
* Standardized categorical data
* Created additional analytical columns

### Feature Engineering

Created features including:

* Added Year
* Added Month
* Added Month Name
* Release Decade
* Duration Number
* Duration Unit

### Exploratory Data Analysis

The project analyzes:

* TV Shows by release year
* TV Shows by release decade
* TV Shows added to Netflix by year
* Top countries producing TV Shows
* Top languages
* Rating distribution
* Most popular TV Shows
* TV Shows with the highest vote counts
* Most common number of seasons
* Popularity vs Vote Count relationship

## 📈 Visualizations

The project uses multiple visualizations including:

* Line Charts
* Bar Charts
* Scatter Plots

These visualizations make it easier to identify trends and patterns within the dataset.

## 💡 Key Insights

The analysis helps identify:

* Major TV Show producing countries
* Most common languages
* Popular rating categories
* Release trends over time
* Netflix content addition trends
* Highly popular TV Shows
* Shows receiving the most votes
* Common TV Show durations
* Relationship between popularity and vote count

## 📁 Project Structure

```text
netflix-tv-shows-data-analysis/
│
├── data/
│   └── netflix_tv_shows.csv
│
├── notebook/
│   └── Netflix_TV_Shows_Analysis.ipynb
│
├── visuals/
│   ├── release_trend.png
│   ├── country_analysis.png
│   ├── language_analysis.png
│   ├── rating_analysis.png
│   ├── popularity_analysis.png
│   └── duration_analysis.png
│
├── README.md
└── requirements.txt
```

## 🚀 How to Run

1. Clone the repository.
2. Install the required libraries.
3. Open the Jupyter Notebook.
4. Run the notebook cells sequentially.

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## 📌 Project Outcome

This project demonstrates practical skills in Python-based data analysis, including data cleaning, exploratory data analysis, feature engineering, statistical analysis, and visualization.

---

**Author:** Malik Muhammad Ali Aslam
