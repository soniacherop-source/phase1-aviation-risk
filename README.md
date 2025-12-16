Aviation Risk Analysis
 Overview

This project analyzes historical aviation accident data to identify aircraft types and operational factors associated with lower accident severity. The goal is to provide data driven recommendations to support a company planning to enter the aviation industry by purchasing and operating aircraft for commercial and private use.

The analysis focuses on identifying lower-risk aircraft manufacturers, high-risk phases of flight, and long-term accident trends to inform safer and more cost-effective business decisions.

Business Understanding

The company seeks to expand into aviation operations but lacks insight into the safety risks associated with different aircraft and flight conditions.

Key Business Questions

-Which aircraft manufacturers and models are associated with lower fatal injury rates?

-Which phases of flight present the highest safety risks?

-How have aviation accident trends changed over time?

-The primary stakeholder for this analysis is the Head of the Aviation Division, who will use these insights to guide aircraft acquisition and operational planning.

Data Understanding

The dataset is sourced from the National Transportation Safety Board (NTSB) and contains records of aviation accidents and selected incidents from 1948 to 2023 in the United States and international waters.

Key Variables Used

-Aircraft make and model

-Phase of flight

-Purpose of flight

-Injury severity (fatal, serious, minor, uninjured)

-Event date (used to analyze trends over time)

Data Preparation and Analysis

The data was cleaned and prepared using pandas in Python.
Key preparation steps included:

-Selecting relevant columns related to aircraft, injuries, and operations

-Handling missing injury values by replacing them with zero

-Removing records missing critical categorical information

-Creating a Year variable from the event date for trend analysis

-The analysis focuses on descriptive statistics and aggregations to assess aviation risk.

Key Visualizations

The following visualizations were created to answer the business questions:

-Average Fatal Injuries by Aircraft Manufacturer
Identifies aircraft manufacturers associated with lower fatal injury rates.

-Average Fatal Injuries by Phase of Flight
Highlights phases of flight that present the highest operational risk.

-Number of Aviation Accidents Over Time
Shows long-term accident trends to assess changes in aviation safety.

These same visualizations are included in the notebook, presentation, and Tableau dashboard for consistency.

Interactive Tableau Dashboard

An interactive Tableau dashboard was created to allow users to explore aviation risk across different dimensions, including year and purpose of flight.

🔗 Tableau Dashboard Link:
👉 https://public.tableau.com/views/AviationRiskAnalysis_17658707461710/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Conclusions and Recommendations
Key Findings

-Certain aircraft manufacturers consistently show lower average fatal injury rates.

-Takeoff, approach, and landing phases present higher safety risks than cruise.

-Aviation accidents have generally declined over time, reflecting improvements in safety standards.

Business Recommendations

-Prioritize acquiring aircraft from manufacturers with historically lower fatal injury rates.

-Invest in pilot training and safety protocols focused on high-risk phases of flight.

Use historical accident trends to guide long-term fleet and operational strategy.

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

Tools Used

-Python (pandas, matplotlib, seaborn)
-Jupyter Notebook
-Tableau Public
-GitHub

Author

Sonia Cherop
