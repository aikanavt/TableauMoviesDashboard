# 🎬 Movie Popularity vs Profit Dashboard

## Overview
This Tableau dashboard explores whether a movie's **popularity** is correlated with its **profitability**, using data from the **TMDB 5000 Movie Dataset**. The objective is to visually assess if higher popularity scores lead to higher profits, or if other factors drive box office success.

---

## 📂 Data Source
- **Dataset:** [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-dataset)
- **Fields Used:**
  - `popularity`
  - `budget`
  - `revenue`
  - **Calculated Field:** `Profit = [revenue] - [budget]`
  - `genres`, `release_date`, `title` (for filtering and categorization)

---

## 📊 Dashboard Features
- **Scatter Plot:**  
   Displays the relationship between **Popularity** and **Profit**.
   - Each point = 1 movie
   - Color-coded by `genre`
   - Includes a **trend line** to visualize correlation

- **Filters:**
  - Year range selector
  - Genre filter
  - Country filter

- **Additional Visuals:**
  - Top 10 Grossing Movies
  - Top 10 Most Popular Movies
  - Popularity Trends Over Time

---

## 🔍 Key Insight
> While popular movies often perform well financially, the dashboard reveals that **popularity does not always guarantee high profit**. Factors such as production costs, genre, and market trends significantly influence profitability.

---

## 🚀 How to Use
1. Adjust the **Year** and **Genre** filters to explore different subsets of movies.
2. Hover over points in the scatter plot to see detailed movie info.
3. Use outlier filters to zoom into typical performance ranges.
4. Review top movie lists for context on blockbuster successes.

---

## ⚠️ Notes
- Some movies may reflect inaccurate profits due to missing or zero values in `budget` or `revenue`.
- Outliers (e.g., mega-budget films) can skew visual interpretation—use filters to manage visibility.

---

## 🔗 View the Dashboard
You can access the interactive dashboard here:  
[**Movie Popularity vs Profit Dashboard**](https://public.tableau.com/views/Movies_17455095650820/MoviesDashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📅 Last Updated
April 2025
