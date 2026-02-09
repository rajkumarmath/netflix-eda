# Netflix Movies and TV Shows – Exploratory Data Analysis

## Overview
This project performs exploratory data analysis (EDA) on the Netflix Movies and TV Shows dataset to understand content distribution, trends over time, country-wise availability, ratings, and duration patterns.

The objective is to derive meaningful insights using Python-based data analysis and visualization techniques.

## Dataset
- Source: Kaggle – Netflix Movies and TV Shows
- Records: ~7,800 titles
- Features include content type, title, director, cast, country, release year, rating, duration, genres, and description.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed
- Data cleaning and preprocessing
- Handling missing values
- Feature extraction (year added, duration)
- Univariate analysis:
  - Content type distribution
  - Ratings distribution
  - Country-wise content
  - Release year trends
- Bivariate analysis:
  - Content type vs year added
  - Rating vs content type
  - Country vs content type
  - Duration and season analysis

## Key Insights
- Netflix’s catalog is dominated by movies, though TV shows have shown steady growth in recent years.
- A significant increase in content addition occurred after 2015.
- The United States is the largest contributor to Netflix’s content library.
- Mature-rated content (TV-MA) makes up a large portion of the catalog.
- Most TV shows on Netflix have a limited number of seasons.

## Limitations
- The dataset does not include user engagement or viewership data.
- Some missing values were handled using assumptions such as labeling unknown categories.
- The dataset represents a snapshot in time and may not reflect the most recent Netflix updates.

## How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
Open the notebook:

bash
Copy code
jupyter notebook
Run the notebook cells sequentially

Conclusion
This project demonstrates the use of Python for data cleaning, exploratory data analysis, and data visualization to extract insights from a real-world dataset.
