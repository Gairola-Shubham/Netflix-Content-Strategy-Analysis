# Netflix Content Strategy Analysis

## Overview
This project performs Exploratory Data Analysis (EDA) on Netflix's content dataset to understand its content distribution, growth trends, genre popularity, and platform strategy. The analysis focuses on extracting meaningful insights using data cleaning, feature engineering, and visualization techniques.

This project demonstrates practical use of Python for analyzing real-world datasets and identifying patterns in streaming platform content.

---

## Dataset
- Dataset: Netflix Titles Dataset
- Total Records: ~7,800 titles
- Features include:
  - title
  - type (Movie / TV Show)
  - director
  - cast
  - country
  - date_added
  - release_year
  - rating
  - duration
  - listed_in (genre)
  - description

---

## Objectives

The main goals of this analysis are:

- Analyze distribution of Movies and TV Shows
- Identify content growth trends over time
- Find most common genres
- Analyze movie durations and TV show seasons
- Identify top contributing countries
- Analyze ratings distribution
- Measure how quickly content is added after release
- Visualize content trends using plots and charts

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading
- Loaded dataset using Pandas
- Inspected structure using `.head()`, `.info()`, `.describe()`

### 2. Data Cleaning
- Handled missing values in director, cast, and country
- Converted date_added to datetime format
- Removed invalid or incomplete records where necessary

### 3. Feature Engineering
Created new useful features such as:

- year_added
- month_added
- content_age (difference between release year and added year)

---

### 4. Exploratory Data Analysis

Performed analysis on:

- Movies vs TV Shows distribution
- Content added per year
- Top genres
- Content duration distribution
- Country-wise content production
- Ratings distribution
- Release trends over time

---

### 5. Visualization

Used visualization techniques such as:

- Bar plots
- Line charts
- Histograms
- Count plots
- Word Cloud

These visualizations help understand content patterns clearly.

---

## Key Insights

- Movies make up the majority of Netflix content
- Content additions increased significantly after 2015
- United States is the largest content contributor
- International Movies are among the most common genres
- Most movies are between 80 and 120 minutes
- Most content is added shortly after release, indicating strong original content production

---

## Project Structure

```
Netflix-Content-Strategy-Analysis/
│
├── Netflix's Content Strategy.ipynb
├── netflix_titles.csv
└── README.md
```

---

## How to Run

1. Clone the repository

```
git clone https://github.com/your-username/Netflix-Content-Strategy-Analysis.git
```

2. Install required libraries

```
pip install pandas numpy matplotlib seaborn wordcloud
```

3. Open Jupyter Notebook

```
jupyter notebook
```

4. Run the notebook

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Data Visualization
- Python Programming
- Real-world data analysis

---

## Future Improvements

- Build recommendation system
- Create dashboard using Streamlit or Power BI
- Apply machine learning for prediction
- Perform deeper genre and country analysis

