# Data Science Skill Assessment

## Q18 - Box Office Data Analysis

This project performs Exploratory Data Analysis (EDA) and Data Visualization on a movie box-office dataset to identify the factors related to opening weekend revenue.

##Objectives

- Load and explore the box-office dataset using Python Pandas.
- Handle missing values and duplicate movie records.
- Analyse production budget, screen count, genre and opening weekend revenue.
- Calculate revenue per screen.
- Categorize movies based on production budget.
- Visualize relationships using Scatter Plots and Bar Charts.
- Identify the factor with the strongest relationship with opening revenue.

##Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Analysis Performed

### 1. Production Budget vs Opening Revenue

A Scatter Plot was used to study the relationship between production budget and opening weekend revenue.

![Budget vs Revenue](outputs/budget_vs_revenue.png)

### 2. Screen Count vs Opening Revenue

A Scatter Plot was used to analyse the relationship between the number of screens and opening weekend revenue.

![Screens vs Revenue](outputs/screens_vs_revenue.png)

### 3. Genre vs Opening Revenue

A Bar Chart was used to compare average opening weekend revenue across movie genres.

![Genre vs Revenue](outputs/genre_vs_revenue.png)

## Key Findings

- Production budget has a strong positive relationship with opening weekend revenue.
- Screen count has a moderate positive relationship with opening weekend revenue.
- Genre-wise analysis helps identify genres with higher average opening revenue.
- Revenue per screen helps measure the efficiency of a movie's theatrical release.

## Correlation Analysis

| Factor | Correlation with Opening Revenue |
|---|---:|
| Production Budget | 0.685 |
| Screen Count | 0.528 |

Production budget shows the **strongest relationship** with opening weekend revenue.

## Conclusion

The analysis shows that production budget is the strongest among the analysed numerical factors associated with opening weekend revenue. Screen count also has a positive relationship, while genre-based analysis provides useful information for distribution and marketing decisions.
