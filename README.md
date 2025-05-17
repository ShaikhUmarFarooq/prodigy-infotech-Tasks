# 📊 Prodigy InfoTech – Data Science Internship

Welcome to my official repository for the **Prodigy InfoTech Data Science Internship**, where I completed a series of real-world tasks using Python, covering data cleaning, analysis, visualization, sentiment analysis, and pattern recognition.

📅 **Internship Duration:** April – May 2025  
🎓 **Name:** Shaikh Umar Farooq  
🏫 **Branch:** B.Tech CSE (AIML), 3rd Year – DBATU University  
🔗 **Organization:** [Prodigy InfoTech](https://prodigyinfotech.dev/)  

---

## 📌 Internship Tasks

### ✅ Task 1: Data Visualization

**Objective:**  
Create a bar chart or histogram to visualize the distribution of a categorical or continuous variable.

**Tools Used:** Python, Matplotlib, Seaborn  
**Key Outputs:**  
- Bar chart of gender count  
- Histogram of age distribution  

📁 File: `task1_visualization.ipynb`

---

### ✅ Task 2: Data Cleaning and EDA on Titanic Dataset

**Objective:**  
Perform data cleaning and exploratory data analysis on the Titanic dataset from Kaggle.

**Dataset:** [Titanic Dataset – Kaggle](https://www.kaggle.com/c/titanic/data)  
**Key Steps:**
- Handling missing values (Age, Embarked)
- Dropping irrelevant columns (Cabin)
- Visualizing survival patterns by gender, class, age
- Heatmap of correlations

**Insights:**  
- Females and first-class passengers had higher survival rates  
- Kids and young adults survived more than elders

📁 File: `task2_titanic_eda.ipynb`

---

### ✅ Task 3: Sentiment Analysis on Twitter Data

**Objective:**  
Analyze social media tweets to classify them into Positive, Negative, and Neutral sentiments.

**Dataset:** [Twitter Entity Sentiment Analysis – Kaggle](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)  
**Key Steps:**
- Dropped null and duplicate tweets
- Visualized sentiment distribution using countplot
- WordClouds for each sentiment group
- Sentiment analysis across different entities/brands

**Insights:**  
- Most tweets were neutral  
- Positive tweets were slightly more than negative  
- Certain brands received more positive attention

📁 File: `task3_sentiment_analysis.ipynb`

---

### ✅ Task 4: Traffic Accident Data Analysis

**Objective:**  
Analyze traffic accident data and visualize contributing factors like road conditions and weather.

**Dataset:** [Traffic Accident Data with Weather Conditions – Kaggle](https://www.kaggle.com/datasets/bismasajjad/traffic-accident-data-with-weather-conditions)  
**Key Steps:**
- Analyzed accident severity distribution
- Visualized top weather conditions during accidents
- Identified top 10 accident-prone states and cities
- Visualized visibility vs severity using box plots

**Insights:**  
- Most accidents occurred under "Clear" weather  
- Severity 2 was the most common  
- Urban areas had higher accident density

📁 File: `task4_traffic_accident_analysis.ipynb`

---

### ✅ Task 5: Road Accident Analysis – Pattern Detection

**Objective:**  
Analyze traffic accident data to identify patterns related to **road conditions**, **weather**, and **location**. Visualize **accident hotspots** and contributing factors using Python.

**Dataset:** [Traffic Accident Data with Weather Conditions – Kaggle](https://www.kaggle.com/datasets/bismasajjad/traffic-accident-data-with-weather-conditions)

**Key Steps:**
- Loaded dataset with features like `Severity`, `Weather_Condition`, `Visibility`, `State`, `City`, `Latitude`, `Longitude`
- Cleaned and filtered missing values
- Visualized severity distribution, weather trends, and state-wise accident counts
- Created interactive accident hotspot map using Plotly

**Visualizations Used:**
- Countplot for Severity levels
- Bar charts for top Weather Conditions
- Bar chart for States with most accidents
- Scatter Mapbox for accident hotspot visualization (using Latitude & Longitude)

**Insights:**
- Severity level 2 was most frequent  
- Most accidents occurred in "Clear", "Overcast", and "Rain" weather  
- States like California, Texas, and Florida had highest accident counts  
- Hotspots were mostly in urban areas (based on plotted locations)

📁 File: `task5_accident_hotspots_analysis.ipynb`

---

## 📂 Folder Structure

