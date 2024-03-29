# Dinosaur Dataset Analysis

## Overview
Analyzing trends in a dataset consisting of dinosaur information scraped from the Natural History Museum website (source: https://www.kaggle.com/datasets/kjanjua/jurassic-park-the-exhaustive-dinosaur-dataset).

## Questions
* What is the distribution of dinosaur lengths across the dataset? How do the lengths of certain types of dinosaurs compare to others?
* In what countries were the dinosaurs most commonly found?
* Are there trends in dinosaur length over different time periods?

## Data Cleaning and Initial Visualizations
Through Kaggle's Notebook feature, I was able to load the dataset directly into a Python notebook. A few modules came pre-loaded, including OS and Numpy. Basic ETL was performed on the data to ensure it was formatted correctly, and Seaborn was used to create histograms to show the overall length distribution and that of specifically the sauropods. Additionally, new columns were created for "start year", "end year", and "mean year" based on the "period" column in order to graph trends in dinosaur length (or other statistics) over time. The edited data was exported as a CSV file to be used in Tableau. The full process is documented in **dinosaur-data-analysis.ipynb**.

## Tableau Story
The visualizations created in the Jupyter Notebook file were recreated in Tableau, along with new visualizations including a map and pie chart of geologic distribution, and organized into a story.

The story can be found [here](https://public.tableau.com/app/profile/luke.snyder/viz/DinosaurDatasetAnalysis/DinosaurDatasetAnalysis)
