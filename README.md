# Disney+ Content Analysis and Interactive Dashboard

## Project Overview
This project focuses on Exploratory Data Analysis (EDA), data cleaning, preprocessing, and interactive visualisation of the Disney+ content dataset using Python.

The objective is to analyse the distribution of Movies and TV Shows, understand content release trends, examine movie durations, and develop an interactive dashboard for exploring the dataset.

## Dataset
- **Total Records:** 1,450
- **Total Features:** 12
- **Movies:** 1,052
- **TV Shows:** 398

The dataset contains information such as title, content type, director, cast, country, release year, rating, duration, genre, and description.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- ipywidgets
- Google Colab / Jupyter Notebook

## Project Workflow

### 1. Data Loading
Imported the dataset and examined its structure, dimensions, and data types.

### 2. Exploratory Data Analysis
Analysed:
- Distribution of Movies and TV Shows
- Content release trends over the years
- Movie duration patterns
- Dataset characteristics and missing values

### 3. Data Cleaning and Preprocessing
- Handled missing values in relevant columns.
- Converted date fields into appropriate datetime format.
- Prepared data for analysis and visualisation.
- Retained unavailable date values rather than introducing inaccurate information.

### 4. Data Visualisation
Created five visualisations:
1. Movies vs TV Shows – Bar Chart
2. Content Releases Over the Years – Line Chart
3. Movie Duration vs Release Year – Scatter Plot
4. Distribution of Movie Durations – Histogram
5. Content Type vs Release Decade – Heatmap

### 5. Interactive Dashboard
Developed an interactive dashboard using Plotly and ipywidgets.

Dashboard features:
- Content type filter (All, Movie, TV Show)
- Release year range slider
- Dynamically updated charts
- Content count based on selected filters
- Dynamically updated visualisations based on selected filters.
- Content count based on the selected filters.

## Key Findings
- Movies account for approximately 72.6% of the dataset.
- TV Shows account for approximately 27.4%.
- 2021 was the year with the highest number of released titles in the dataset, with 125 titles.

## Project Outcome
The project demonstrates the use of Python for data analysis, preprocessing, visualisation, and interactive dashboard development. It provides an accessible way to explore patterns and trends in Disney+ content.

## How to Run
1. Open the Jupyter Notebook in Google Colab.
2. Run the cells sequentially.
3. Upload the Disney+ dataset CSV file when prompted.
4. Run the dashboard cell and use the available filters to explore the data.

## Repository Contents
- `Disney_Plus_Dashboard (2).ipynb` – Main project notebook containing the complete analysis, visualisations, and interactive dashboard.

---

**Project Category:** Data Analysis and Visualisation
