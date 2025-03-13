# Fitness & Sleep Analysis: Understanding the Relationship Between Exercise and Sleep
# Overview
This project explores the relationship between fitness activities (workouts, heart rate, calories burned) and sleep quality using self-collected data from Mac+ (for fitness) and Apple Health (for sleep tracking). The goal is to identify trends and correlations that may impact overall health and well-being.
# Motivation
Even with all the school work and social life I try to do fitness as much as I can and try to make it a habit to have a healthy lifestyle. But just going to the gym and working out is not enough. Matter of fact the most important thing in fitness is not lifting heavy weights or diet, it is actually sleep or sleep schedule. And that is where I lack. I can't seem to have a healthy sleep schedule because of all the things I told before (School, social life, etc.). And with this project I can clearly see the impact that sleep has on my fitness program and maybe it might motivate me to fix it. It would also help me with all the other stuff as well.
# Data Collection
Fitness Data (Mac+ app)
  -Metrics Collected: Workout duration, calories burned, heart rate, exercise type
  -Collection Method: Exported from Mac+
Sleep Data (Apple Health app)
  -Metrics Collected: Sleep duration, sleep stages (light, deep, REM), wake-up times
  -Collection Method: Extracted from Apple Health
Enrichment Data: Weather Conditions
  -Why? External factors like temperature and humidity may influence both sleep quality and exercise performance.
  -Data Source: Weather API for daily temperature, humidity, and air quality
# Methodology
 1. Data Preprocessing
  -Cleaning and structuring the exported data
  -Merging fitness, sleep, and weather datasets
 2. Exploratory Data Analysis (EDA)
  -Trends in sleep patterns and workout intensity
  -Identifying correlations (e.g., Does higher workout intensity improve sleep?)
 3. Statistical & Hypothesis Testing
  -T-tests or ANOVA to compare sleep quality on workout vs. non-workout days
 4. Machine Learning & Predictive Modeling 
  -Regression models to predict sleep duration based on exercise intensity
  -Clustering to find common sleep-exercise behavior groups
