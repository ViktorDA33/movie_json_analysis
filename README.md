# Movie JSON Analysis

Python project analyzing 6 JSON movie datasets (1970–2020) with genres and actors trends.

Overview

This project analyzes movie data from the Wikipedia Movie Dataset
.
It focuses on:

Top genres and their trends over time

Top actors and their productivity over time

Bonus: How top actors distribute their films across top-3 genres versus others

The project uses Python, pandas, numpy, matplotlib, and seaborn.

How to Run

Install dependencies:

pip install pandas numpy matplotlib seaborn


Run the analysis:

python movie_analysis.py


Note: Replace movie_analysis.py with the actual filename of your Python script.

Analysis Steps

Load JSON datasets for selected years and combine into a single DataFrame.

Clean data: remove unnecessary columns (href, extract, thumbnail, etc.) and keep complete rows.

Explore data structure (df.info(), df.head()).

Analyze genres:

Find top 10 genres

Plot bar and pie charts

Examine trends of top 3 genres over time

Analyze actors:

Find top 10 actors

Plot bar and pie charts

Examine trends of top 3 actors over time

Bonus analysis:

Compare top-10 actors’ film distribution in top-3 genres vs. other genres

Visualize as stacked bar chart with percentages

Key Insights
Genres

Top 5 genres: Comedy, Drama, Action, Thriller, Horror (majority of movies).

Top 3 genres trend over time: Drama and Comedy dominate; Action shows steady but smaller volume.

Actors

Top 3 actors by number of films: Bruce Willis, Samuel L. Jackson, Robert De Niro.

Trends over years show peaks in 1990s–2010s; Samuel L. Jackson is highly productive and versatile.

Bonus: Bruce Willis is highly specialized (98% films in top-3 genres), while Willem Dafoe is most versatile (only 54% in top-3 genres).

File Structure
Movie-JSON-Analysis/
│
├─ movie_analysis.py       # Python script with analysis
├─ README.md              # This file
├─ kino.csv               # Optional: combined dataset saved as CSV
└─ (Optional plots/ folder if saving figures)

Technologies Used

Python: pandas, numpy, matplotlib, seaborn

JSON data handling and visualization
