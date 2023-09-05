# Lyft Analytics Project :car: 

This project aims to analyze Lyft's driver data to determine the **Lifetime Value** of a driver to Lyft, considering various factors that influence this value. The project utilizes three CSV files, namely `driver_ids.csv`, `ride_ids.csv`, and `ride_timestamps.csv`, which contain relevant data about drivers, their rides, and ride timestamps. The analysis and findings will provide insights into driver behavior, longevity, and value generation.

## Objectives :dart:

1. **Calculate Driver's Lifetime Value:** Calculate the projected lifetime value of a driver to Lyft. This involves assessing the overall revenue generated from a driver's rides considering expenses and fee structures.

2. **Identify Key Factors:** Determine the main factors influencing a driver's lifetime value. These could include ride distance, ride duration, prime time, etc.

3. **Average Projected Lifetime:** Calculate the average projected lifetime of a driver. This metric represents the typical duration a driver continues driving with Lyft once onboarded.

4. **Segmentation Analysis:** Explore whether there are specific driver segments that outperform the average driver in terms of value generation.

5. **Business Recommendations:** Provide actionable recommendations based on insights derived from the analysis.

## Lyft Fare Calculation :page_facing_up:

Based on the reasearch on Lyft rate card (https://www.ridester.com/lyft-cost/)

## Analysis Steps :chart_with_upwards_trend:

1. **Data Preprocessing:** Clean and merge data files, handle missing values, and convert timestamps to appropriate formats.

2. **Feature Engineering:** Calculate ride fares based on the provided fare components and prime time information. Derive relevant metrics like total earnings, expenses, and net profit for each ride.

3. **Lifetime Value Calculation:** Compute the lifetime value of each driver by summing their net profits across all rides.

4. **Factors Analysis:** Analyze the impact of factors such as ride distance, ride duration, and prime time on lifetime value. Visualize relationships using graphs.

5. **Average Lifetime Calculation:** Determine the average duration a driver remains active on the platform after onboarding.

6. **Segmentation Analysis:** Identify driver segments with above-average lifetime value. Understand the characteristics that differentiate these segments.

7. **Business Recommendations:** Based on insights gained, provide actionable recommendations to Lyft for optimizing driver acquisition, engagement, and retention strategies.

## 📜 Full Python Code

You can access the complete R code for the project on GitHub:
[Lyft Python Code]([https://github.com/taoye0330/marketing-mix-modeling-project/blob/main/Marketing%20Mix%20Modeling.R](https://github.com/taoye0330/lyft-analytics-project/blob/main/lyft-analytics.ipynb)).


## 📢 Feedback & Contributions

Your feedback is invaluable! If you have any questions, suggestions, or contributions, please don't hesitate to reach out. Let's make this a collaborative effort! 🚀

---

Thank you for your interest and support!

Let's dive into the data and discover the road ahead for Lyft! :car:
