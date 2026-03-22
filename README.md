# 🎬 Netflix Movies EDA (1990s)

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on Netflix movie data to understand trends in movies released during the 1990s. The analysis focuses on movie duration, genre distribution, and yearly release patterns.

---

## 🎯 Objectives
- Analyze movies released between 1990 and 1999
- Identify the most frequent movie duration
- Count short action movies (< 90 minutes)
- Understand trends in movie releases over the years
- Explore genre distribution

---

## 🛠️ Tools & Technologies
- Python 🐍
- Pandas 📊
- Matplotlib 📈
- Jupyter Notebook

---

## 📂 Dataset Information

The dataset `netflix_data.csv` contains the following columns:

| Column        | Description                      |
|--------------|----------------------------------|
| show_id      | Unique ID of the show           |
| type         | Type of show (Movie/TV Show)    |
| title        | Title of the show               |
| director     | Director of the show            |
| cast         | Cast of the show                |
| country      | Country of origin               |
| date_added   | Date added to Netflix           |
| release_year | Year of release                 |
| duration     | Duration of the show (minutes)  |
| description  | Description of the show         |
| genre        | Genre of the show               |

---

## 🔍 Steps Performed

1. **Data Loading**
   - Loaded dataset using Pandas

2. **Data Filtering**
   - Selected only movies
   - Filtered data for the 1990s (1990–1999)

3. **Analysis**
   - Found most frequent movie duration
   - Counted short action movies
   - Calculated average duration
   - Compared long vs short movies

4. **Visualization**
   - Movies per year (trend analysis)
   - Genre distribution
   - Duration distribution

---

## 📊 Key Insights

- Most movies have a duration around **90–100 minutes**, indicating a standard runtime.
- Short action movies (< 90 minutes) are relatively fewer compared to longer ones.
- Movie releases increased towards the **late 1990s**.
- **Drama and Action** are the most dominant genres.
- Majority of movies are longer than 90 minutes.

---

## 📁 Project Structure

```
Netflix_EDA_Project/
│── Netflix_EDA_Project.ipynb
│── netflix_data.csv
│── README.md
```

---

## 🚀 How to Run

1. Clone the repository :
    git clone https://github.com/Narasaipriya/netflix-eda-project

2. Open Jupyter Notebook :
    jupyter notebook
   
4. Run all cells in :
    Netflix_EDA_Project.ipynb
   
---

## 💡 Future Improvements
- Analyze director-wise trends
- Country-based movie analysis
- Recommendation system (basic ML)
- Interactive dashboards using Power BI or Tableau

---

## 🙌 Author
**Sai Priya Nara**

---

## ⭐ Acknowledgment
This project is inspired by Netflix dataset analysis for learning data analytics concepts.
