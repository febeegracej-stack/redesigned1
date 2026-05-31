# Task 1: Data Cleaning and Preprocessing

## Objective

The objective of this task is to clean and preprocess a raw dataset containing missing values and inconsistent data to make it suitable for analysis.

## Dataset

**Dataset Name:** Netflix Movies and TV Shows

The dataset contains information about movies and TV shows available on Netflix, including title, director, cast, country, release year, rating, and duration.

## Data Cleaning Process

### 1. Missing Value Handling

Missing values were identified and replaced using appropriate placeholder values:

| Column | Replacement Value |
|----------|----------|
| director | Unknown |
| cast | Unknown |
| country | Unknown |
| date_added | Not Available |
| rating | Not Rated |
| duration | Unknown |

### 2. Duplicate Record Check

The dataset was checked for duplicate records.

**Result:** No duplicate rows were found.

### 3. Data Quality Verification

Column names and dataset structure were reviewed to ensure consistency and usability for further analysis.

## Data Quality Report

### Missing Values Before Cleaning

| Column | Missing Values |
|----------|----------:|
| director | 2634 |
| country | 831 |
| cast | 825 |
| date_added | 10 |
| rating | 4 |
| duration | 3 |

### Missing Values After Cleaning

All missing values in the identified columns were successfully handled.

### Duplicate Records

| Status | Count |
|----------|----------:|
| Before Cleaning | 0 |
| After Cleaning | 0 |

## Files Included

- netflix_titles.csv — Original dataset
- netflix_cleaned.xlsx — Cleaned dataset
- README.md — Project documentation
- screenshots/ — Screenshots of the cleaning process and results

## Tools Used

- Microsoft Excel / Google Sheets
- GitHub

## Outcome

The dataset was successfully cleaned and prepared for future data analysis, visualization, and machine learning tasks. Missing values were handled, data quality was improved, and the dataset is now ready for further processing.
