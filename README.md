
![IMDB Top 250 Movies Analysis](IMDB_Top_250_Movies_Analysis.png)
<br>
![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
<a target="_blank" href="https://www.linkedin.com/in/tkacz-milosz-data-science/"><img height="20" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<br>

**Date:** December 27, 2022

## Overview

This repository contains the R-Markdown file for an exploratory data analysis (EDA) of IMDb's top 250 movies. The analysis covers various aspects, including numerical insights, genres, and a focus on notable actors, directors, and writers.

## Data Source

The dataset used for this analysis was sourced from Kaggle, specifically the [IMDb Top 250 Movies dataset](https://www.kaggle.com/datasets/ashishjangra27/imdb-top-250-movies) created by Ashish Jangra.

## Tools and Libraries Used

- R and RStudio
- Libraries: dplyr, stringr, DT, ggplot2, plotly

## Exploratory Data Analysis Highlights

- **Numerical Insights:** Explored key numerical features such as movie rank, year of release, duration, IMDb votes, and IMDb ratings. Addressed missing data and conducted correlation analysis.

- **Genres Analysis:** Investigated the distribution of movie genres in the top 250 list, revealing Drama as the most prevalent genre.

- **Genre and Attributes Relationships:** Explored relationships between genres and attributes like production year, IMDb rating, duration, and number of votes.

- **Actors Analysis:** Identified the most prolific actors in the top 250 movies, highlighting Robert De Niro as a standout with nine appearances.

- **Directors and Writers Analysis:** Explored the contributions of directors and writers, showcasing notable figures such as Kubrick, Kurosawa, and Nolan.

## Visualizations

The analysis includes interactive visualizations using ggplot2 and plotly to enhance the understanding of relationships and trends.

## How to Run the Analysis

1. Ensure you have R and RStudio installed on your machine.
2. Install the required libraries using the following commands:

   ```R
   install.packages("dplyr")
   install.packages("stringr")
   install.packages("DT")
   install.packages("ggplot2")
   install.packages("plotly")
   ```

3. Open the R-Markdown file (`IMDb_Top_250_Analysis.Rmd`) in RStudio.
4. Execute the code chunks sequentially to reproduce the analysis.

## Acknowledgments

Special thanks to [Ashish Jangra](https://www.kaggle.com/ashishjangra27) for creating the IMDb Top 250 Movies dataset on Kaggle.

Feel free to explore and contribute to the analysis. If you have any questions or suggestions, please open an issue or reach out to the project author.

Happy exploring!
