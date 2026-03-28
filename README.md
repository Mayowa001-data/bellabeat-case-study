# Bellabeat Data Analysis Case Study

## Project Summary

This project analyses smart device usage data to identify behavioural trends and provide actionable recommendations to improve user engagement for the Bellabeat app.

---

## Business Task

The objective of this analysis is to identify trends in smart device usage using Fitbit data and apply these insights to help inform Bellabeat’s marketing strategy and increase user engagement.

---

## Dataset

The dataset used is the Fitbit Fitness Tracker dataset (publicly available on Kaggle).
It contains data from 30 users, including:

* Daily steps
* Calories burned
* Activity levels
* Sleep tracking
* Minute-level activity logs

---

## Tools Used

* Excel (data cleaning & analysis)
* Pivot Tables
* Data Visualisation

---

## Data Cleaning & Preparation

The following steps were performed to prepare the data for analysis:

* Removed duplicate records
* Standardised inconsistent date formats (mm/dd/yyyy → dd/mm/yyyy)
* Converted datetime values from text to proper format
* Split date and time into separate columns
* Created new calculated columns:

  * Hour (from timestamp)
  * Day of week
* Checked for missing values and blanks
* Cleaned and standardised numeric formats

---

## Key Insights

### 1. Inconsistent Activity Levels

User activity levels vary significantly from day to day, indicating inconsistent exercise habits.

### 2. Lower Weekend Activity

Users tend to be less active on weekends compared to weekdays.

### 3. Strong Steps vs Calories Relationship

There is a strong positive correlation between steps taken and calories burned.

### 4. Low Activity Distribution

A large proportion of users fall into low-to-moderate activity levels and do not consistently meet recommended daily step targets.

### 5. Peak Activity Hours

User activity peaks during morning and evening hours, with low activity during late-night periods.

---

## Visualisations & Insights

### Daily Activity Trends

<img width="1898" height="1162" alt="Daily_activity_trend" src="https://github.com/user-attachments/assets/9b652e5b-f0cf-44d3-a055-a4db096e7cdf" />


Daily activity fluctuates significantly across users, showing inconsistent engagement.

---

### Weekday vs Weekend Activity

<img width="1653" height="995" alt="weekday_vs_weekend" src="https://github.com/user-attachments/assets/6b54bdad-4fcc-4733-8b3c-713887812d7c" />

Activity levels are generally lower on weekends compared to weekdays.

---

### Steps vs Calories Relationship

<img width="1653" height="998" alt="steps_vs_calories" src="https://github.com/user-attachments/assets/2fb0ac93-fd2d-4b10-8af9-b5f5d3d8edfe" />

A strong positive relationship exists between steps taken and calories burned.

---

### Activity Level Distribution

<img width="1651" height="991" alt="activity_level_distribution" src="https://github.com/user-attachments/assets/bcf0b220-2503-4525-9b08-417f9c44a749" />

Most users fall below optimal activity levels, indicating opportunity for improvement.

---

### Hourly Activity Patterns

<img width="1653" height="996" alt="hourly_activity" src="https://github.com/user-attachments/assets/ae44d1d8-d8c3-4875-af97-241e440c116e" />

Activity peaks during key hours of the day, especially mornings and evenings.

---

## Recommendations

Based on the analysis, the following recommendations are proposed for the Bellabeat app:

* Introduce personalised activity reminders to increase engagement
* Implement gamification features such as step goals and streaks
* Send notifications during low-activity periods
* Develop weekend-specific challenges to boost activity levels
* Use time-based insights to optimise user engagement strategies

---

## Conclusion

This analysis highlights key behavioural trends in smart device usage. By leveraging these insights, Bellabeat can improve user engagement, encourage healthier habits, and strengthen its overall marketing strategy.

---

## Data Files

The cleaned dataset used for this analysis can be found in the `/data` folder of this repository.


The cleaned dataset used for this analysis can be found in the `/data` folder of this repository.

