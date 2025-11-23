 Customer Risk Analysis – Power BI Project
🔹 Overview

This project focuses on analyzing credit card customers to identify risk patterns, understand customer behaviour, and assist banks in making data-driven decisions regarding risk categories.
The analysis includes EDA in Python, creation of interactive Power BI dashboards, and deriving key insights using different slicers such as Age, Gender, Income Band, Occupation Group, and Risk Category.

🔹 Objectives

Identify customer segments with high vs. low risk.

Understand the impact of demographics (age, gender) on risk.

Analyze income levels, occupation groups, and credit card balance distribution.

Build a professional dashboard for interactive exploration.

Provide clear insights for decision-making.

🔹 Dataset Description

The dataset contains the following important fields:

Customer Age

Gender

Income Band

Occupation Group

Credit Card Balance

Average Risk Score

Risk Category (Safe, Very Safe, Moderate, Risky, Very Risky)

🔹 Tools & Technologies

Python (EDA, data cleaning, preprocessing)

Pandas, NumPy, Matplotlib

Power BI (Dashboard & Data Visualization)

DAX Measures (KPIs & calculations)

📌 What I Observed (Key Insights)
✔️ 1. Risk Distribution by Gender

Male: 41% Safe

Female: 40% Safe

Both Gender: 40.1% Safe
➡️ Gender does not have a major impact on risk level.

✔️ 2. Income Band vs Average Risk

High income band → Higher risk

Low income band → Lower risk
➡️ High earners tend to take more credit or financial risks.

✔️ 3. Occupation Group vs Average Risk

Professional and Other categories consistently show higher average risk, regardless of gender.
➡️ Professionals (Analysts, Software Engineers, Financial roles) handle larger credit limits.

✔️ 4. Credit Card Balance Distribution

Across all slicers:

Most customers fall in the 2K – 6K balance range.

Very few customers have balances above 10K.
➡️ Majority customers maintain moderate card balances.

📌 Insights by Age Band Slicer
Age 18–25

Safe customers: 38%

Highest risk category for: High income band

Highest risk occupations: Professional & Other

Balance distribution: 2K–6K most common

Age 26–35

Safe customers: 40.08%

High income band again shows higher risk

Occupation risk pattern same as above

Balance range same (2K–6K)

Age 36–50

Safe customers: 41.08%

High income band = higher risk

Professional & Other = higher risk

Balance again clustered around 2K–6K

Age 51–65

Similar to 26–50

Only difference:
✔️ “Other” occupation has higher risk than Professional

Age 65+

Same trend; no major deviation.

📌 Insights by Income Band Slicer
High Income Band

Highest distribution: Moderate Risk (59.9%)

Occupation groups (Professional + Other) = high risk

Balance distribution expanded up to 12K

Medium Income Band

Maximum category: Safe (47.97%)

Occupation Group “Other” has higher average risk

Balance: 2K–8K prominent

Low Income Band

Dominant category: Very Safe

Professional & Other have equal and high risk score

Balance up to 10K, with occasional spikes near 10K

📌 Insights by Occupation Group Slicer
Admin

Safe: 40.4%

High income = high risk

Balance 2K–10K

Other

Safe: 41.08%

Same pattern as Admin

High income → high risk

Professional

Highest credit card balance (2K–10K)

High risk due to financial responsibilities

Skilled

Similar trends as Admin and Other

📌 Insights by Risk Category Slicer
Safe

Balance mostly 2K–4K

Very Safe

Balance mostly 2K–4K (very high concentration)

Risky

Balance 2K–8K

Very Risky

Balance 2K–12K high

Moderate

Balance 2K–10K very high

📌 KPIs Used in Dashboard

Total Customers

Average Risk Score

% Safe Customers

% Risky Customers

Average Credit Card Balance

Distribution by Income Band

Distribution by Occupation Group

📌 Dashboard Features

Fully interactive dashboard

Used slicers:

Age

Gender

Income Band

Occupation Group

Risk Category

Each slicer updates:

Donut chart (risk distribution)

Bar/column charts (income band, occupation)

Histogram (credit balance)

📌 Conclusion

The analysis clearly shows:

High-income customers take more financial risks.

Professional & Other occupations show consistently high risk.

Most customers maintain moderate card balances (2K–6K).

Safe customers increase with age (18–25 → 65+).

Risk patterns remain stable across gender.

This dashboard helps banks:

Segment customers

Identify high-risk groups

Improve credit decision models
