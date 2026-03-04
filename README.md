# Kaggle Data Science Survey Analysis (2017–2021)

## Overview

This project performs **data cleaning, preprocessing, and exploratory data analysis (EDA)** on the **Kaggle Data Science Survey dataset (2017–2021)**. The objective of the analysis is to understand trends within the global data science community, including demographics, programming language usage, job roles, and salary patterns.

The dataset contains responses from **over 100,000 participants worldwide**, making it a valuable source for understanding the evolving landscape of data science and machine learning professionals.

Through structured data cleaning and analysis, the project extracts meaningful insights and visualizations that highlight patterns in **geographical distribution, gender representation, compensation, and technical skills**.

---

# Objectives

The main goals of this project are to:

* Clean and preprocess a real-world survey dataset
* Handle missing values and duplicate responses
* Transform categorical variables into machine-readable formats
* Convert salary ranges into numeric values for statistical analysis
* Perform exploratory data analysis to identify meaningful patterns
* Visualize insights related to the data science workforce

---

# Dataset

The dataset used in this project is the **Kaggle Data Science and Machine Learning Survey (2017–2021)**.

It includes information on:

* Age
* Gender
* Country
* Education level
* Job role
* Coding experience
* Compensation
* Programming languages used

The dataset is available from Kaggle:



---

#  Data Cleaning and Preprocessing

Before performing analysis, several preprocessing steps were applied to improve data quality:

### 1. Removing Metadata Row

The first row of the dataset contained survey question text rather than actual responses. This row was removed to ensure accurate analysis.

### 2. Handling Missing Values

Many columns contained missing values due to the survey structure (multi-select questions). Missing values were handled appropriately without introducing bias.

### 3. Removing Duplicate Responses

Duplicate rows were identified and removed to avoid skewing statistical results.

### 4. Cleaning Text Data

Text columns were cleaned by:

* Removing extra spaces
* Standardizing formatting
* Converting non-informative responses (e.g., *Prefer not to answer*) into missing values

### 5. Encoding Categorical Variables

Categorical variables such as **gender, country, and job role** were converted into numerical values using **Label Encoding** to enable statistical analysis.

### 6. Salary Conversion

Compensation values were originally recorded as ranges (e.g., `10,000–19,999`). These ranges were converted into numeric midpoint values so that averages and comparisons could be computed.

---

# 📈 Exploratory Data Analysis

Several analyses were conducted to identify patterns within the dataset.

## **1️.** Geographic Distribution of Respondents

The survey responses were heavily concentrated in certain regions. India and the United States contributed the largest number of respondents.

**Insight:**
The dataset is geographically imbalanced, meaning insights may reflect trends from highly represented countries.

---

## **2.** Gender Distribution

The gender distribution analysis shows a significant majority of respondents identifying as male, with a smaller proportion identifying as female or other gender identities.

**Insight:**
This highlights the continuing **gender imbalance in the data science and technology industries**.

---

## **3.** Average Salary by Job Role

The analysis of compensation by job role shows that **executive and managerial positions** (such as Chief Officer and Product Manager) report the highest average salaries.

**Insight:**
Leadership and managerial roles typically command higher compensation due to strategic responsibilities within organizations.

---

## **4.** Programming Language Popularity

The most commonly used programming languages among respondents were:

* Python
* SQL
* R
* Java
* C++

**Insight:**
Python and SQL dominate the data science ecosystem due to their strong support for data manipulation, machine learning, and database interaction.

---

## **5.** Programming Languages per Respondent

Analysis of the number of programming languages used per respondent shows:

* Average languages per respondent: **~1.84**
* Median languages used: **2**
* Most respondents use **1–3 programming languages**

**Insight:**
Data professionals tend to rely on a **small set of core tools rather than many programming languages**.

---

# Visualizations

The project includes several visualizations to support the analysis:

* Top countries participating in the survey
* Gender distribution of respondents
* Average salary by job role
* Most popular programming languages
* Distribution of programming languages used per respondent

These visualizations help reveal patterns and make the findings easier to interpret.

---

# Technologies Used

The project was implemented using the following tools and libraries:

* **Python**
* **Pandas** – data manipulation and analysis
* **NumPy** – numerical operations
* **Matplotlib** – data visualization
* **Scikit-learn** – categorical encoding

---




#  Key Takeaways

* The global data science community is highly concentrated in a few countries.
* There remains a noticeable gender imbalance in the field.
* Managerial roles typically earn higher salaries than technical roles.
* Python and SQL are the dominant programming languages in data science.
* Most professionals rely on a small set of programming languages rather than many.

---




