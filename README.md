# hotel_booking_cancellation_analysis

Analyzing hotel reservation data to understand booking patterns, cancellation rates, and revenue trends using Python.

# Overview
This project analyzes a comprehensive hotel booking dataset to identify the key factors that lead to reservation cancellations. The goal is to provide actionable insights for both City and Resort hotels to help them reduce cancellation rates and optimize their average daily rates (ADR).

# Business Objective
The main objectives of this project are:

- Analyze the proportion of cancelled vs. confirmed bookings.

- Compare cancellation patterns between City Hotels and Resort Hotels.

- Track the Average Daily Rate (ADR) across different months to identify seasonal pricing trends.

- Understand the relationship between lead time, customer type, and the likelihood of cancellation.

- Evaluate the impact of different market segments on reservation status.

# Dataset

The project uses the hotel_booking.csv dataset containing over 119,000 reservation records.
Important columns include:

- hotel

- is_canceled

- lead_time

- arrival_date_month

- adr

- market_segment

# Tools & Technologies
The analysis was performed using:

- Python

- Pandas 

- Matplotlib & Seaborn 

- Jupyter Notebook

# Data Cleaning & Preparation

Before performing analysis, several preprocessing steps were completed:

- Converted the reservation_status_date column into a datetime format to allow for accurate time-series comparisons.

- Dropped unnecessary personal information columns such as name, email, and phone-number to focus strictly on behavioral data.

- Handled missing values in columns like country and agent to maintain the integrity of the statistical summaries.

- Filtered out data entries where the Average Daily Rate (ADR) was zero or negative to remove outliers that would skew revenue analysis.

# Key Findings

- Cancellation Volume: City Hotels generally experience a higher volume of cancellations compared to Resort Hotels.

- Pricing Correlation: Average Daily Rates (ADR) fluctuate significantly by month, with clear peaks during holiday seasons.

- Market Behavior: Bookings made via specific market segments, such as "Groups," often show different cancellation tendencies than individual "Transient" bookings.

- Lead Time Impact: Reservations made far in advance often have a higher probability of being cancelled compared to last-minute bookings.

# Visualizations

<img width="720" height="511" alt="Screenshot 2026-03-09 155253" src="https://github.com/user-attachments/assets/e4a56e15-5ed4-4849-8037-2216ba40d481" />

<img width="949" height="498" alt="Screenshot 2026-03-09 155309" src="https://github.com/user-attachments/assets/8a0c7fc8-f3a6-4b29-b7dc-a39a7eecf0d4" />

<img width="1814" height="807" alt="Screenshot 2026-03-09 155334" src="https://github.com/user-attachments/assets/b860012c-e89a-4a56-a1b0-fe66b0a35510" />

<img width="1744" height="843" alt="Screenshot 2026-03-09 155358" src="https://github.com/user-attachments/assets/a3fe2e17-54c9-46b6-bca4-b43fe63b7454" />

<img width="1671" height="852" alt="Screenshot 2026-03-09 155422" src="https://github.com/user-attachments/assets/c048a597-9edd-41b8-81a1-40c7af643da1" />

<img width="853" height="814" alt="Screenshot 2026-03-09 155457" src="https://github.com/user-attachments/assets/5f3abbd8-673a-44e8-bf32-3c8d6730cd1b" />

# How to Run This Project
Clone the repository
git clone https://github.com/jannatulfeva/hotel_booking_cancellation-analysis.git

Install required libraries
pip install pandas matplotlib seaborn

Open and run the notebook
Run the notebook: hotel_booking_cancellation-analysis.ipynb
















