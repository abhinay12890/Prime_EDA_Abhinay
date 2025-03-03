# Amazon Prime Video EDA Project

## Project Overview

This project performs Exploratory Data Analysis (EDA) on an Amazon Prime Video dataset to uncover valuable insights about content diversity, regional distribution, trends over time, and audience interests. The goal is to provide data-driven recommendations to Amazon Prime Video and other streaming services for optimizing content acquisition, enhancing user satisfaction, and maximizing subscription growth.

## Project Contributors

*   **Name:** K. Abhinay
*   **Contribution:** Individual

## Problem Statement

The project aims to address the following key business questions through data analysis:

*   **Content Diversity:** What genres and categories are prevalent on Amazon Prime Video?
*   **Regional Availability:** How does content distribution vary across different regions?
*   **Trends Over Time:** How has Amazon Prime’s content library evolved over time?
*   **IMDb Ratings & Popularity:** What are the highest-rated or most popular shows and movies?

## Business Objectives

The primary business objective is to leverage data analytics to support content decision-making for Amazon Prime Video and similar streaming platforms. By identifying trends in content performance, regional preferences, and audience engagement, the insights will be used to:

*   Optimize content acquisition strategies.
*   Enhance user satisfaction through personalized recommendations.
*   Drive subscription growth.

## Dataset

The dataset used in this project includes information about titles (movies and TV shows) available on Amazon Prime Video in the United States. It consists of two CSV files:

*   **titles.csv:** Contains information about each title, including genre, production country, IMDb and TMDB ratings, popularity scores, etc.
*   **credits.csv:** Provides data on the cast and crew involved in each title.

## Project Structure

*   **`Prime_EDA_Abhinay.ipynb` (Jupyter Notebook):** This notebook contains the complete EDA code, including data loading, cleaning, preprocessing, analysis, visualization, and insights.
*   **`titles.csv`:** Dataset containing title information.
*   **`credits.csv`:** Dataset containing credit information.
*   **`README.md`:** This file providing an overview of the project.

## Dependencies

The following Python libraries are required to run the code in the notebook:

*   numpy
*   pandas
*   seaborn
*   matplotlib
*   plotly
*   scikit-learn

You can install these libraries using pip:

```bash
pip install numpy pandas seaborn matplotlib plotly scikit-learn
