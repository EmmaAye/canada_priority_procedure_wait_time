Canada-Wide Priority Procedure Wait Time Analysis
This project analyzes the wait times for six priority medical procedures across multiple provinces in Canada. The goal is to uncover disparities, identify contributing factors to long wait times, and recommend actionable insights through data analytics, visualization, and statistical modeling.

📌 Objective
Understand the distribution of wait times for priority procedures across Canadian provinces.

Formulate and test hypotheses on interprovincial disparities and the effect of surgery type and region.

Model factors contributing to long wait times using statistical techniques.

Visualize insights to inform policymakers and healthcare administrators.

🔍 Data Source
Data was collected from the Canadian Institute for Health Information (CIHI).

The dataset includes metrics like number of procedures, number completed within benchmark time, and median wait times by province and procedure type (hip replacement, knee replacement, etc.).

🧪 Methodology
Hypothesis Formulation: Defined 5 research questions and corresponding null/alternative hypotheses.

Data Cleaning: Removed missing and zero entries, transformed variables for analysis.

Lag Features: Created lag-based variables to detect historical trends in wait times.

Statistical Testing: Used t-tests and ANOVA to evaluate interprovincial differences and benchmark completion rates.

Modeling: Built predictive models using linear regression to assess features impacting long wait times.

📊 Tools Used
Python (Pandas, NumPy, SciPy, StatsModels, XGBoost, Random Forest)

Tableau and Python for dashboard visualization

Excel for initial exploration and summary

Jupyter Notebook

📈 Key Findings
Significant disparities exist across provinces, with Ontario and Nova Scotia frequently exhibiting longer wait times.

Procedures like knee replacement and hip replacement consistently face delays beyond benchmark targets.

Benchmark completion rates are closely tied to procedure type and regional factors.

📌 Deliverables
Hypothesis testing summary table and model results

Power BI interactive dashboard

Final report: DAMO_611_Project_Part3_Report.pdf

📦hospital-staffing-prediction
 ┣ 📂Dataset/                  # Cleaned and raw datasets
 ┣ 📂Python Files/             # Exploratory analysis and modeling in Jypyter Notebook
 ┣ 📂Tableau/                  # Tableau Visualization
 ┣ 📂Report/                   # Case Study Report Detailing Research Questions, Hypothesis Tests and Modeling
 ┣ 📜README.md                 # This file
🎯 Future Work


👥 Team Members
Naw Mu Aye
Aye, Thanda
Bui, Ngoc Mai Khanh
Pawar, Pratiksha Ravindra
