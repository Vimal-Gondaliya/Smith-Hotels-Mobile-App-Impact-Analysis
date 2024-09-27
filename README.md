# Smith Hotels Mobile App Impact Analysis

## Problem Statement
Smith Hotels is considering launching a new mobile app to enhance customer engagement and increase revenue. This project analyzes data from a live test to evaluate the app's effectiveness on customer spending behavior. The key questions include:
1. Will the app lead to increased customer spending?
2. How much of an increase in spending can be expected?
3. Does the app's effect on spending vary by customer characteristics?

## Business Background
Several hospitality companies have developed mobile apps to streamline reservations and enhance customer experience. A well-designed app can increase customer retention and revenue, while a poorly designed one may hurt business. In this context, understanding the app's impact is crucial for decision-making.

## Experiment Design
A before-after experimental design was employed with two groups of loyalty program customers:
- **Control Group**: 2000 customers tracked for one year without app exposure.
- **Treatment Group**: 2000 customers received the app and were tracked for another year.

## Objectives
To provide management with insights regarding:
- The potential increase in customer spending due to the app.
- Expected spending increases.
- Variations in app effects based on customer demographics.

## Project Tasks

### Part I: Data Preparation and Wrangling
- Load the dataset.
- Check for missing values and correct data types.

### Part II: Exploratory Data Analysis
- **Univariate Analysis I**: Analyze customer demographics (Gender, Age, Nationality, Loyalty Tenure).
- **Univariate Analysis II**: Analyze customer purchase behavior (Amount Spent, Number of Bookings).
- **Multivariate Analysis**: Examine relationships between customer characteristics and purchase behavior through pivot tables and visualizations. Conduct hypothesis testing on spending differences between genders.

### Part III: Statistical Analysis
- **After-Only Design**: Analyze treatment effects by comparing average spending of control vs. treatment groups post-app adoption.
- **Before-After Design**: Calculate the difference in spending before and after app adoption, and perform hypothesis testing on the treatment effect.

### Part IV: Executive Summary
- Summarize findings in non-technical language to address management's questions.

## Dataset Overview
Include a brief description of the dataset and its features.

## License
This project is licensed under the BSD 3-Clause License.

## Acknowledgments
Credit any sources or collaborators here.
