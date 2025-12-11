# Nur Arsani – Data Analyst Portfolio

## About

I am Nur! I'm currently pursuing a degree in Data Science at UW–Madison with a strong interest in cleaning messy datasets, exploring patterns, and turning data into insights that matter. My goal after I graduate is to work in data analytics, ideally in the social impact or public health space. I am actively seeking opportunities in Data Analytics where I can apply my skills in data exploration, visualization, and stakeholder communication to solve real-world problems.

## Portfolio Projects

### 📊 Yellow Taxi NYC Report

**Goal:** To analyze how COVID-19 impacted NYC’s yellow taxi system by examining trends in trip volume, fare pricing, and trip duration from 2015 to 2025.

**Summary:** This project processed over 100 billion taxi trip records from the NYC Taxi and Limousine Commission, leveraging the Center for High Throughput Computing (CHTC) to run 1,388 parallel R jobs. We used statistical testing and geospatial visualizations to assess how the pandemic reshaped transportation patterns.
Key findings include:

📉 Trip volumes dropped by an average of 15,112 trips per month per zone after COVID-19 (p < 0.0001).

💰 Average fares rose by $5.24 per trip (p < 0.0001).

🧮 Duration became a stronger predictor of fare, particularly during pandemic years, indicating pricing sensitivity to time and context.

🗺️ Heatmaps revealed sharp declines in weekday, rush-hour demand during 2020–2021, with slow but incomplete recovery by 2024.

**Methods:**

Data cleaning and filtering of implausible records (e.g., 0 fares, <30s rides)

Zone-level monthly aggregation of summary statistics

Paired t-tests for pre-/post-COVID comparisons

Multiple regression models with interaction terms (e.g., year × borough)

Spatial-temporal heatmaps for demand visualization

**Skills & Tools:** Data cleaning, EDA, visualization, time series analysis  
**Technology:** matplotlib, seaborn,R, Paired t-tests, Linear Regression, CHTC (HTCondor), Data Wrangling, Geospatial Heatmaps

---

### 🔍 Gun Analysis Report

**Goal:** To analyze the lethality of gun violence incidents in the U.S. based on gun characteristics—specifically type of firearm (long vs. short barrel) and ownership status (stolen vs. not-stolen).

**Summary:** This project explores over 9,000 gun violence incidents from 2017, sourced from the Gun Violence Archive via James Ko's structured dataset. We focused on single-gun incidents to examine how firearm type and ownership status impact casualty rates (injuries + fatalities). Using two-sample t-tests and visualizations, we found:

Long guns (e.g., rifles, shotguns) caused statistically higher casualty rates per incident than short guns.

Not-stolen guns resulted in significantly more casualties per incident than stolen ones, suggesting legal gun ownership may be associated with higher lethality.

The analysis offers data-driven insights that could inform future policy discussions around firearm regulation and public safety.

**Skills & Tools:** Data wrangling and cleaning, Statistical inference (Welch’s t-tests), Causal analysis of categorical predictors, Data visualization and storytelling in R

  
**Technology:** R, ggplot2, dplyr, t-tests, data wrangling, statistical inference

---

## Contact

📧 Email: narsani@wisc.edu 
🔗 [LinkedIn](https://www.linkedin.com/in/nur-fa-aiqa-arsani-9784082b0/)  

---

