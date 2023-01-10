<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>

<h3 align="center"><a href = "https://www.udacity.com/course/data-analyst-nanodegree--nd002"> Udacity Data Analyst Nanodegree </a></h3>
<h4 align="center">Project V: Communicate Data Findings</h4>

## Table of Contents
- [Project Overview](#project_overview)
- [Project Details](#details)
- [Key Insights for Presentation](#key)
- [Summary of Findings](#summary)

## Project Overview <a name="project_overview"></a>
Project Overview
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process.

- In Part I, Exploratory data visualization, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables.

- In Part II, Explanatory data visualization, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying my findings will be through transforming yomyur exploratory visualizations from the first part into polished, explanatory visualizations.

Finally, you will be generating a slideshow of the visualizations with jupyter notebook and the pdf file will be uploaded here.

## Project Details <a name="details"></a>
- Dataset:
The Dataset contains 113,917 loans, each loan has information on each borrower's annual percentage rate (APR), status, borrowed amount, debt, etc. Variables with missing values were dropped to make the Dataset more accurate. Outliers were also removed to provide more reliable Data. This investigation will be analyzing factors that could influence borrower's APR and what loans were taken by what type of borrowers.
The dataset can be download [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547358770029000)
- Explore the data: Feel free to explore the jupyter notebook where the dataset is visually, and programatically explored.
- Document the story: organized findings convey a story to present to an audience.
- Communicate the findings - a slide deck with my findings is prepared for a curious audience.

## Key Insights for Presentation <a name="key"></a>
<p> I've chosen key plots with high data-to-ink ratio for the presentation. The plots I've chosen shows distribution of main variables, Loan status, monthly income, Prosper rating and I've tried to tell a story what are major predictors for loan status and Prosper rating variables. <p />

## Summary of Findings <a name="summary"></a>
- After analyzing each variables. Borrowers's APR, Borrowers's score, rating, available bank card credit and creditscore were found to be negatively correlated to Borrower's APR. Adding that that, borrower' Scores (given from 0 to 11) gave the strongest negative relationship with borrower's APR.
- Borrowers with different letter ratings were also analyzed. It came out that borrowers with the lowerest rating(HR) received higher APR percentage, and borrower with high rating A(A) received lowers APR percentage. This differentiate groups of people in terms of APR received based on their rating and scores.
