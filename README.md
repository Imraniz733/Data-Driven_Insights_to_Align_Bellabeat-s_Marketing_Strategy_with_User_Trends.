# Data-Driven_Insights_to_Align_Bellabeat_Marketing_Strategy_with_User_trends.

## Table of Contents
- [Introduction](#introduction)
- [Data Description](#data-description)
- [Data Cleaning And Processing](#data-cleaning-and-processing)
- [Exploratory Data Analysis(EDA)](#exploratory-data-analysis-EDA)
- [Conclusion](#conclusion)
- [Recommendations](#Recommendations)
## Introduction 
#### This project analyzes data from Bellabeat, a wellness company that manufactures smart devices to promote a healthy lifestyle. Bellabeat’s smart devices track users' daily activities, providing valuable insights into their wellness habits. The goal of this analysis is to generate data-driven recommendations that can inform Bellabeat’s marketing strategies, helping the company better target its audience and enhance its market presence through a deeper understanding of user behavior.

## Data Description 
Fitbit Fitness Tracker Data
Source: Kaggle (CC0: Public Domain)[link](https://www.kaggle.com/datasets/arashnic/fitbit)

This dataset, provided by Mobius on Kaggle, includes detailed personal fitness tracker data from thirty Fitbit users who consented to share their data for analysis. The dataset records minute-level output on physical activity, heart rate, and sleep monitoring, along with daily summaries of activity and step counts. These insights allow for an in-depth exploration of users’ habits and wellness patterns.

Data integrity verification is essential to ensure the analysis is based on accurate and reliable information. By confirming the quality of this dataset, we can derive trustworthy insights that effectively address our research questions and inform actionable recommendations.

## Data Cleaning And Processing
#### Upon reviewing the files, I found that the "dailyactivity" dataset contains all the necessary data for a comprehensive analysis. This dataset includes information such as total steps, activity levels ranging from sedentary to active, calories burned, and total distance covered. These metrics provide valuable insights into high-level trends and daily activity patterns of users.
We began with two files containing daily activity data, each structured identically. After merging them, we conducted data cleaning by checking for null values and duplicate entries and standardizing date formats for consistency. With these steps completed, the data is now cleaned, organized, and ready for analysis.

## Exploratory Data Analysis(EDA)
#### 1. Distribution of Total Steps: 
- The most common step count appears to be around 0–5000 steps, indicating many individuals in this dataset are relatively inactive or have low daily step counts.
- As step counts increase, the frequency drops, showing that fewer people are highly active (10,000 steps or more).
- Some outliers or highly active individuals in the dataset recorded very high step counts (20,000–35,000), but they form a small minority.

#### 2. Active Distance Vs Calories Burned:
1. Positive Correlation with Calories:
- Very active distance has the strongest correlation with calories burned, which implies that users who engage in more intense physical activities burn more calories.
- Moderate and light activities also contribute to calorie burning, but not as significantly as very active movements.
2. Distribution of Activities:
- Most users are spending more time in light activities rather than very active ones.
- There is a notable difference in calorie burning between users who are more very active and those who are more lightly active.

#### 3. Average Time Spent in Different Acitivty Levels:
1. Very Active Minutes (Red Bar):
- Average time: 19 minutes. Represents low engagement in high-intensity exercises like running.
2. Fairly Active Minutes (Orange Bar):
- Average time: 13 minutes. Indicates low engagement in moderate activities such as brisk walking.
3. Lightly Active Minutes (Green Bar):
- Average time: 185 minutes. Shows moderate daily movement through casual walking and light tasks.
4. Sedentary Minutes (Gray Bar):
- Average time: 992 minutes (over 16 hours). Indicates that most of the day is spent in minimal physical activity.
The stark contrast between sedentary minutes and other activity levels suggests that users are overwhelmingly inactive for most of the day. The engagement in light activity is far greater than in moderate or vigorous activities.

#### 4. Caloric Expenditure During Sedentary Minutes Vs Very Active Minutes:
- While it's not a strict linear relationship, there seems to be a slight upward trend, indicating that people who spend more time sedentary tend to burn more calories, likely because of their body's basic metabolic needs. This also suggests that calorie burn might only sometimes be directly related to physical activity, as some users may have a higher natural calorie expenditure.
- The graph shows a generally positive relationship between Very Active Minutes and Calories Burned, with more active minutes typically leading to higher calorie burn. However, there is significant variation, especially at lower activity levels, indicating that factors like resting metabolism also play a role in total calories burned. This suggests that calorie burn is influenced by both active time and individual metabolic differences.

#### 5. Total Steps Over Time:
1. High Variability:
- Daily step counts fluctuate from 20,000–30,000 steps to below 5,000 steps.
2. Stable Trend:
- The 7-day moving average indicates consistent activity levels despite daily spikes.
3. Activity Peaks:
- Temporary increases in steps suggest specific events or more intense physical activity.
Most daily step counts remain within the 5,000–10,000 range, with no significant long-term trend.

## CONCLUSION
#### The insights derived from our analysis indicate that a significant portion of users demonstrate low levels of activity, as evidenced by their daily step counts, calories burned across various activities, and overall time spent in physical exercise. To promote a healthier lifestyle, it is essential to encourage users to engage in regular physical activity, aiming for a daily goal of 7,000 to 10,000 steps.

## RECOMMENDATIONS
1. PERSONALIZED GOAL SETTINGS:
- Dynamic goal adjustment based on user performance to gradually increase activity without overwhelming users.
- Introduce features like “Take 200 steps now” notifications or hourly reminders for short walks. Reward small achievements like completing short walking tasks.
- The app can remind users to stand, stretch, or walk for a few minutes every hour to reduce sedentary time.
- Promote the app’s ability to deliver actionable, real-time insights through notifications, personalized reports, and weekly goal-setting tips.
- Tailor messaging for office or remote workers, using slogans like “Turn Sitting Into Steps” or “Beat the Sedentary Slump”. Provide quick, desk-friendly exercises and tips to break up sedentary time.
2. SUBSCRIPTION PLANS:
- For highly active users, the app can offer advanced features like detailed activity breakdowns, workout insights, or performance analytics that focus on improving stamina, distance goals, and more advanced fitness tracking.
- offer advanced tools or features only available to higher tiers, such as enhanced analytics, customization options, or priority customer support.
3. EDUCATIONAL CONTENT ON TRENDING HEALTH TOPICS:
- Share small tips or articles about reducing sedentary time, such as improved energy levels, better health outcomes, and mental clarity, to raise awareness and provide actionable suggestions.
- Launch social challenges where users share their daily activity, steps, or calorie burn progress, encouraging social engagement. Create hashtags like #MyStepsJourney or #WalkYourWayToHealth to build a sense of collective achievement.
- Host regular webinars or live Q&A sessions with health experts on trending health topics, open to all users.
- Polls, Quizzes, and Stories, Use Instagram Stories and other social media features to run interactive quizzes, polls, and quick wellness tips to engage users. Create dedicated groups (on platforms like Facebook or LinkedIn) based on user interests, such as sleep health, nutrition, mental well-being, or fitness.
