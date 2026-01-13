# 🎮 Video Game Sales Analysis

## 📌 Project Overview
This project analyzes historical video game sales data to identify market trends, regional user preferences, platform performance, and genre popularity. The analysis combines exploratory data analysis (EDA), data visualization, and statistical hypothesis testing.

## 📊 Dataset Description
The dataset contains information about video games released across multiple platforms and regions.

**Main columns:**
- Name — Game title
- Platform — Gaming platform
- Year_of_Release — Release year
- Genre — Game genre
- NA_sales — Sales in North America (million USD)
- EU_sales — Sales in Europe (million USD)
- JP_sales — Sales in Japan (million USD)
- Other_sales — Sales in other regions (million USD)
- Critic_Score — Critic rating (0–100)
- User_Score — User rating (0–10)
- Rating — ESRB rating

> ⚠️ Data for the year 2016 may be incomplete.

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- SciPy
- Jupyter Notebook

## 🔍 Analysis Steps
1. Data cleaning and preprocessing  
2. Exploratory data analysis (EDA)  
3. Platform and genre analysis  
4. Regional user profiling (NA, EU, JP)  
5. Statistical hypothesis testing  
6. Business insights and conclusions  

## 📈 Key Insights
- North America and Europe show similar consumption patterns, dominated by Action and Shooter games.
- Japan demonstrates a strong preference for Role-Playing games and portable platforms.
- Platform life cycles significantly impact global sales trends.
- Statistical tests reveal that not all visual differences are statistically significant.

## 🧪 Hypothesis Testing
Two hypotheses were tested using Welch’s t-test with a 5% significance level:
- The average user ratings for Xbox One and PC platforms are the same.
- The average user ratings for Action and Sports genres are different.

## 📁 Project Structure
```text
video-game-sales-analysis/
│
├── data/
│   └── games.csv
│
├── notebooks/
│   └── video_game_sales_analysis.ipynb
│
├── images/
│   └── sample_visualizations.png
│
└── README.md
