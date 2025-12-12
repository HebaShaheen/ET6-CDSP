# Data Exploration
This project explores three datasets related to online education, adaptability, and time utilization. Each notebook Building upon the cleaned data from the `Cleaned_data` folder in`2_data_preparation` folder,descriptive statistics, and visual exploration.

### Dataset 1: 

File: **[`Cleaned-ONLINE EDUCATION SYSTEM REVIEW.csv`]**(https://github.com/HebaShaheen/ET6-CDSP/blob/main/2_data_preparation/Cleaned_data/Cleaned-ONLINE%20EDUCATION%20SYSTEM%20REVIEW.csv)

**Overview**

This notebook analyzes students’ learning conditions, engagement, and academic performance before and after online learning. Column names were standardized, and new features were created to capture technology access and engagement.

**Summary**

- Created tech_readiness based on device type and internet availability.

- Created engagement_cal using study hours, interaction, group study, and social media use.

- Split marks into numeric marks_before and marks_after.

- Compared engagement and performance across education levels.

- Visualized engagement distribution and changes in marks before vs after online learning.

### Dataset 2: 

File: **[`Cleaned-students_adaptability_level_online_education.csv`]**(https://github.com/HebaShaheen/ET6-CDSP/blob/main/2_data_preparation/Cleaned_data/Cleaned-students_adaptability_level_online_education.csv)

**Overview**

This notebook explores students’ adaptivity levels (Low, Moderate, High) in online education, focusing on demographic, institutional, and infrastructural factors.

**Summary**

- Examined overall dataset structure and category distributions.

- Converted age ranges and class duration into numeric midpoints.

- Mapped adaptivity levels and load-shedding to ordered numeric scales.

- Visualized distributions of all variables using histograms and bar charts.

### Dataset 3: 

File: **[`Exploration-Cleaned-COVID-19 Survey Student Responses.csv`]**(https://github.com/HebaShaheen/ET6-CDSP/blob/main/2_data_preparation/Cleaned_data/Cleaned-COVID-19%20Survey%20Student%20Responses.csv)

**Overview**

This notebook analyzes students’ daily habits and time utilization during COVID-19 online learning. The dataset was cleaned and reduced to focus on learning-related variables.

**Summary**

- Renamed columns and removed non-essential lifestyle variables.

- Focused on online class time, self-study, sleep, social media use, and class medium.

- Visualized numeric and categorical distributions to understand student time allocation.
