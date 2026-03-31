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

Daily step counts fluctuate significantly, while calories burned remain relatively stable, suggesting that baseline metabolic activity contributes consistently to calorie expenditure regardless of step variation.

### 2. Lower Weekend Activity

Activity levels are highest midweek and decline towards the weekend, with Sunday showing the lowest engagement.

### 3. Strong Steps vs Calories Relationship

There is a clear positive correlation between steps taken and calories burned, reinforcing that increased physical activity leads to higher energy expenditure.

### 4. Low Activity Distribution

A large proportion of users fall into low-to-moderate activity levels and do not consistently meet recommended daily step targets.

### 5. Peak Activity Hours

User activity peaks during early morning hours and shows a secondary increase in the evening, suggesting that users are most active before work and after typical working hours.

### Overall

These insights highlight clear behavioural patterns that can be leveraged to improve user engagement and encourage healthier habits through targeted interventions.

---

## Visualisations & Insights

### Daily Activity Trends


<img width="1898" height="1162" alt="Daily_activity_trend" src="https://github.com/user-attachments/assets/6ec31cba-67b1-4b4e-a7ea-c9a985a50d07" />


Daily activity fluctuates significantly across users, showing inconsistent engagement.

---

### Weekday vs Weekend Activity

<img width="1653" height="995" alt="weekday_vs_weekend" src="https://github.com/user-attachments/assets/ca0624bf-b10b-453a-aaba-6ddf056f6051" />

Activity levels are generally lower on weekends compared to weekdays.

---

### Steps vs Calories Relationship

<img width="1653" height="998" alt="steps_vs_calories" src="https://github.com/user-attachments/assets/b9255446-38e1-4a52-a88b-42db1225aaab" />

A strong positive relationship exists between steps taken and calories burned.

---

### Activity Level Distribution

<img width="1653" height="996" alt="activity_level_distribution" src="https://github.com/user-attachments/assets/f83225b5-7595-4a70-8d23-6aeadf9a85ab" />

Most users fall below optimal activity levels, indicating opportunity for improvement.

---

### Hourly Activity Patterns

<img width="1653" height="996" alt="hourly_activity" src="https://github.com/user-attachments/assets/b5251ec6-8a68-4b8c-8119-33ae20e10943" />

Activity peaks during key hours of the day, especially mornings and evenings.

---

## Recommendations

Based on the analysis, the following data-driven recommendations are proposed for the Bellabeat app:

### 1. Target Low-Activity Users

The majority of users fall into the low activity category.
Bellabeat should introduce personalised step goals, beginner-friendly challenges, and progress tracking to help inactive users gradually increase their activity levels.

---

### 2. Leverage Peak Activity Times

User activity peaks during early mornings and evenings.
Bellabeat can send notifications, workout suggestions, and reminders during these high-engagement periods to maximise user interaction and habit formation.

---

### 3. Address Weekend Activity Drop

Activity levels decline towards the weekend, particularly on Sundays.
Bellabeat should introduce weekend-specific challenges, incentives, and reminders to encourage users to stay active during these periods.

---

### 4. Reinforce Activity–Calorie Relationship

There is a strong positive correlation between steps and calories burned.
The app should visualise this relationship clearly to motivate users by showing how increased movement directly impacts calorie burn and overall health.

---

### 5. Improve Consistency in User Behaviour

Daily activity trends show significant fluctuations in step counts.
Bellabeat can implement streak features, habit tracking, and consistency-based rewards to encourage regular daily activity.

---

### 6. Utilise Time-Based Engagement Strategies

Periods of low activity (e.g., late night and mid-day dips) present opportunities for intervention.
Bellabeat can send timely nudges or reminders during these low-activity windows to re-engage users.

---

## Conclusion

This analysis highlights key behavioural trends in smart device usage. By leveraging these insights, Bellabeat can improve user engagement, encourage healthier habits, and strengthen its overall marketing strategy.

---

## Data Files

The cleaned dataset used for this analysis can be found in the `/data` folder of this repository.

