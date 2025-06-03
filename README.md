# Spotify-Songs-Analysis

This repository contains a Jupyter Notebook that performs exploratory data analysis on a Spotify songs dataset. The notebook answers several analytical questions and provides visualizations related to song submissions, artists, genres, and release timelines.

## Contents

- `spotify_analysis.ipynb`; The main Jupyter Notebook containing:
  - Python scripts to load and analyze the data
  - Answers to each analytical question, clearly separated into sections
  - Visualizations and diagrams for better insight
- `spotify_dataset.csv`; The Spotify songs dataset used for analysis

## Analytical Questions Answered

1. **Number of files submitted for the month of March**  
   Calculates how many songs were added in March across all years.

2. **Maximum duration for each year**  
   Finds the song with the maximum duration released in each year.

3. **Number of songs released for each artist for all years**  
   Summarizes total songs released by each artist across the dataset.

4. **Number of songs released for each artist in 2010**  
   Filters the dataset for the year 2010 and counts songs per artist.

5. **Number of songs released for each top genre in each year**  
   Provides counts of songs released per top genre, broken down by year.

## Diagrams and Visualizations

- **Bar Plot:** Number of songs added by month & year  
  Helps visualize seasonal and yearly trends.

- **Line Graph:** Number of songs added by top genre for all years  
  Shows the popularity of top genres over time.

## Usage

1. Clone this repository or download the files.
2. Ensure you have Python (>=3.7) and Jupyter Notebook installed.  
   You can install Jupyter via Anaconda or with pip:
   ```
   pip install notebook
   ```
3. Install required libraries:
   ```
   pip install pandas matplotlib seaborn
   ```
4. Launch the notebook:
   ```
   jupyter notebook spotify_analysis.ipynb
   ```
5. Run each section independently to view the analysis and results.

## Dataset

The analysis uses `spotify_dataset.csv`, which should be placed in the same directory as the notebook. This dataset contains metadata for Spotify songs, including fields such as song name, artist, genre, duration, date added, and release year.

## License

This project is for educational purposes. See the dataset source for any specific data usage licenses.

---
**Author:** [Jagadeeshwari]  
**Date:** June 2025
