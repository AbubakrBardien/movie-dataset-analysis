# Movie Dataset Analysis

This project does Data Cleaning and Data Analysis, on the top 1000 movies from IMDB, using Jupyter Notebooks. The Jupyter Notebooks are named accordingly.

The movies dataset, "imdb_top_1000.csv", was obtained from [Kaggle](https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows), and is under the Public Domain License (CC0).

In both Jupyter Notebooks, I made notes in-between to convey my thought process. And in the "Data_Analysis" notebook, I created the following graphs to gain insights about the data.

Types of graphs created:

- Number of Movies released across the years
- 3 Best vs 3 Wost Grossing Movies
- Distribution of Public Ratings and Average Critic Reviews
- Distribution of Movie Runtimes
- Top Directors
- Top Genres
- Top Genre Combinations

## Installation

Requirements:

- python
- jupyter-notebook

(You can install these using your package manager)

### Install Python Virtual Environment tool

For Windows: `pip install virtualenv`\
For Linux: `pipx install virtualenv` (Install `pipx` with your package manager if you haven't already)

### Create Python Virtual Environment:
After cloning the repository, go into the project folder to create the virtual environment.

Windows:
```cmd
virtualenv .venv
.venv\Scripts\activate
```

Linux:
```bash
virtualenv .venv
source .venv/bin/activate
```

### Install Dependencies:
```bash
pip install -r requirements.txt
```
