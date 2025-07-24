# media_trends
# Analysis of Trending Movies and TV Shows

## 📖 Overview

This project performs an in-depth analysis of a dataset containing trending movies and TV shows. The primary goal is to uncover insights into what drives media popularity, how audience ratings vary across different categories, and to identify trends over time.

The analysis is conducted using Python with libraries such as Pandas, Seaborn, and SciPy for data manipulation, visualization, and statistical testing. The key findings are also summarized in an interactive Tableau dashboard for a high-level overview.

---

## 📊 Dataset

The dataset used for this analysis is `trending.csv`, a collection of popular media with the following key features:
* `original_title`: The title of the movie or TV show.
* `popularity`: A score indicating the media's popularity.
* `vote_average`: The average user rating.
* `vote_count`: The number of votes received.
* `release_date`: The release date of the media.
* `media_type`: The type of media (Movie or TV).
* `original_language`: The original language of the media.

---

## 🔎 Analysis & Key Questions

The analysis, detailed in the `MediaTrends.ipynb` Jupyter Notebook, seeks to answer the following questions:

1.  **Correlation:** Is there a statistically significant relationship between a movie's popularity and its average vote?
2.  **Performance by Language:** Do films in certain languages receive higher average ratings than others?
3.  **Media Type Comparison:** How do movies and TV shows compare in terms of audience ratings, and is the difference statistically significant?
4.  **Time Analysis:** Are there discernible trends in the popularity of media released over time?

---

## 🛠️ Tools & Libraries

* **Data Analysis:** Python
    * **Pandas:** For data manipulation and cleaning.
    * **Seaborn & Matplotlib:** For data visualization.
    * **SciPy:** For statistical analysis, including the independent t-test.
* **Dashboarding:** Tableau Public

---

## ✨ Key Findings

* **Popularity vs. Rating:** A linear regression analysis revealed an R-squared value of **0.004**, indicating no meaningful linear correlation between a title's popularity and its average rating.
* **Language Performance:** While the dataset is predominantly English (75%), **Japanese-language media had the highest average rating** among all languages represented.
* **Movie vs. TV Show Ratings:** An independent t-test showed a **statistically significant difference** between the average ratings of movies and TV shows, with TV shows having a slightly higher average rating.
* **Popularity Over Time:** A time-series analysis showed significant fluctuations in the popularity of trending media, with a notable peak in late 2022.

---

## 📈 Tableau Dashboard

A summary of the key findings was visualized in an interactive Tableau dashboard. This provides a high-level, at-a-glance view of the most important insights from the analysis.

![Tableau Dashboard for Trending Movies Analysis](http://googleusercontent.com/file_content/0)

The dashboard highlights:
* Key performance indicators (KPIs) such as the overall average score and total votes.
* A comparison of average ratings by language.
* A time-series plot showing how audience popularity has changed over the years.
* A scatter plot visualizing the relationship between critic ratings and audience popularity.

---

## 🚀 How to Run This Project

To replicate this analysis, please follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```
2.  **Install the required libraries.** It is recommended to use a virtual environment.
    ```bash
    pip install pandas seaborn matplotlib scipy jupyter
    ```
3.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
4.  **Open and run the `MediaTrends.ipynb` notebook** to see the full analysis. The `trending.csv` dataset should be in the same directory.

