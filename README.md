🚗 NYC Motor Vehicle Collisions Analysis
This project analyzes motor vehicle collisions in New York City using historical crash data. The analysis uncovers trends, seasonal patterns, and anomalies, helping identify how collisions evolved over time, especially in light of events like the COVID-19 pandemic.

Time Series Decomposition

📊 Overview
Dataset: NYC Open Data Portal
Time Period: 2012–2024
Focus Areas:
Collision trends across years
Common contributing factors
Temporal patterns (seasonal/trend decomposition)
COVID-19's impact on traffic incidents
🧪 Project Workflow
Data Loading: NYC crash data imported using pandas
Cleaning: Handled nulls, standardized timestamps, extracted features (year, month)
EDA: Visualized top causes, borough-wise stats, and monthly distribution
Time Series Analysis: Applied seasonal decomposition to identify:
Long-term trends
Weekly/monthly seasonality
Residual outliers (unexpected spikes/dips)
📌 Tools Used
Python 🐍
Jupyter Notebook
pandas, matplotlib, seaborn – for analysis and plots
statsmodels – for time series decomposition
folium – for mapping
📷 Visualization Highlight
The plot above demonstrates time series decomposition on the daily number of collisions:

Trend: Decline post-2020 due to lockdowns
Seasonality: Weekly patterns visible across years
Residuals: Outliers due to specific events or anomalies
🚀 How to Run
Clone the repo
Open the notebook in Jupyter
Ensure the dataset CSV is in the same directory
Run the notebook step-by-step
git clone https://github.com/yashling/NYC-Collisions-Analysis.git
cd NYC-Collisions-Analysis
jupyter notebook NYC_motor_vehicle_collisions_crashes.ipynb
