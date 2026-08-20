# Seaborn & Pandas Visualization Lab

A completed data visualization project using **Seaborn**, **Pandas**, **Matplotlib**, and two classic datasets: **Palmer Penguins** and **Iris**.

## Project Overview

This lab focuses on creating clear statistical visualizations and applying presentation-oriented styling. The notebook progresses from basic Seaborn boxplots to real-data analysis using categorical encodings, scatter plots, histograms, grouped summaries, and pandas-native plotting.

## Learning Objectives

- Create boxplots with Seaborn
- Add clear titles and axis labels
- Apply Seaborn styles such as `darkgrid`
- Use Seaborn contexts such as `poster`, `talk`, and `paper`
- Encode categories using color and marker style
- Create histograms and scatterplots from pandas DataFrames
- Aggregate data with `groupby()` before visualization
- Create visualizations directly from pandas Series and DataFrames

## Datasets

### Penguins
`penguins.csv` contains biometric measurements for three penguin species, including body mass, bill length, bill depth, species, and sex.

The analysis includes:
- body-mass distributions separated by sex
- bill length vs. bill depth with sex encoded by color and species encoded by marker style

### Iris
`iris.csv` contains sepal and petal measurements for three iris species.

The analysis includes:
- mean sepal width by species
- sepal-length distributions separated by species

## Notebook Workflow

### Part I — Seaborn
1. Create a basic boxplot
2. Add labels and a title
3. Apply the `darkgrid` style
4. Apply the `poster` context
5. Visualize penguin body-mass distributions by sex
6. Visualize penguin bill-size relationships by sex and species

### Part II — Pandas Plotting
7. Aggregate mean sepal width by species and create a bar chart
8. Create species-specific sepal-length histograms

## Technologies

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook / Google Colab

## Run the Project

Open `SeabornPandas.ipynb` in Jupyter or Google Colab and run the notebook from top to bottom.

Because the notebook reads `penguins.csv` and `iris.csv` using relative file paths, make sure both CSV files are available in the notebook's working directory when running locally or in Colab.

## Repository Structure

```text
DS_Course0_Week1_Module6_SeabornPandas/
├── SeabornPandas.ipynb
├── penguins.csv
├── iris.csv
└── README.md
```

## Key Takeaway

Seaborn is especially useful when statistical relationships and categorical encodings need to be communicated quickly, while pandas plotting provides a convenient way to visualize already-grouped or filtered data with minimal code.

## Author

Steven Rouse
