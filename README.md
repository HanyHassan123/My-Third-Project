##Cyber Security Threats Dataset

This dataset provides a detailed view of global cyber security threats and incidents. It includes various attributes such as attack sources, types, countries involved, financial impact, and defense mechanisms. The data has been enhanced with additional features to support advanced analytical and machine learning tasks.

Dataset Overview

File Name: cyber_security_threats.csv

Source: Kaggle

Rows: (Specify number if known)

Columns: 13

Tools Used: Python (Pandas, Matplotlib, Seaborn), Power BI

Status: Cleaned, analyzed, and visualized


Features

Feature	Description

attack_source	Origin or initiator of the attack (e.g., botnet, malware, insider).
attack_type	Type of cyberattack (e.g., DDoS, phishing, ransomware).
country	Country where the attack was initiated or reported.
defence_mechanism	Method used to mitigate or respond to the attack.
financial_loss	Estimated monetary loss due to the attack (USD).
incident_resolution_time	Time taken to resolve the incident (in hours or days).
number_of_affected_user	Number of users impacted by the attack.
security_vulnerability_type	Vulnerability exploited (e.g., SQL injection, zero-day, misconfiguration).
target_industry	Industry affected (e.g., finance, healthcare, education).
year	Year of occurrence.
threats_level (Added)	Custom-calculated level of threat (e.g., Low, Medium, High).
attacks_per_country (Added)	Aggregated number of attacks per country.


Use Cases

Exploratory Data Analysis (EDA)

Trend analysis of cybersecurity threats over the years

Predictive modeling of financial loss or resolution time

Clustering based on threat levels or regions

Visualization dashboards (Power BI, Tableau, etc.)

Cybersecurity risk analysis

Data storytelling dashboards

Machine learning experiments (e.g., predicting financial loss)

Corporate threat profiling


##The dataset was cleaned and processed using Python, including:

Handling missing values

Feature engineering (threats_level, attacks_per_country)

Data type conversions

Exploratory Data Analysis using Matplotlib & Seaborn


Visualization

The processed dataset was imported into Power BI for interactive dashboard creation. Key visuals included:

Threat distribution by country and industry

Yearly trends of attack types

Financial loss analysis per threat level

Top 10 vulnerable countries and industries




Example Insights

Top 5 countries with the highest number of cyberattacks

Most common types of attacks in the finance industry

Correlation between threat level and financial loss

Year-over-year growth of ransomware attacks


License

This dataset is provided for educational and research purposes only.

Author

Hany Hassan Ahmed
LinkedIn | alnagarwps@gmail.com
