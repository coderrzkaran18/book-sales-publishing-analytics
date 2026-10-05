# Book Sales & Publishing Analytics

### Exploratory Data Analysis of Book Sales, Ratings, Publishing Trends & Reader Engagement

An Exploratory Data Analysis (EDA) project based on the **Books Sales
and Ratings** dataset from Kaggle. The project explores book genres,
languages, publishing trends, ratings, pricing, authors, gross sales,
and units sold using Python and data visualization.

------------------------------------------------------------------------

## Project Overview

This project analyzes book-related data to identify meaningful patterns
and relationships in:

-   Book genres and language distribution
-   Publishing activity over time
-   Book ratings and rating counts
-   Author ratings and units sold
-   Sale price and units sold
-   Gross sales by author
-   Sales trends across publishing years

The goal is to transform raw book data into clear, data-driven insights
through systematic exploratory analysis.

------------------------------------------------------------------------

## Dataset

**Dataset:** Books Sales and Ratings

**Source:** Kaggle

[View Dataset on
Kaggle](https://www.kaggle.com/datasets/thedevastator/books-sales-and-ratings)

The dataset contains book-level information related to attributes such
as author, genre, language, publishing year, ratings, sale price, units
sold, author rating, and gross sales.

------------------------------------------------------------------------

## Objectives

-   Understand the structure and characteristics of the dataset.
-   Perform data cleaning and preprocessing.
-   Check data quality, missing values, and duplicates.
-   Analyze categorical and numerical variables.
-   Explore genre and language distributions.
-   Analyze publishing trends over time.
-   Study book ratings and reader engagement.
-   Explore relationships between ratings, price, and sales.
-   Identify high-performing authors.
-   Generate meaningful analytical insights from visualizations.

------------------------------------------------------------------------

## Tools & Technologies

  Tool / Library                    Purpose
  --------------------------------- --------------------------------
  Python                            Data analysis
  Pandas                            Data manipulation and analysis
  NumPy                             Numerical operations
  Matplotlib                        Data visualization
  Seaborn                           Statistical visualization
  Jupyter Notebook / Google Colab   Development environment

------------------------------------------------------------------------

## Project Workflow

``` text
Dataset
   ↓
Data Loading
   ↓
Data Understanding
   ↓
Data Cleaning & Preprocessing
   ↓
Missing Value & Duplicate Check
   ↓
Exploratory Data Analysis
   ↓
Statistical Analysis
   ↓
Data Visualization
   ↓
Insight Generation
   ↓
Business Interpretation
```

------------------------------------------------------------------------

# Exploratory Data Analysis

## 1. Average Rating vs Rating Count

This scatter plot explores the relationship between the average rating
of a book and the number of ratings received.

![Average Rating vs Rating
Count](images/Average%20Rating%20vs%20Rating%20Count.png)

------------------------------------------------------------------------

## 2. Rating Count by Genre

This box plot compares the distribution of rating counts across
different book genres and highlights differences in reader engagement.

![Rating Count by
Genre](visualizations/Book%20Rating%20Count%20by%20Genre.png)

------------------------------------------------------------------------

## 3. Genre Distribution

This visualization shows the number of books available across different
genres.

![Genre Distribution](visualizations/Genre%20Distribution.png)

------------------------------------------------------------------------

## 4. Gross Sales by Author

This chart compares authors based on their total gross sales and
highlights authors with comparatively higher sales performance.

![Gross Sales by Author](visualizations/Gross%20Sales%20by%20Author.png)

------------------------------------------------------------------------

## 5. Language Distribution

This visualization shows the distribution of books across different
languages in the dataset.

![Language Distribution](visualizations/Language%20Distribution.png)

------------------------------------------------------------------------

## 6. Publishing Year Distribution

This chart shows how books are distributed across publishing years and
helps identify changes in publishing activity over time.

![Publishing Year
Distribution](visualizations/Publishing%20Year%20Distribution.png)

------------------------------------------------------------------------

## 7. Units Sold by Author Rating

This box plot compares units sold across different author-rating
categories to explore the relationship between author rating and sales
performance.

![Units Sold by Author
Rating](visualizations/Units%20Sold%20by%20Author%20Rating.png)

------------------------------------------------------------------------

## 8. Sale Price vs Units Sold

This scatter plot explores the relationship between sale price and the
number of units sold.

![Sale Price vs Units
Sold](visualizations/Sale%20Price%20vs%20Units%20Sold.png)

------------------------------------------------------------------------

## 9. Units Sold Trend

This visualization shows how units sold vary across publishing years.

![Units Sold Trend](visualizations/Units%20Sold%20Trend.png)

------------------------------------------------------------------------

# Key Insights

The exploratory analysis provides the following observations:

-   **Genre fiction** represents the largest genre category in the
    analyzed dataset.
-   **English-language books** account for the largest share of books.
-   The dataset contains considerably more books from recent publishing
    years.
-   Rating counts vary substantially across genres.
-   Books with different average ratings can have widely different
    rating counts, indicating that average rating alone does not explain
    reader engagement.
-   Author-rating categories show differences in the distribution of
    units sold.
-   Sale price and units sold do not show a simple linear relationship
    in the analyzed data.
-   A relatively small group of authors records higher gross sales than
    other authors.
-   Units sold vary significantly across publishing years, with stronger
    sales activity visible in more recent periods.

> **Note:** These are exploratory observations from the available
> dataset. They indicate patterns and relationships, not necessarily
> causal effects.

------------------------------------------------------------------------

# Business Questions

### Sales Analysis

-   Which authors generate the highest gross sales?
-   How do units sold change over time?
-   Does sale price appear to influence sales volume?

### Reader Engagement

-   Which genres have higher rating counts?
-   Is average rating associated with rating count?
-   How does author rating relate to units sold?

### Publishing Analysis

-   Which genres contain the most books?
-   Which languages dominate the dataset?
-   How has publishing activity changed over time?

------------------------------------------------------------------------

# Visualization Summary

    No. Analysis
  ----- --------------------------------
      1 Average Rating vs Rating Count
      2 Rating Count by Genre
      3 Genre Distribution
      4 Gross Sales by Author
      5 Language Distribution
      6 Publishing Year Distribution
      7 Units Sold by Author Rating
      8 Sale Price vs Units Sold
      9 Units Sold Trend

------------------------------------------------------------------------

# Project Structure

``` text
Book-Sales-Publishing-Analytics/
│
├── data/
│   └── books.csv
│
├── notebooks/
│   └── Book_Sales_Analysis.ipynb
│
├── visualizations/
│   ├── Average Rating vs Rating Count.png
│   ├── Book Rating Count by Genre.png
│   ├── Genre Distribution.png
│   ├── Gross Sales by Author.png
│   ├── Language Distribution.png
│   ├── Publishing Year Distribution.png
│   ├── Units Sold by Author Rating.png
│   ├── Sale Price vs Units Sold.png
│   └── Units Sold Trend.png
│
├── README.md
└── requirements.txt
```

------------------------------------------------------------------------

# Installation & Setup

### 1. Clone the repository

``` bash
git clone <your-github-repository-url>
```

### 2. Navigate to the project directory

``` bash
cd Book-Sales-Publishing-Analytics
```

### 3. Install dependencies

``` bash
pip install -r requirements.txt
```

### 4. Run the notebook

``` bash
jupyter notebook
```

Open the analysis notebook and run the cells sequentially.

------------------------------------------------------------------------

# Requirements

The main libraries used in this project are:

``` text
pandas
numpy
matplotlib
seaborn
jupyter
```

------------------------------------------------------------------------

# Future Improvements

The project can be extended with:

-   Interactive Power BI dashboard
-   SQL-based analysis
-   Genre-wise sales performance analysis
-   Author performance dashboard
-   Statistical hypothesis testing
-   Sales forecasting
-   Book recommendation system
-   Interactive Streamlit dashboard

------------------------------------------------------------------------

# Learning Outcomes

This project strengthened practical skills in:

-   Data cleaning and preprocessing
-   Exploratory Data Analysis
-   Pandas data manipulation
-   NumPy-based numerical analysis
-   Data visualization
-   Statistical exploration
-   Correlation analysis
-   Outlier identification
-   Categorical and numerical analysis
-   Trend analysis
-   Business insight generation
-   Data-driven decision making

------------------------------------------------------------------------

# Conclusion

The **Book Sales & Publishing Analytics** project demonstrates how
Exploratory Data Analysis can be used to understand patterns in book
publishing, reader engagement, pricing, ratings, and sales performance.

The project combines data preparation, statistical exploration,
visualization, and business-oriented interpretation to convert raw book
data into meaningful analytical insights.

------------------------------------------------------------------------

## Author

**Karan Chauhan**

**B.Tech -- Computer Science Engineering (Data Science)**

**Email:** `your-email@example.com`

**GitHub:**
[github.com/coderrzkaran18](https://github.com/coderrzkaran18)

**LinkedIn:** `your-linkedin-profile`

------------------------------------------------------------------------

### Project Information

**Project:** Book Sales & Publishing Analytics\
**Domain:** Data Analytics / Exploratory Data Analysis\
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn\
**Dataset:** Books Sales and Ratings -- Kaggle

------------------------------------------------------------------------

⭐ If you found this project useful, consider giving the repository a
star.
