# Project2
NFL Team Analysis

This project analyzes NFL team ranking changes in passing and rushing over several seasons, specifically focusing on the years 2021–2023. Using interactive visualizations, it allows users to compare rank changes over time and across teams.
Project Overview

The primary objective of this project is to visualize rank changes in NFL team passing and rushing stats, helping to identify trends and fluctuations for individual teams over time. The visualizations offer insights into team performance, showing how ranks for passing and rushing evolve each year.
Repository Structure

The repository contains the following files:

    README.md: This file, explaining the purpose, structure, and data source for the project.
    ranking_changes_analysis.ipynb: The main Jupyter Notebook where data processing, analysis, and plotting are performed. It includes code for data cleaning, transformation, and creating visualizations using Plotly.
    ranking_changes_df.csv: A CSV file with NFL team ranking changes in passing and rushing. The columns include:
        Team: The name of each NFL team.
        Passing Rank Change: A list of rank change values for each year (2021–2023).
        Rushing Rank Change: A list of rank change values for each year (2021–2023).
    requirements.txt: A file listing the Python dependencies required to run the project (e.g., pandas, plotly).

Data Source

The data used in this project was scraped from Pro-Football-Reference, a comprehensive database for NFL statistics and historical information. All data preprocessing and analysis performed in this repository complies with the data usage policies specified by the source.
