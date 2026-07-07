# Zomato Restaurant Data Analysis using Python

## 📌 Project Overview
This repository contains the comprehensive data analysis project for **Internship Task 1 at Alfido Tech**. The goal of this project is to analyze the Zomato Restaurant Dataset to uncover hidden insights regarding restaurant ratings, popular cuisines, location preferences, and factors affecting structural pricing models.

## 🗂️ Project Structure
The analysis is modularly structured across 5 organized notebook parts to maintain high code readability and clean engineering standards:
* **Part 1:** Data Loading and Initial Preprocessing
* **Part 2:** Data Cleaning (handling missing values, duplicate records, and data type conversions)
* **Part 3:** Exploratory Data Analysis (EDA) & Numerical Summary Statistics
* **Part 4:** Advanced Data Visualizations (Distribution plots, Correlation patterns, and text analysis)
* **Part 5:** Location Hotspot Analysis & Strategic Recommendations

## ⚙️ Technologies & Tools Used
* **Language:** Python 3.x
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn, WordCloud
* **Environment:** Google Colab

## 🧹 Key Data Cleaning Steps Performed
* Handled structural string formatting bugs and removed duplicated rows.
* Converted critical objects like `rate` (ratings) and `approx_cost(for two people)` into appropriate continuous numeric formats for calculation.
* Filtered out noisy structural missing values from targeted feature metrics.

## 📊 Visualizations Covered
1. **Restaurant Ratings Distribution (Histogram):** Pinpoints the density clusters of overall customer ratings.
2. **Popular Cuisines (Bar Chart):** Tracks down the highest demanded food categories across the platform.
3. **Cost vs Rating (Scatter Plot):** Maps consumer expenditure against user satisfaction scores.
4. **Correlation Heatmap:** Checks mathematical linear relationships between spatial columns.
5. **Cuisine/Dish Trends (Word Cloud):** Generates structural visibility of recurring text reviews and trending dishes.
6. **Geographic Distribution (Location Hotspots Bar Chart):** Visualizes top business zones with dense restaurant populations.

## 💡 Key Insights & Observations
* **Rating Patterns:** A dominant majority of restaurants secure solid baseline ratings settling optimally between **3.5 and 4.5**.
* **Demand Density:** Cuisines like Indian and Chinese completely dominate market choice and popularity metrics.
* **Pricing Fallacy:** Restaurant cost holds only a mild, moderate correlation matrix value ($r = 0.35$) with user ratings, proving that budget-friendly spots routinely match premium-tier quality satisfaction.

## 🚀 Strategic Business Recommendations for Alfido Tech
1. **Premium Onboarding:** Target elite partnerships with highly rated clusters in active merchant hubs.
2. **Dynamic Campaigns:** Deploy hyper-focused seasonal marketing weeks specializing in high-volume cuisines (e.g., Indian/Chinese).
3. **Value Section:** Formulate a curated in-app segment called *"Hidden Gems"* highlighting lower-cost, high-rating restaurant locations to drive massive conversion rates among student demographics.
4. **Logistics Optimization:** Prioritize physical delivery infrastructure setup and local ad-spends centered precisely within top-performing geographic hotspots.
5. **B2B Consultation:** Package backend metrics to upsell data-driven operational counseling to underperforming resturants holding sub-3.0 ratings in premium real-estate locations.
6.
