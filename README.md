# 🎬 Pandas Analysis of Netflix Shows and Movies

## 📚 Table of Contents
- **Project Overview**
- **Data Overview** 
- **Structure Explanation** 
- **How to Run** 
- **Pandas Analysis**
- **What I Learned**
- **Technical Details**
- **Author**

## 🔎 Project Overview

The goal of this project is to analyze Netflix TV show and movie data using Pandas. The project takes a closer look at the average duration of Netflix productions, the number of Polish movies and TV shows released over the years and so on.

## 📂 Data Overview

### Overview

The dataset consists of **one CSV file**: 

- `netflix_titles.csv` – contains a unique ID, title, director, cast, rating, etc.

**Data source:** [Kaggle Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) 

### Data Cleaning

The dataset was cleaned in the [0_data_cleaning.ipynb](python_files/0_data_cleaning.ipynb) file. One column was dropped, null values were handled, duplicates were removed, the date column was converted to the correct type, unnecessary blank spaces were removed.

New dataframes were created and saved to the new CSV files in **data_after_cleaning** folder.

## 🧱 Structure Explanation

| Folder / File | Description |
|----------------|-------------|
| **data/** | Original data file, cleaned data files and analysis results |
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

Anupam Kher is the actor with the most appearances in Netflix productions (over 40). However, the most popular actor on this list is definitely Samuel L. Jackson with over 20 appearances. Most actors with a high number of appearances appear more often in movies than in TV shows, with the exception of Takahiro Sakurai and Yuki Kaji.

### 2. How Many Polish Movies and TV Shows has Netflix released (over the years)?

**Notebook**: [Movies and TV Show Release](python_files/2_polish_movies_and_shows.ipynb)

**Visualization:**

![chart2](/images/chart2.png)

**Insights:**

Netflix has released over a dozen Polish productions since 2016. The peak was in 2019 with 13 movies and 3 TV shows. In 2020 and 2021 the total number of Polish producitons decreased compared to the previous year, likely due to the COVID pandemic. It seems that Netflix is more interested in making movies than TV shows in Poland. 

### 3. Average duration of movies and TV shows by categories 

**Notebook**: [Average Duration](python_files/3_avg_duration_analysis.ipynb)

**Visualization:**

![chart3](/images/chart3.png)

**Insights:**

The correlation between the average duration of movies and TV shows across specific categories (Horror, Comedies, Sci-Fi & Fantasy, Thrillers, Dramas, and Action & Adventure) is low. TV shows rarely last longer than three seasons and the average movie duration ranges from 98 to 114 minutes.

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

PenaVega & Rodriguez are the duo of actor and director who worked together most often, with five productions released. Other duos on the list share 4 collaborations. The most unusual duo is Clint Eastwood who is known for acting in his own productions. 

## 💪 What I Learned

I learned multiple Python skills, mainly Pandas and Matplotlib skills such as: accessing data, merging dataframes, creating pivot tables, aggregation, data visualization.

## 🖥️ Technical Details

- **Python Libraries:** Pandas, Matplotlib and other
- **Environment:** Visual Studio Code
- **Data source:** [Kaggle Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) 


## ✒️ Author

- **Author:** Mateusz Bochenek
- **Mail:** matbochenek42@gmail.com
- **GitHub link:** https://github.com/matbochenek42
- **LeetCode link:** https://leetcode.com/u/SmO7BWmsiz/
