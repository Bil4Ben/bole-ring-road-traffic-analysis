# Bole Ring Road Traffic Analysis

## Overview
This project analyzes traffic flow based on field survey data collected at a fixed point along Bole Ring Road, Addis Ababa.

## Study Area
Bole Ring Road, Addis Ababa, Ethiopia (GPS: 8.983220, 38.780600)

## Objectives
- Analyze vehicle flow by type
- Identify peak traffic periods
- Estimate passenger movement
- Visualize traffic patterns

## Methods
- Data collection from field survey
- Data cleaning using Python (pandas)
- Time grouping (morning, midday, evening)
- Vehicle classification analysis
- Visualization using matplotlib

## Tools
- Python
- pandas
- matplotlib
- numpy

## Key Outputs
- Vehicle count bar charts
- Passenger estimation charts
- Time-based traffic summaries

## Results and Visualizations

### 1. Vehicle Count by Type
![Vehicle Count](figures/Vehicle_count_per_transport_mode.png)


## Conclusion

The traffic pattern observed in this study shows variation across different time periods, with relatively higher vehicle flow in the evening compared to midday and morning periods.

However, it is important to interpret these results in context. The data collection was conducted during a mix of normal and special days, including a Sunday and an election period. These conditions may have influenced mobility patterns.

- Notes on Traffic Variation (Election Days and Sundays)

Vehicle counts show noticeable reductions on Sundays and election days. This is mainly due to changes in travel behavior during these periods. On Sundays, many essential destinations such as churches and social gathering places (e.g., pool centers) are located within or near villages, allowing people to walk instead of using vehicles. Similarly, during election days, polling stations are typically set up close to residential areas, which reduces the need for transportation. As a result, these social and spatial factors lead to lower observed traffic volumes compared to normal working days.

Therefore, the observed traffic distribution may not fully represent a typical weekday traffic pattern. Instead, it reflects a combination of routine urban movement and event-driven travel behavior.

Despite these limitations, the study provides useful insight into how external social and political events can influence traffic flow patterns along the Bole Ring Road corridor.
