# Data-Analysis-On-Netflix-Data

🎬✨ Netflix Movie Data Analysis — Complete Insight Report
<p align="center"> <img src="https://upload.wikimedia.org/wikipedia/commons/7/75/Netflix_icon.svg" width="130"> </p> <p align="center"> <b>📊 Data • 🎥 Movies • 📈 Insights • 🤖 Analytics</b> </p>
🚀 Project Overview

This project analyzes a dataset of 9,000+ Netflix movies to uncover meaningful insights using Python and various data visualization tools.
The analysis focuses on genres, popularity, votes, and production trends to answer five real business questions mentioned in the task.

All analysis is done inside:
👉 movie.ipynb

📁 Dataset Features

Your Netflix dataset includes:

🎭 Genre

⭐ Popularity

🗳 Vote Count

🎬 Movie Titles

📅 Release Year

🌍 Country

🗣 Language

📝 Overview / Description

❓🔍 Business Questions Solved
1️⃣ 🎭 Most Frequent Genre on Netflix
<div align="center">
📊 Genre Distribution Chart
<img src="download.png" width="650" style="border-radius: 10px;">

Figure: Count of movies by genre in the Netflix dataset

</div>
📝 Insight

✔ Drama is the most dominant genre
✔ Followed by Comedy, Action, and Thriller
✔ Least common genres include TV Movie, Documentary, and Western

2️⃣ ⭐ Which Genres Have the Highest Votes?

Movies were grouped by genre and sorted by vote count.

📝 Insight

✔ Genres with the highest votes show better audience engagement
✔ Top-voted genres often overlap with most frequent genres
✔ Voting patterns indicate viewer preferences on Netflix

3️⃣ 🔥 Which Movie Has the Highest Popularity? What’s Its Genre?

Using idxmax() on the popularity column, the highest-popularity movie and its genre were extracted.

📝 Insight

✔ This movie stands out significantly compared to others
✔ Helps identify blockbuster-level interest on Netflix

4️⃣ 🧊 Which Movie Has the Lowest Popularity? What’s Its Genre?

Using idxmin(), the least popular movie was identified.

📝 Insight

✔ This reveals underperforming content
✔ Useful for identifying genres with low traction

5️⃣ 📅 Which Year Has the Most Filmed Movies?

Movies were grouped by release year, and counts were plotted.

📝 Insight

✔ Certain years show a spike in movie releases
✔ Indicates content production trends over time

📊 Visualizations Included

Your notebook contains:

🎭 Genre Count Plot

⭐ Votes by Genre

🔥 Popularity Distribution

🎬 Highest & Lowest Popularity Movies

📅 Release Year Frequency Plot

All plots are styled cleanly using Seaborn and Matplotlib.

🧰 Tech Stack
Tool	Purpose
🐍 Python	Analysis & Logic
📦 Pandas	Data Cleaning
🔢 NumPy	Numerical Calculations
🎨 Seaborn	Visualization
📊 Matplotlib	Plot Styling
📝 Jupyter	Interactive Notebook
🏃‍♂️💻 How to Run the Project
git clone https://github.com/Ghalib18/Data-Analysis-On-Netflix-Data
cd Data-Analysis-On-Netflix-Data
jupyter notebook


Open movie.ipynb → Run all cells.

📝✨ Key Insights Summary

🎭 Netflix favors certain genres heavily (Drama, Comedy, Action).

⭐ User votes favor popular mainstream genres.

🔥 The highest-popularity movie stands out strongly.

🧊 The least popular movie helps identify weak content.

📅 Netflix movie production increased in key years.

🏁 Conclusion

This project provides a clean, data-driven view into Netflix’s movie catalog using structured analysis and visual storytelling.
It answers all five business questions with clear insights, supporting data-focused decision-making.
