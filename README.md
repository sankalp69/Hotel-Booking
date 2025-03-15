Hotel Booking Analysis - Exploratory Data Analysis (EDA)
GitHub
GitHub Link: [Hotel Booking Analysis Repository](https://github.com/sankalp69/Hotel-Booking)

📌 Project Overview
This project analyzes hotel booking data to uncover patterns, trends, and factors influencing booking cancellations. The dataset includes 119,390 entries with 32 features, covering bookings for both Resort Hotels and City Hotels from 2015 to 2017. The goal is to provide actionable insights to optimize hotel operations, reduce cancellations, and enhance profitability.

🎯 Business Objective
The hospitality industry is highly competitive, and hotels need data-driven strategies to retain customers. This EDA aims to:

Identify key booking trends (seasonality, customer preferences).

Understand factors driving cancellations (lead time, deposit type, market segment).

Provide recommendations to improve customer satisfaction and revenue.

📁 Dataset Description
Key Features:
Hotel Types: Resort Hotel vs. City Hotel.

Booking Status: is_canceled (1 = canceled, 0 = not canceled).

Temporal Data: Arrival dates (year, month, week), stay duration.

Customer Demographics: Adults, children, country of origin.

Operational Metrics: Lead time, deposit type, customer type, ADR (Average Daily Rate).

Data Challenges:
Missing values in company (94.3%), agent (13.7%), and country (0.4%).

High dimensionality with mixed data types (numerical, categorical).

🔍 Key Insights
1. Cancellation Analysis
27.5% of bookings were canceled.

Longer lead times correlate with higher cancellation rates.

Deposit type (No Deposit vs. Non-Refundable) significantly impacts cancellation likelihood.

2. Seasonal Trends
Peak booking months: July and August.

Resort hotels see higher demand in summer, while city hotels are busier during business months.

3. Customer Behavior
Transient customers (non-contract) form the majority (80%).

Repeat guests account for only 3.2% of bookings, highlighting retention opportunities.

4. Revenue Insights
City hotels have a higher ADR (Average Daily Rate) than resort hotels.

Special requests (e.g., parking, meals) correlate with lower cancellation rates.

📊 Visualization Highlights
The Jupyter notebook includes visualizations such as:

Heatmaps for missing values.

Monthly booking/cancellation trends.

Correlation matrices for cancellation factors.

Distribution of lead times and customer types.

🛠️ Installation & Usage
Prerequisites
Python 3.6+

Libraries: pandas, numpy, matplotlib, seaborn

Steps:
Clone the repository:

bash
Copy
git clone https://github.com/sankalp69/Hotel-Booking.git
Install dependencies:

bash
Copy
pip install pandas numpy matplotlib seaborn
Run the Jupyter Notebook:

bash
Copy
jupyter notebook Hotel_Booking_Analysis_project.ipynb
📂 Files
Hotel_Booking_Analysis_project.ipynb: Full EDA workflow (data cleaning, analysis, visualizations).

Hotel Bookings.csv: Raw dataset (not included in the repo due to size; download here).

👨💻 Contributor
Sankalp Patekar
GitHub

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
