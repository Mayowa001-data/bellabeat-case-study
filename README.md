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

![Daily Activity](visuals/daily_trend.png)

Daily activity fluctuates significantly across users, showing inconsistent engagement.

---

### Weekday vs Weekend Activity

![Weekday vs Weekend](visuals/weekday_vs_weekend.png)

Activity levels are generally lower on weekends compared to weekdays.

---

### Steps vs Calories Relationship

![Steps vs Calories](visuals/steps_vs_calories.png)

A strong positive relationship exists between steps taken and calories burned.

---

### Activity Level Distribution

![Activity Distribution](visuals/activity_distribution.png)

Most users fall below optimal activity levels, indicating opportunity for improvement.

---

### Hourly Activity Patterns

![Hourly Activity](visuals/hourly_activity.png)

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

