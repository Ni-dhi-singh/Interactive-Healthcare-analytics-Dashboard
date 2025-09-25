🏥 Healthcare Analytics Dashboard (Excel)

📌 Overview

This project is an Excel-based Healthcare Analytics Dashboard designed to analyze hospital/clinic data.
It provides key insights into patients, revenue, payments, and diseases with interactive filters (slicers) and visualizations.

The dataset is synthetic (not real patient data) and structured to represent a hospital’s operations — including patients, visits, billing, payments, and claims.

DASHBOARD PREVIEW
https://github.com/Ni-dhi-singh/Interactive-Healthcare-analytics-Dashboard/commit/139babf825005af04b562958ae4354ee6c294f5e

RAW DATASET
https://github.com/Ni-dhi-singh/Interactive-Healthcare-analytics-Dashboard/blob/main/Healthcare%20data.xlsx

Full Project
https://1drv.ms/x/c/8b29f840b5e020c6/EYb3spuvsHxIgr4L6Z9LJw4BcTc97reuH0Mx4Y_SjsWFOA

🎯 Key Features

✅ KPIs

Total Patients

Total Billed Revenue (Charge Amount)

Total Collected Revenue (Payment Amount)

Pending Payments (based on payer type & claim status)


📊 Charts & Visualizations

Patients per Department (Bar Chart)

Disease Distribution (Donut / Pie Chart)

Monthly Patient Trend (Line Chart)

Payment Status (Paid vs. Unpaid)

Age Group & Gender Split (Column Chart)

🎛️ Filters (Slicers)

Department

Gender / Age

Date (Month / Year)


🧮 Data & Calculations

Total Patients → Count of unique patient_id

Total Billed Revenue → SUM(charge_amount_USD)

Total Collected Revenue → SUM(payment_amount_USD)

Pending Payments → charge_amount_USD - payment_amount_USD

Only for Self-pay (Unpaid) and Denied claims



📜 License

This project is for educational & portfolio purposes only.
All data is synthetic and does not represent real patients.
