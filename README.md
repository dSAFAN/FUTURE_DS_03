# eCommerce Conversion Funnel Analysis

## 📌 Project Overview
This project involves building an automated, end-to-end Python data pipeline to analyze massive eCommerce event logs (over 50 million rows).
The goal of the analysis is to calculate unique user conversion rates across a standard sales funnel (**View → Intent → Purchase**) and segment the performance by brand and price tier.

## 🛠️ Tech Stack & Skills Demonstrated
* **Language:** Python
* **Libraries:** Pandas (Memory optimization, Vectorized operations, Categorical data types)
* **Tools:** Jupyter Notebook, Git, GitHub
* **Concepts:** ETL Pipeline design, Funnel metrics, Drop-off rate calculation, Data cleaning

## 📊 Quick Executive Findings
* **The Top-of-Funnel Leak:** Across all months analyzed, the steepest drop-off occurs early, with roughly **84%** of product views failing to convert into shopping cart intent.
* **Price Sensitivity:** Products in the "Medium" price tier consistently exhibit the highest intent-to-purchase conversion rates (averaging ~99%), heavily outperforming low-tier and high-tier items.
* **Brand Dominance:** Apple and Samsung drive the highest volume of traffic, but conversion efficiency varies wildly across niche brands.

## 📂 Deep-Dive Monthly Reports
To see the complete statistical breakdown, brand performance leaderboards, and business recommendations, please read the full monthly reports below:

* 📄 **[Read the October 2019 Analysis Report](reports/funnel_analysis_report_OCT_2019.md)**
* 📄 **[Read the November 2019 Analysis Report](reports/funnel_analysis_report_NOV_2019.md)**

## 💻 Exploring the Code
The automated data processing pipeline, including memory-efficient data loading and dynamic segmentation algorithms, can be found here:
* **[View the ETL Pipeline Notebook](notebooks/01_funnel_eda.ipynb)**
