# Bellabeat Data Analysis (in R)

## Overview
This repository hosts an R script dedicated to the analysis of fitness data from "Fitbit Fitness Tracker Data". The dataset generated by respondents to a distributed survey via Amazon Mechanical Turk between 03.12.2016-05.12.2016. Thirty eligible Fitbit users consented to the submission of personal tracker data, from various health metrics, including daily activity, calorie burn, sleep patterns, and heart rate. The goal is to draw insights that could enhance Bellabeats products, which is a high-tech company that manufacturers health-focused smart devices. Based on the results of the analysis Bellabeats could improve their offerings and influence in their marketing strategy.

## About the Analysis
* The R script begins with the **Prepare Phase**, where data from different CSV files is loaded and inspected for structure and quality.
* In the **Process Phase**, the data undergoes cleaning, including the removal of missing values and duplicates, and transforming date formats for time series analysis, also additional columns were created.
* The **Analysis Phase** includes:
  * Performing summary statistics about each data frame
  * Calculating average weekly metrics for activity and sleep.
  * Calculating average daily metrics for activity and steps.
  * Classification of Participants by User Type and Sleeper Type.
  * Correlation analysis between total steps and calorie burn and other metrics.
* The **Visualization** Part employs ggplot2 to graphically represent all the above analysis from calculating average trends over time to Correlation analysis.

## Results and Insights
* This project provided valuable insights into the correlation between physical activities and other health metrics.
* Key patterns and trends were identified that allowed us to determine the optimal time for activity and weekly changes in user habits.
* For a detailed report on the analysis and results, including real-world applications and in-depth insights, visit my blog post on Hashnode: [Bellabeat Data Analysis (in R)](https://dilshodanalyst.hashnode.dev/bellabeat-data-analysis-in-r).

## About the Author
Dilshod Akhrorov is a data enthusiast with a passion for turning data into actionable insights. With prior experience in data analysis and knowledge in Environmental science, Dilshod is ready to unlock valuable insights from data and drive changes in our Data Driven World.

## Contact
Connect with Dilshod Akhrorov on [LinkedIn](https://www.linkedin.com/in/dilshod369/).
Follow Dilshod Akhrorov's blog on [Hashnode](https://hashnode.com/@Dannode) for more insights and articles on Data Analytics.

## Acknowledgements
This project is part of Dilshod Akhrorov's certification on [Google Data Analytics](https://www.coursera.org/professional-certificates/google-data-analytics) and is used for educational purposes. The data used is publicly available and was provided by [FitBit Fitness Tracker Data]( https://www.kaggle.com/datasets/arashnic/fitbit).
