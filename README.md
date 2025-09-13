**Health Analytics Dashboard**


📌 **Project Overview**
This project analyzes Obsessive-Compulsive Disorder (OCD) patient data using SQL for data preparation and Power BI for visualization.
The goal is to provide data-driven insights into OCD diagnosis trends, patient demographics, and behavioral patterns to support healthcare professionals, researchers, and policy makers in making informed decisions.


🎯 **Business Problem**
OCD is a mental health condition that affects individuals differently across gender, ethnicity, and behavioral patterns. Healthcare providers often struggle to:
Identify which groups are most affected,
Understand common obsession and compulsion types,
Track trends in diagnoses over time,
Compare severity scores (Y-BOCS) across demographics.
This project resolves these challenges by creating a data analytics solution that highlights key patient insights.


🛠️ **Tech Stack**
SQL (MySQL/Workbench) – Data cleaning, transformation, and aggregation.
Power BI – Interactive dashboard visualization.
Dataset – OCD patient dataset (sample, anonymized).


📊 **Key Insights & Features**

🔹 From SQL Analysis
Gender Distribution: Patient count split between Male & Female with average obsession scores.
Ethnicity Analysis: Patient counts by ethnicity with respective average scores.
Diagnosis Trends: Month-on-Month patient diagnosis trends.
Obsession Types: Most common obsessions (e.g., hoarding, contamination) with average scores.
Compulsion Types: Most common compulsions (e.g., washing, checking, praying).

🔹 From Power BI Dashboard

Yearly Patient Trends – Line chart showing patient counts across years.
Gender Distribution – Donut chart highlighting male vs female ratios.
Ethnicity Breakdown – Bar chart with patient counts and scores across ethnic groups.
Compulsion Type Analysis – Bar chart of different compulsion types.
Obsession vs Score – Line + bar visualization comparing obsession counts with severity scores.

📈 **Business Value**
Enables healthcare professionals to identify high-risk groups.
Provides policy makers with insights into prevalence across demographics.
Helps in designing targeted treatment plans for common obsessions/compulsions.
Tracks diagnosis trends for resource allocation in mental health services.

🚀**How to Use**
Clone the repository:
git clone https://github.com/<your-username>/HealthCare-Data-Analytics.git
cd HealthCare-Data-Analytics

Import the SQL script:
source sql_code_health_data.sql;

Open the Power BI file Health_Analytics.pbix.
Explore the interactive dashboard.

📸 **Dashboard Preview**

<img width="1368" height="800" alt="image" src="https://github.com/user-attachments/assets/969979fd-5b34-429a-8b98-4c290fb82ec1" />



**📂 Repository Structure**
├── sql_code_health_data.sql    # SQL queries for data analysis
├── Health_Analytics.pbix       # Power BI dashboard
├── README.md                   # Project documentation
└── dashboard_preview.png       # Dashboard screenshot

📌 **Future Improvements**
Automate data refresh in Power BI.
Add predictive modeling for OCD risk.
Expand dataset with more demographic variables.


