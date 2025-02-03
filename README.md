# IMDB Movies Dataset - Jupyter Notebook

## Overview

This project analyzes the IMDB Movies Dataset using Python in a Jupyter Notebook. The notebook contains data preprocessing, exploratory data analysis (EDA), and visualization techniques to derive insights from the dataset.

## Dataset Information

- **Dataset Name**: IMDB Movies Dataset
- **Source**: IMDB
- **File Type**: CSV / DataFrame
- **Attributes**: Includes movie title, genre, director, actors, release year, ratings, and more.

## Features of the Notebook

1. **Data Loading**

   - Reads the dataset using Pandas.
   - Displays basic information such as column names, data types, and missing values.

2. **Data Cleaning & Preprocessing**

   - Handles missing values and duplicates.
   - Converts data types where necessary.
   - Normalizes and structures data for analysis.

3. **Exploratory Data Analysis (EDA)**

   - Visualizes distributions and trends in ratings, genres, and release years.
   - Identifies top-rated and most popular movies.
   - Analyzes relationships between variables such as budget and revenue.

4. **Data Visualization**

   - Uses Matplotlib and Seaborn for graphs and plots.
   - Generates histograms, bar charts, and scatter plots to highlight key findings.

5. **Statistical Analysis**

   - Calculates summary statistics like mean, median, and standard deviation.
   - Performs correlation analysis between numerical features.

## Requirements

To run the Jupyter Notebook, you need the following dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

Or install using a requirements file:

```bash
pip install -r requirements.txt
```

## How to Use

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook IMDB_movies_dataset.ipynb
   ```
2. Run the notebook cells in sequential order.
3. Modify parameters or add your own analysis for further insights.

## Results & Insights

- The dataset provides an in-depth look at trends in the movie industry.
- Ratings and popularity are influenced by factors such as genre and director.
- Yearly trends show fluctuations in movie production and audience preferences.

## Future Improvements

- Expand the dataset with additional sources for better insights.
- Implement machine learning models to predict movie success.
- Enhance visualizations with interactive plots.

## Author & License

- **Author**: Yameen Munir
- **License**: MIT License

For any questions or contributions, feel free to submit a pull request or open an issue.

