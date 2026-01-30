# Shipment Transit Performance Analysis (Python)

## Project Overview
This project analyzes courier and logistics shipment transit data to evaluate delivery efficiency,
facility movement, and overall network performance. The dataset is provided in a nested JSON format,
containing shipment-level details along with multiple tracking events for each shipment.

The objective of this project is to flatten complex JSON data, handle real-world data inconsistencies,
compute transit performance metrics, and generate business-ready analytical reports.

---

## Problem Statement
Logistics and courier companies require insights into how shipments move through their transit
network. This project answers key operational questions such as:
- How long does a shipment take from pickup to final delivery?
- How many logistics facilities does a shipment pass through?
- How efficient is inter-facility transit?
- How often are deliveries completed on the first attempt?
- How do express and standard services compare in performance?

---

## Key Features
- Parsing and processing nested JSON shipment data
- Flattening shipment-level and event-level information
- Handling real-world data edge cases:
  - Missing or null fields
  - Inconsistent timestamp formats
  - Incomplete event sequences
  - Missing address information
  - Duplicate events
- Identifying pickup, transit, out-for-delivery, and delivery events
- Calculating transit time and facility performance metrics
- Generating detailed and summary CSV reports

---

## Metrics Computed

### Shipment-Level Metrics
- Total transit time (in hours)
- Number of logistics facilities visited
- Inter-facility transit time
- Average hours per facility
- Express vs standard service classification
- Number of out-for-delivery attempts
- First-attempt delivery indicator

### Network-Level Metrics
- Average, median, and standard deviation of transit time
- Facility usage statistics
- Service-type comparison metrics
- Delivery success rates

---

## Output Files
- **transit_performance_detailed.csv**  
  Shipment-level detailed transit and delivery metrics

- **transit_performance_summary.csv**  
  Aggregated network-level performance statistics

---

## Technologies & Tools Used
- Python
- Pandas
- JSON
- Datetime
- Jupyter Notebook
- Data Analysis
- Data Cleaning
- Exploratory Data Analysis (EDA)

---

## Learning Outcomes
- Hands-on experience with real-world logistics data
- Working with complex nested JSON structures
- Writing clean, defensive, and readable Python code
- Converting raw tracking data into actionable business insights

---

## Disclaimer
This project was created for learning and portfolio purposes.
---
## Keywords
Python, Pandas, Data Analysis, JSON Parsing, Logistics Analytics, Shipment Tracking,
Transit Performance, Supply Chain Analytics, ETL, Exploratory Data Analysis,
CSV Reporting, Business Insights
