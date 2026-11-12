# Amazon Prime Movies and TV Shows – Exploratory Data Analysis (EDA)

## 1. Project Overview

This project focuses on Exploratory Data Analysis (EDA) of the Amazon Prime Movies and TV Shows dataset. The objective is to analyze the content available on Amazon Prime Video and discover meaningful patterns related to content types, genres, release years, countries, ratings, runtime, IMDb scores, TMDb popularity, and cast and crew information.

Python-based data analysis and visualization techniques are used to understand the dataset and generate useful insights.

## 2. Problem Statement

Streaming platforms contain thousands of movies and TV shows. Understanding the distribution, characteristics, popularity, and audience ratings of this content can help platforms make better content-related decisions.

This project explores the Amazon Prime catalogue to identify patterns and trends that can support content planning and audience engagement.

## 3. Business Objective

- Analyze the distribution of movies and TV shows.
- Identify popular genres and content categories.
- Understand content release trends over the years.
- Examine IMDb ratings and TMDb popularity.
- Analyze the distribution of TV shows by number of seasons.
- Study runtime patterns of movies.
- Identify major contributing actors and directors.
- Generate actionable insights for content strategy.

## 4. Dataset Description

The project uses Amazon Prime Movies and TV Shows data.

The dataset includes information such as:

- Content ID
- Title
- Content type
- Description
- Release year
- Age certification
- Runtime
- Genres
- Production countries
- Number of seasons
- IMDb ID and score
- IMDb votes
- TMDb popularity and score
- Cast and director credits

The merged dataset contains **125,186 rows and 19 columns**.

## 5. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 6. Exploratory Data Analysis

The project includes data loading, dataset inspection, missing-value analysis, duplicate checking, variable analysis, data cleaning, and visualization.

A total of 15 visualizations were developed to explore different aspects of the Amazon Prime catalogue.

## 7. Key Analysis Areas

1. Content type distribution
2. Age certification analysis
3. Release decade analysis
4. Production country analysis
5. Genre distribution
6. TV show season distribution
7. Runtime distribution
8. IMDb score analysis
9. TMDb score analysis
10. IMDb votes analysis
11. Top actors analysis
12. Top directors analysis
13. Most popular titles analysis
14. Correlation heatmap
15. Pair plot analysis

## 8. Project Structure

```text
Amazon-Prime-EDA/
│
├── graphs/
│   └── Visualization images
│
├── Dataset/
│   ├── credits.csv.zip
│   └── titles.csv.zip
│
├── Amazon_Prime_EDA.ipynb
│
├── amazon_prime_merged.zip
│
└── README.md
```

## 9. How to Run the Project

1. Clone or download this repository.
2. Extract the compressed dataset files.
3. Install the required Python libraries.
4. Open the Jupyter Notebook.
5. Update the dataset paths if necessary.
6. Execute the notebook cells sequentially.

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## 10. Conclusion

This project provides an exploratory understanding of the Amazon Prime Movies and TV Shows catalogue through data analysis and visualization. The findings help identify content distribution patterns, release trends, audience ratings, popularity, and contributions from actors and directors.

The analysis demonstrates how data visualization and exploratory data analysis can transform raw streaming-platform data into meaningful insights that support informed business decisions.

## 11. Author

**Venkata Ganesh Naik Banavath**

GitHub: https://github.com/VenkataGanesh1922
