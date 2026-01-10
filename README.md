# 🎬 Pandas Analysis of Netflix Shows and Movies

## 📚 Table of Contents
- **Project Overview**
- **Data Overview** 
- **Structure Explanation** 
- **How to Run** 
- **Pandas Analysis**
- **What I have learned?**
- **Technical Details**
- **Author**

## 🔎 Project Overview

The goal of this project is to analyze Netflix shows and movies data using Pandas. Before the analysis dataset was cleaned in Pandas. The project takes a closer look at average duration of Netflix's productions, the number of Polish movies and shows released over the years and other.


## 📂 Data Overview

### Overview

The dataset consists of **one CSV file**: 

- `netflix_titles.csv` – contains unique id, title, director, cast, rating, etc.

**Data source:** [Kaggle Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) 

### Data Cleaning

The dataset was cleaned in the [0_data_cleaning.ipynb](python_files/0_data_cleaning.ipynb) file: one column was dropped, null values were replaced, duplicates were removed, date column was formatted to the correct type, blank spaces from rows were removed.

New dataframes were created and saved to the new csv files in **data_after_cleaning** folder.

## 🧱 Structure Explanation

| Folder / File | Description |
|----------------|-------------|
| **data/** | Original data file, files saved after data cleaning and analysis files outcomes |
| **python_files/** | Python files used in the project |
| **images/** | Matplotlib charts used to visualize analysis |
| **README.md** | Project overview 

---

## ⚙️ How to Run

1. Download the entire folder
2. Install Jupyter Notebook or VS Code (with the required extensions)
3. Update all directory paths in all files (USER_PATH variable)

## 📈 Pandas Analysis

### 1. Actor and actress appearances in shows and movies

**Notebook**: [Actors Appearances](python_files/1_actor_and_actress_appearances.ipynb)

**Visualization:**

![chart1](/images/chart1.png)

**Insights:**

### 2. How Many Polish Movies and Shows has Netflix released (over the years)?

**Notebook**: [Movies and Show Release](python_files/2_polish_movies_and_shows.ipynb)

**Visualization:**

![chart1](/images/chart2.png)

**Insights:**

### 3. Average duration of movies and show by categories 

**Notebook**: [Average Duration](python_files/3_avg_duration_analysis.ipynb)

**Visualization:**

![chart1](/images/chart3.png)

**Insights:**

### 4. American actors and directors who work together most often

**Notebook**: [Actors and Director](python_files/4_american_actors_and_directors.ipynb)

**Visualization:**

| Duo                   | Number |
|-----------------------|----------------------------|
| PenaVega & Rodriguez  | 5                          |
| Trejo & Rodriguez     | 4                          |
| Keitel & Scorsese     | 4                          |
| Sabara & Rodriguez    | 4                          |
| Mewes & Smith         | 4                          |
| Ford & Spielberg      | 4                          |
| Eastwood & Eastwood   | 4                          |
| Sandler & Brill       | 4                          |
| Blair & Saulnier      | 4                          |
| Wayans & Tiddes       | 4                          |


**Insights:**

## 💪 What I have learned?

## 🖥️ Technical Details

- **Python Libraries:** Pandas, Matplotlib and other
- **Environment:** Visual Studio Code
- **Data source:** [Kaggle Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) 


## ✒️ Author

- **Author:** Mateusz Bochenek
- **Mail:** matbochenek42@gmail.com
- **GitHub link:** https://github.com/matbochenek42
- **LeetCode link:** https://leetcode.com/u/SmO7BWmsiz/