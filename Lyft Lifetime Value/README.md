# Lyft Driver Lifetime Value Project :car: 

This project aims to analyze Lyft's driver data to determine the **Lifetime Value** of a driver to Lyft, considering various factors that influence this value. The project utilizes three CSV files, namely `driver_ids.csv`, `ride_ids.csv`, and `ride_timestamps.csv`, which contain relevant data about drivers, their rides, and ride timestamps. The analysis and findings will provide insights into driver behavior, longevity, and value generation.

## Data Overview :clipboard:

### driver_ids.csv
- **driver_id:** Unique identifier for a driver
- **driver_onboard_date:** Date on which driver was onboarded

### ride_ids.csv
- **driver_id:** Unique identifier for a driver
- **ride_id:** Unique identifier for a completed ride
- **ride_distance:** Ride distance in meters
- **ride_duration:** Ride duration in seconds
- **ride_prime_time:** Prime time applied on the ride

### Ride_timestamps.csv
- **ride_id:** Unique identifier for a ride
- **event:** Type of event (requested, accepted, arrived, dropped off)
- **timestamp:** Time of event

**Assumptions:**
- All rides occurred in New York.
- All timestamps are in EDT.

## Objectives :dart:

1. **Calculate Driver's Lifetime Value:** Calculate the projected lifetime value of a driver to Lyft. This involves assessing the overall revenue generated from a driver's rides considering expenses and fee structures.

2. **Identify Key Factors:** Determine the main factors influencing a driver's lifetime value. These could include ride distance, ride duration, prime time, etc.

3. **Average Projected Lifetime:** Calculate the average projected lifetime of a driver. This metric represents the typical duration a driver continues driving with Lyft once onboarded.

4. **Segmentation Analysis:** Explore whether there are specific driver segments that outperform the average driver in terms of value generation.

5. **Business Recommendations:** Provide actionable recommendations based on insights derived from the analysis.

## Assumptions :page_facing_up:

Utilizing the provided Lyft rate card, we assume the following fare components:
- Base Fare: $2.00
- Cost per Mile: $1.15
- Cost per Minute: $0.22
- Service Fee: $1.75
- Minimum Fare: $5.00
- Maximum Fare: $400.00

## Analysis Steps :chart_with_upwards_trend:

1. **Data Preprocessing:** Clean and merge data files, handle missing values, and convert timestamps to appropriate formats.

2. **Feature Engineering:** Calculate ride fares based on the provided fare components and prime time information. Derive relevant metrics like total earnings, expenses, and net profit for each ride.

3. **Lifetime Value Calculation:** Compute the lifetime value of each driver by summing their net profits across all rides.

4. **Factors Analysis:** Analyze the impact of factors such as ride distance, ride duration, and prime time on lifetime value. Visualize relationships using graphs.

5. **Average Lifetime Calculation:** Determine the average duration a driver remains active on the platform after onboarding.

6. **Segmentation Analysis:** Identify driver segments with above-average lifetime value. Understand the characteristics that differentiate these segments.

7. **Business Recommendations:** Based on insights gained, provide actionable recommendations to Lyft for optimizing driver acquisition, engagement, and retention strategies.

## Getting Started :rocket:

To replicate the analysis and findings, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have the necessary libraries and packages installed (list them in a `requirements.txt` file).
3. Place the provided CSV files (`driver_ids.csv`, `ride_ids.csv`, `ride_timestamps.csv`) in a folder named `data`.
4. Run the analysis scripts in the specified order, as mentioned in the `Analysis Steps` section.

## Conclusion :clipboard:

This project aims to unravel the factors affecting Lyft driver lifetime value and provide valuable insights for Lyft's business strategy. By understanding what drives driver value and longevity, Lyft can optimize its operations, driver engagement, and overall success. 

Let's dive into the data and discover the road ahead for Lyft! :car:
