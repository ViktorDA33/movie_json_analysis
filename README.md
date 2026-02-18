# Movie JSON Analysis

Python project analyzing 6 JSON movie datasets (1970–2020) with genres and actors trends.

## Steps performed

1. **Listed available JSON files** from the source and selected datasets using `numpy.arange`.
2. **Loaded each JSON file**, removed unnecessary columns (`href`, `extract`, `thumbnail`, `thumbnail_width`, `thumbnail_height`) and kept only complete rows.
3. **Combined all datasets** into a single DataFrame and saved a backup copy as CSV.
4. **Explored data structure** using `info()` to understand nested fields.
5. **Analyzed genres**:
   - Found top 10 genres by movie count
   - Plotted bar and pie charts
   - Displayed summary table
6. **Analyzed trends for the top 3 genres** over the selected years with line charts.
7. **Analyzed actors**:
   - Found top 10 actors by movie count
   - Visualized with bar charts and summary table
8. **Analyzed trends for the top 3 actors** over the selected years with line charts.
9. **Bonus analysis**:
   - Focused on the top 10 actors and their participation in top-3 genres
   - Calculated proportions and displayed as stacked bar chart with percentages

## Technologies used

- Python
- `pandas`
- `numpy`
- `matplotlib`
- JSON data handling and visualization

## How to run

1. Install required libraries:

```
pip install pandas numpy matplotlib
```

2. Open the Jupyter Notebook:

```
jupyter notebook movie_analysis.ipynb
```

All analysis, tables, and visualizations are contained inside the notebook.
---
You can also view the analysis directly in the Jupyter Notebook here: [movie_analysis.ipynb](movie_analysis.ipynb)
---
## Data Source

The movie datasets were obtained from the public repository:

https://github.com/prust/wikipedia-movie-data

Repository owner: prust  
Dataset: Wikipedia Movie Data (1900–2020)

The data was used for educational and analytical purposes.
