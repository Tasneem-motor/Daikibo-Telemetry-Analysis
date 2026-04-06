# Daikibo-Telemetry-Analysis
Tableau dashboard analysis of machine downtime across factories

📊 Daikibo Telemetry Data Analysis (Tableau)

📌 Project Overview

This project analyzes telemetry data collected from multiple Daikibo factories to identify machine downtime patterns and failure-prone devices. The goal is to determine which factory experienced the highest downtime and which machine types contributed the most to these failures.

🏭 Factories Analyzed

* Daikibo Factory Meiyo (Tokyo, Japan)
* Daikibo Factory Seiko (Osaka, Japan)
* Daikibo Berlin (Berlin, Germany)
* Daikibo Shenzhen (Shenzhen, China)

🛠 Tools & Technologies

* Tableau (Data Visualization & Dashboarding)
* Tableau Public (Dashboard Publishing)
* JSON Dataset


📂 Dataset Details

* Time Period: **May 2021**
* Data Frequency: **Every 10 minutes**
* Each record contains:

  * Factory Location
  * Machine Type
  * Machine Status (Healthy / Unhealthy)


🔍 Data Processing & Analysis

* Created a calculated field:

  **Unhealthy = 10 minutes of downtime for each unhealthy status**

* Built two key visualizations:

  1. **Down Time per Factory**
  2. **Down Time per Device Type**

* Designed an **interactive dashboard** where selecting a factory filters machine-level downtime.


📊 Key Insights

🏭 Factory with Highest Downtime

➡️ **Daikibo Factory Seiko (Osaka, Japan)**


⚙️ Machines with Most Breakdowns

➡️ **Laser Welder**
➡️ **Laser Cutter**

🌐 Live Dashboard

👉 https://public.tableau.com/views/daikibo-analysis/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

📁 Project Files

* `daikibo-analysis.twbx` → Tableau packaged workbook

🎯 Conclusion

The analysis highlights that the Seiko factory experienced the highest downtime, primarily driven by failures in laser-based machinery. These insights can help prioritize maintenance efforts and improve operational efficiency.

🚀 Future Improvements

* Add predictive maintenance using machine learning
* Perform time-based trend analysis
* Integrate real-time monitoring dashboards

---
