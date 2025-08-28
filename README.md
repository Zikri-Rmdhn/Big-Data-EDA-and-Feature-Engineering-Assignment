# ✈️ Big Data Assignment: Feature Engineering on NYC Flights Data

### Project Overview
This project focuses on **feature engineering and exploratory data analysis (EDA)** using the [2013 NYC Flights dataset](https://www.kaggle.com/datasets/mahoora00135/flights).  

The primary objective was to **experiment with preprocessing and feature engineering techniques**.  
All steps were carried out **as if the main objective of the assignment was for flight delay analysis**, even though the main focus of this assignment was the exploration itself.  

To support this context, we applied various preprocessing strategies, created new features, and generated visualizations to better understand flight patterns and potential delay-related factors.  

The dataset contains information about all flights departing from **Newark (EWR)**, **LaGuardia (LGA)**, and **John F. Kennedy (JFK)** airports in New York City during the year 2013.  

---

### Group Members
- Sandhika Surya Ardianto  
- Muhammad Zikri Ramadhan *(me)*  

---

### Methods & Techniques
Throughout this project, we applied several approaches, including:

1. **Data Cleaning**  
   - Dropped irrelevant columns: `id`, `year`, `time_hour`, and `name`.  
   - Detected and removed duplicate records.  
   - Handled missing values by:  
     - Imputing `dep_time`, `arr_time`, and `air_time` using flight time relations.  
     - Recalculating `dep_delay`, `arr_delay`, and `air_time`.  
     - Filling categorical missing values using the most frequent value.  
   - Encoded categorical variables using **Label Encoding**.  
   - Removed outliers using the **IQR method**.  

2. **Feature Engineering**  
   - **isWeekend**: indicates if the flight took place on a weekend.  
   - **sched_air_time**: calculated scheduled airtime in minutes.  
   - **flight_category**: classified flights into Short, Medium, Long, and Ultra Long hauls.  
   - **sched_dep_category**: grouped departure times into 4 time blocks (midnight, morning, afternoon, evening).  

3. **Data Visualization**  
   - **Boxplots** to detect and compare outliers (before & after filtering).  
   - **Histograms** for feature distributions.  
   - **Heatmap** to analyze correlations across features.  
   - **Scatter plots** to visualize relationships, e.g., scheduled airtime vs. distance.  

---

### My Contributions
In this project, my primary responsibility was:  
- **Feature Engineering**  
  Designed and implemented new derived features (e.g., weekend indicator, flight duration categories, and departure time ranges), and evaluated their relevance for analyzing flight delays.  

I also contributed to:  
- **Data Cleaning & Preprocessing** → Assisted in handling missing values and feature selection to improve dataset quality and usability.  
- **Data Visualization** → Helped generate plots to reveal patterns in flight delays.  

These tasks allowed me to **strengthen my skills in data preprocessing, feature engineering, and exploratory data analysis (EDA)**, particularly in the context of **delay analysis**.  

---

### Presentation
During the presentation, we applied a simple storytelling approach:  
We first introduced the dataset and its relevance, then framed the project *as if* the ultimate goal was to analyze flight delays. We explained our workflow (data cleaning, feature engineering, visualization), and finally shared the engineered features, visualizations, and key insights. This experience also gave us valuable practice in **data storytelling and analytical communication**.

---

📌 *This project was developed as part of our **Big Data course assignment**.*
