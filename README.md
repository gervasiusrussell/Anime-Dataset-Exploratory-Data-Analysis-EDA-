# 🎥 Anime Dataset Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on a dataset of top anime series, focusing on patterns across **anime type, episodes, sources, ratings, and popularity metrics** such as members, favorites, and recommendations.

The goal is to understand how different factors relate to anime popularity and audience reception.

---

## 📂 Dataset

* Source: *Custom cleaned dataset* (`top_animes_after_cleaning.csv`)
* Cleaned to remove unnecessary columns and handle missing values (e.g., replacing missing licensors with the mode).
* Focused on top **1000 anime entries** for analysis.

---

## 🛠 Tools & Libraries

* **R Programming**
* `tidyverse` – data manipulation
* `ggplot2` – visualization
* `plotly` – interactive plots
* `corrplot` – correlation analysis

---

## 📂 Project Workflow

1. **Data Cleaning & Preprocessing**

   * Removed unused columns.
   * Replaced `"None found, add some"` in `Licensors` with `NA`.
   * Filled missing values in `Licensors` with the **mode**.
   * Dropped remaining rows with missing values.

2. **Exploratory Data Analysis (EDA)**

   * Boxplots: `Type` vs `Members` distribution.
   * Mean `Score` comparison by `Source`.
   * Correlation analysis across numerical variables (`Favorites`, `Recommended`, etc.).
   * Interactive scatterplots for engagement features.
   * Stacked bar plots: `Rating` vs `Score` distribution by anime `Type`.
   * Episode frequency analysis.

---

## 📊 Key Insights

* **Anime Type**: Distribution of members varies significantly depending on type (e.g., TV, Movie, OVA).
* **Source Material**: Anime based on **manga and light novels** tend to have higher average scores.
* **Correlations**: Strong correlations exist among audience engagement metrics (favorites, recommendations, scores).
* **Ratings**: Audience reception differs across rating categories, with certain types dominating specific rating groups.
* **Episodes**: Popular shows vary widely in episode counts, though frequency distributions reveal clustering.

---

## 📊 Sample Visualizations

* Boxplots: Popularity (`Members`) across anime types.
* Bar plots: Average score by source material.
* Correlation heatmap of audience metrics.
* Interactive scatterplots (`Favorites` vs `Recommended`).
* Stacked bar plots of rating distributions.
* Line charts of episode frequency.

---

## 🚀 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/yourusername/anime-eda.git
   ```
2. Open the R project / R Markdown file in RStudio.
3. Install required libraries:

   ```R
   install.packages(c("tidyverse", "ggplot2", "plotly", "corrplot"))
   ```
4. Run the `.Rmd` file to generate the **EDA report**.

---

## 🔍 Keywords

`Data Science` · `EDA` · `Anime Dataset` · `R` · `Visualization` · `Interactive Plots`

---

📌 *This project demonstrates skills in **data cleaning, exploratory analysis, and visualization** using both static (`ggplot2`) and interactive (`plotly`) methods.*
