Amazon Prime Video Content Analysis & Insights
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on Amazon Prime Video’s content dataset to uncover trends, patterns, and business insights that can guide content strategy and user engagement decisions.

The analysis combines content metadata and cast/crew information to provide a holistic understanding of:

Content distribution (Movies vs TV Shows)

Genre dominance

Ratings and popularity trends

Regional production patterns

Long-term content growth

🎯 Business Objective

The objective of this project is to:

Identify high-performing genres

Understand audience quality perception (IMDb & TMDb scores)

Detect growth patterns in content production

Analyze regional content dominance

Provide actionable recommendations for content strategy

The goal is to enable data-driven decision making in the streaming industry.

📂 Dataset Information

Two datasets were used:

1️⃣ titles.csv

Contains:

id

title

show_type (Movie / TV Show)

release_year

genres

age_certification

runtime

imdb_score

imdb_votes

tmdb_popularity

tmdb_score

production_countries

2️⃣ credits.csv

Contains:

person_id

id

name

character

role (Actor / Director / Writer)

The datasets were merged using a Left Join on the id column.

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🧹 Data Cleaning & Preprocessing

✔ Removed duplicate rows
✔ Handled missing values
✔ Filled missing ratings using median values
✔ Replaced missing text fields with appropriate labels
✔ Converted genres & production countries to list format
✔ Standardized numerical data types

📊 Exploratory Data Analysis

The analysis was structured using the UBM Framework:

🟢 Univariate Analysis

Distribution of Movies vs TV Shows

Top genres

Release year trends

IMDb & TMDb score distribution

Runtime distribution

Age certification analysis

TV seasons distribution

🟡 Bivariate Analysis

IMDb rating by show type

IMDb vs TMDb correlation

Votes vs popularity relationship

Genre vs rating comparison

Country vs content production

🔵 Multivariate Analysis

Genre × Show Type heatmap

Country × Show Type comparison

Genre × Rating × Popularity relationship

Seasons × Ratings × Popularity

Actor participation volume

Total visualizations created: 20+ meaningful charts

🔍 Key Insights

🎥 Movies dominate in quantity

📺 TV shows have slightly higher average ratings

🎭 Drama & Documentary are highest-rated genres

⭐ IMDb scores strongly correlate with popularity

🇺🇸 USA dominates production

📈 Rapid growth in content after 2017

📉 Most TV shows have only 1–2 seasons

💡 Business Recommendations

Shift from volume-driven to quality-focused production

Invest in high-rated genres like Drama & Documentary

Develop long-running flagship TV series

Expand regional/local content

Use ratings-driven marketing strategies

Avoid genre saturation

📈 Business Impact

This project demonstrates how data can support:

Content acquisition strategy

Marketing decisions

Investment prioritization

Subscriber retention planning

🚀 How to Run the Project
# Clone the repository
git clone https://github.com/rk583578/Capstone-Project-EDA/

# Install required libraries
pip install pandas numpy matplotlib seaborn

# Open the notebook
jupyter notebook
📌 Project Structure
Amazon-Prime-EDA/
│
├── titles.csv
├── credits.csv
├── EDA_Notebook.ipynb
├── README.md

👤 Author Raushan Gupta
Data Analyst | Python | SQL | Power BI

⭐ Final Note

This project showcases strong skills in:

Data Cleaning

Data Visualization

Business Storytelling

Analytical Thinking

Decision-Oriented Insights
