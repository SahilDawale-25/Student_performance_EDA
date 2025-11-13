# Student Habits vs Academic Performance Analysis

## Overview
This project analyzes a simulated dataset of 1,000 students to explore how lifestyle habits affect academic performance. The dataset includes daily habits such as study hours, sleep, social media usage, exercise, diet quality, mental health rating, attendance, and more, mapped against final exam scores.

The project includes:
- Data loading and cleaning
- Exploratory Data Analysis (EDA)
- Descriptive and Inferential Statistics
- Visualizations to identify trends and correlations
- Beginner-level Machine Learning (Linear Regression)

## Dataset
- File: `student_habits_performance.csv`
- Columns:
  - `student_id`, `age`, `gender`, `study_hours_per_day`, `social_media_hours`, `netflix_hours`
  - `part_time_job`, `attendance_percentage`, `sleep_hours`, `diet_quality`, `exercise_frequency`
  - `parental_education_level`, `internet_quality`, `mental_health_rating`, `extracurricular_participation`, `exam_score`

## Key Analysis and Insights
- **Correlation Analysis:** Study hours strongly correlate with exam scores, while social media and Netflix usage show negative correlations.
- **Inferential Statistics:** T-tests and ANOVA tests were performed to check the effect of gender, part-time jobs, exercise, and diet on exam scores.
- **Visualizations:** 
  - Histograms, Boxplots, and Countplots for distributions
  - Scatterplots and Regression plots for relationships
  - Stacked bar charts and barplots for categorical comparisons

## How to Run
1. Clone the repository.
2. Place `student_habits_performance.csv` in the project folder.
3. Open `Student_EDA_project.ipynb` in Jupyter Notebook.
4. Run the notebook cells sequentially to reproduce analysis and visualizations.

## Tools & Libraries
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- SciPy

## Project Purpose
- Understand relationships between lifestyle habits and academic performance
- Practice EDA, visualization, and beginner machine learning
- Create a polished project for GitHub portfolio
