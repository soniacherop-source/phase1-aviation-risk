Aviation Risk Analysis

 Author : Sonia CHEROP
 
Project Overview

This project analyzes historical aviation accident data to identify aircraft types and operational factors associated with lower accident severity. The goal is to provide data driven recommendations to support a company planning to enter the aviation industry by purchasing and operating aircraft for commercial and private use.

The analysis focuses on identifying lower-risk aircraft manufacturers, high-risk phases of flight, and long-term accident trends to inform safer and more cost-effective business decisions.

Business Understanding

The company seeks to expand into aviation operations but lacks insight into the safety risks associated with different aircraft and flight conditions.

Key Business Questions

1.Which aircraft manufacturers and models are associated with lower fatal injury rates?

2.Which phases of flight present the highest safety risks?

3.How have aviation accident trends changed over time?

Data Understanding

The dataset is sourced from the National Transportation Safety Board (NTSB) and contains records of aviation accidents and selected incidents from 1948 to 2023 in the United States and international waters.

Key Variables Used

.Aircraft make and model

.Phase of flight

.Purpose of flight

.Injury severity (fatal, serious, minor, uninjured)

.Event date (used to analyze trends over time)

Data Preparation 

The data was cleaned and prepared using pandas in Python.
Key preparation steps included:

.Removing or handling missing values

.Selecting relevant columns for analysis

.Renaming columns for clarity

.Creating a cleaned dataset for analysis and visualization

Data Analysis and Insights

Key findings from the analysis:

Some aircraft manufacturers consistently show lower average fatal injuries

Takeoff and landing phases are associated with higher accident severity

Accident trends vary across different time periods

These insights help identify lower-risk aircraft options and operational risk factors.

Interactive Tableau Dashboard

An interactive Tableau dashboard was created to visualize:

.Aircraft manufacturers with the lowest fatal injury risk

.Accident trends over time

.Risk distribution across phases of flight

🔗 Tableau Dashboard Link:
https://public.tableau.com/views/AviationRiskAnalysisDashboard_17660454152630/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Conclusions
This project demonstrates how data analysis and visualization can support safer aircraft acquisition and operational decisions. The insights provide a strong foundation for risk-aware entry into the aviation industry.

Repository Structure
aviation-risk-analysis/
│
├── data/
│   └── AviationData.csv
│
├── notebook/
│   └── aviation_risk_analysis.ipynb
│
├── images/
│   └── visualizations.png
│
├── presentation.pdf
├── .gitignore
└── README.md

How to run the project

1.Clone the repository

2.Install required Python libraries (pandas, numpy, matplotlib, seaborn)

3.Open the Jupyter Notebook and run cells sequentially

Tools Used

-Python (pandas, matplotlib, seaborn)

-Jupyter Notebook

-Tableau Public

-GitHub


Sonia Cherop
