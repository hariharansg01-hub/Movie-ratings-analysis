# 🎬 Movie Ratings Analysis

A Python data analysis project that explores movie ratings, compares genres, identifies top-rated movies, and studies viewer rating trends across decades using Pandas, NumPy, and Matplotlib.

## 📌 Project Overview

This project analyzes viewer ratings for 200 movies using a generated dataset containing 20,000 ratings. It helps understand which genres receive higher ratings, how movie popularity affects rankings, and how ratings vary across release decades.

The analysis is performed using Python in Jupyter Notebook, with visualizations to present the findings clearly.

> **Dataset note:** This project uses synthetic data generated for learning and demonstration. Movie titles and ratings are simulated and do not represent real films or audience reviews.

## 🎯 Objectives

- Analyze average viewer ratings by movie genre.
- Calculate each movie's average rating and total number of votes.
- Identify the top 10 movies using a minimum of 50 ratings.
- Understand how a minimum-vote rule improves ranking reliability.
- Examine the distribution of star ratings.
- Explore rating trends across release decades.
- Create visualizations and export analysis results.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming and data analysis |
| Jupyter Notebook | Interactive coding and execution |
| NumPy | Generate and process numerical data |
| Pandas | Data cleaning, merging, grouping, and aggregation |
| Matplotlib | Create charts and visualizations |

## 📂 Project Structure

```text
Movie-Ratings-Analysis/
│
├── Movie_Ratings_Analysis.ipynb
├── README.md
├── requirements.txt
│
├── data/
│   ├── movies.csv
│   └── ratings.csv
│
└── outputs/
    ├── chart.png
    ├── results.json
    ├── genre_analysis.csv
    ├── movie_analysis.csv
    ├── top10_movies.csv
    └── decade_analysis.csv
```

The notebook generates the dataset and performs the analysis. The `data/` and `outputs/` folders can be included in the repository if you save the generated CSV and result files there.

## 📊 Dataset Description

The project generates two datasets:

### 1. Movies Dataset

Contains 200 movies with the following columns:

- `movie_id` — Unique movie identifier
- `title` — Movie title (generated placeholder)
- `genre` — Movie genre
- `year` — Movie release year

### 2. Ratings Dataset

Contains 20,000 simulated viewer ratings:

- `movie_id` — Movie identifier
- `rating` — Viewer rating from 0.5 to 5 stars

The ratings are merged with movie details using `movie_id` for further analysis.

## 🔍 Project Workflow

1. Import NumPy, Pandas, and Matplotlib.
2. Generate movie details and simulated viewer ratings.
3. Merge ratings with movie information.
4. Calculate average ratings and vote counts by genre.
5. Summarize individual movie ratings.
6. Rank the top 10 movies with at least 50 ratings.
7. Compare rankings with and without the minimum-vote rule.
8. Analyze average ratings by release decade.
9. Create a multi-chart visualization dashboard.
10. Export summary tables and results.

## 📈 Visualizations

The notebook creates a dashboard containing:

- **Average Rating by Genre:** Compares viewer preferences across genres.
- **Rating Distribution:** Shows how frequently each star rating occurs.
- **Votes vs. Average Rating:** Examines the relationship between popularity and average rating, using a logarithmic vote-count axis.
- **Top 10 Movies:** Displays highly rated movies that meet the 50-vote threshold.
- **Rating Trend by Decade:** Compares average ratings across release decades.

Different genres use different colors to make the charts easier to interpret.

## 💡 Key Insights

The analysis helps answer these questions:

- Which genre has the highest and lowest average rating?
- Which movies rank highest after applying the minimum-vote rule?
- How many highly rated movies have too few votes to qualify?
- How are viewer ratings distributed?
- Do average ratings differ across release decades?

The exact findings are calculated when the notebook is executed and can be reviewed in its output cells and exported results.

## ▶️ How to Run the Project

### Step 1: Install Python libraries

Run this command in a Jupyter Notebook cell:

```python
%pip install numpy pandas matplotlib
```

### Step 2: Open the notebook

Open `Movie_Ratings_Analysis.ipynb` in Jupyter Notebook or JupyterLab.

### Step 3: Execute the code

Run the notebook cells in order, starting from the imports and dataset generation.

You can use **Kernel → Restart & Run All** to execute the entire notebook.

### Step 4: View the results

After execution, view the analysis tables, charts, and calculated insights in the notebook.

The notebook also exports chart and analysis files when the relevant cells are run.

## 📚 Concepts Practiced

- Pandas `merge()`
- `groupby()` and `agg()`
- Mean and count calculations
- Filtering and ranking with `nlargest()`
- NumPy random data generation
- Matplotlib bar charts, histograms, scatter plots, and line charts
- Saving results as CSV and JSON

## 🏁 Conclusion

This project demonstrates how Python data analysis tools can be used to explore movie ratings, compare genres, rank movies, and visualize trends. It also highlights why rankings should consider the number of ratings, rather than relying only on average scores.

The project is intended for educational and portfolio purposes.

## 👨‍💻 Author

**Hariharan SG**

<img width="2831" height="1624" alt="chart" src="https://github.com/user-attachments/assets/5141f91a-44af-4f7b-9098-209f4735f5fc" />



Project 11 — Movie Ratings Analysis
