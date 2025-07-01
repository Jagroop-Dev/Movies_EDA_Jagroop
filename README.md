# Movie Data Exploratory Data Analysis (EDA)

This project explores a dataset of movies, focusing on key aspects such as **budget**, **revenue**, **popularity**, and **vote count**. The goal is to provide an in-depth understanding of trends in the movie industry, highlighting patterns, correlations, and interesting outliers.

## Table of Contents
- [Introduction](#introduction)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Budget vs Revenue](#budget-vs-revenue)
  - [Top Genres by Average Revenue](#top-genres-by-average-revenue)
  - [Correlation Analysis](#correlation-analysis)
  - [Outliers: Movies with Zero Revenue](#outliers-movies-with-zero-revenue)
- [In-Depth Movie Analysis](#in-depth-movie-analysis)
  - [Movie 1: Avatar](#movie-1-avatar)
  - [Movie 2: John Carter](#movie-2-john-carter)
- [Key Insights & Conclusions](#key-insights-conclusions)

## Introduction

This project aims to explore various aspects of movie performance using a dataset containing key features such as **budget**, **revenue**, **genres**, and more. The analysis uncovers trends and patterns in the industry, allowing us to understand how certain variables, like budget and genre, impact a movie's success.

## Data Cleaning

The data was initially cleaned by addressing missing values, converting JSON columns (such as genres, production companies, and spoken languages) into usable formats, and filtering out irrelevant rows to ensure high-quality data for analysis.

## Exploratory Data Analysis (EDA)

### **Budget vs Revenue**
A scatter plot with a regression line shows the relationship between **budget** and **revenue**, highlighting that while higher budgets tend to result in higher revenue, there are diminishing returns for extremely high budgets.

### **Top Genres by Average Revenue**
A bar plot was used to identify the top-performing movie genres by average revenue. **Animation** topped the list, showing its strong financial performance compared to other genres like **Comedy** and **Mystery**, which had lower average revenues.

### **Correlation Analysis**
A heatmap was used to explore the relationships between key movie variables. Strong correlations were observed between **budget** and **revenue**, and **popularity** and **vote count**, while **vote average** had weaker correlations with other variables.

### **Outliers: Movies with Zero Revenue**
A quick analysis revealed **1,427 movies with zero revenue**. These movies likely suffer from **budgeting errors**, **data issues**, or had **little to no commercial success**. Including these movies can skew average revenue figures, and they may be excluded or treated separately for more accurate analysis.

## In-Depth Movie Analysis

### **Movie 1: Avatar**
- **Why Selected**: "Avatar" is one of the highest-grossing films of all time and offers a clear example of how a massive budget ($237 million) led to extraordinary box office success ($2.79 billion).
- **In-Depth Observation**: The massive success of "Avatar" was driven by cutting-edge technology, a unique storyline, and a global fanbase, proving that high budgets can lead to exponential returns when paired with the right content.
- **Comparison**: Compared to other sci-fi blockbusters, "Avatar" outperformed films like "The Dark Knight" and "Star Wars: The Force Awakens" due to technological innovation and its broad appeal.

### **Movie 2: John Carter**
- **Why Selected**: "John Carter" had an enormous budget ($250 million) but failed to generate significant revenue, making it a compelling case study of a high-budget movie that underperformed.
- **In-Depth Observation**: Despite a large budget, "John Carter" struggled in terms of marketing, audience engagement, and critical reception, showing that even large investments don’t guarantee success.
- **Comparison**: When compared to other action-adventure movies with similar budgets, "John Carter" underperformed significantly, suggesting that factors like poor marketing or weak storytelling can severely impact a film's financial performance.

## Key Insights & Conclusions

- **Budget-Adjusted Revenue**: While there is a strong correlation between budget and revenue, calculating profitability (revenue - budget) shows that many high-budget movies do not perform as expected, suggesting diminishing returns for extremely large budgets. More efficient budget allocation is needed to maximize profitability.
  
- **Outliers**: Movies with **zero revenue** were identified as outliers in the dataset. These films either experienced commercial failure or contain data issues. Excluding or treating these movies separately will yield more accurate insights into industry trends.

- **Top Genres**: Certain genres, such as **Animation**, consistently outperform others in terms of revenue. This suggests that investing in certain genres can be a lucrative strategy.

This analysis underscores the importance of **data quality**, **budget efficiency**, and **targeted genre selection** when producing films. Future studies could explore additional factors, such as **marketing efforts**, **critical reviews**, and **audience ratings**, to further enhance the understanding of what drives box office success.

---

## How to Run

1. Clone the repository:
    ```
    git clone <repository_url>
    ```

2. Run the Jupyter Notebook for the full analysis.

---

### **Note**: This project uses data obtained from publicly available sources. All visualizations and analysis are based on the data provided in the dataset.

---
