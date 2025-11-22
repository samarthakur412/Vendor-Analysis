# Vendor Analysis
📌 Overview

<img width="502" height="299" alt="BI dashboard" src="https://github.com/user-attachments/assets/f1b4e60e-1f51-4916-bf29-5a4fbc81ac04" />


This is an end-to-end Data Science project focused on vendor analysis. The project covers the full lifecycle of a data science workflow:

Ingesting raw vendor data into a database

Writing ingestion scripts for automation

Cleaning and preprocessing data

Performing Exploratory Data Analysis (EDA)

Conducting Hypothesis Testing to validate assumptions

Drawing actionable insights from the data

Preparing a final report for stakeholders

🎯 Objectives

Identify key trends and patterns in vendor performance

Validate business hypotheses using statistical testing

Provide data-driven recommendations to optimize vendor selection and management

Vendor-Analysis/
├── data/                 # Raw and cleaned datasets
├── ingestion/            # Data ingestion scripts
├── notebooks/            # EDA and hypothesis testing notebooks
├── reports/              # Final reports and insights
├── src/                  # Data cleaning & utility functions
├── requirements.txt      # Dependencies
└── README.md             # Project documentation

🛠️ Tech Stack

Programming: Python (Pandas, NumPy, SciPy)

Database: SQLite (can be adapted to PostgreSQL/MySQL)

Visualization: Matplotlib, Seaborn

Environment: Jupyter Notebooks

📊 Methodology

Data Ingestion

Automated loading of raw vendor data into a structured database

Data Cleaning

Handling missing values

Removing duplicates & outliers

Formatting columns (dates, numbers, categories)

Exploratory Data Analysis (EDA)

Distribution plots, correlation analysis

Trend analysis over time & vendor categories

Hypothesis Testing

Testing vendor performance differences (delivery time, price, quality)

Validating assumptions with statistical tests (t-tests, chi-square, ANOVA)

Insights & Reporting

Identified best performing vendors

Highlighted vendor inefficiencies

Suggested improvements for vendor selection strategy

🚀 How to Run

Clone the repository:

git clone https://github.com/samarthakur412/Vendor-Analysis.git
cd Vendor-Analysis


Install dependencies:

pip install -r requirements.txt


Set up the database (run provided SQL schema or ingestion script).

Run EDA & Hypothesis notebooks in notebooks/.

Explore results in the reports/ folder.

📌 Key Findings (Sample)

Certain vendors consistently deliver late → potential risk

High-rated vendors have significantly lower defect rates

Some product categories show strong seasonal demand fluctuations

Price differences between vendor groups are statistically significant

🔮 Future Work

Build predictive models for vendor reliability

Develop a vendor recommendation system

Create interactive dashboards for real-time monitoring

🤝 Contributing

Pull requests and suggestions are welcome!

📜 License

This project is licensed under the MIT License.

