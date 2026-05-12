# 🏥 NHS Prescription Analytics Dashboard

## 📌 Project Overview

This project analyses NHS prescription data to uncover patterns in healthcare spending, prescription volume, supplier activity, and regional variation across England. The goal was to transform a large raw prescribing dataset into a clean, interactive, and portfolio-ready analytics dashboard using Excel and Tableau Public.

The dashboard provides a high-level overview of NHS prescribing costs while also allowing deeper analysis into supplier spending, prescription behaviour, and regional distribution of healthcare expenditure.

---

# 🎯 Project Objectives

- Clean and prepare large NHS prescribing datasets
- Analyse prescription volume and NHS spending
- Identify high-cost suppliers and prescribing trends
- Compare spending across NHS regions
- Explore the relationship between prescription volume and cost
- Build a professional interactive Tableau dashboard

---

# 🛠 Tools & Technologies

| Tool | Purpose |
|------|----------|
| Microsoft Excel | Data cleaning and preparation |
| Tableau Public | Dashboard development and visualisation |

---

# 📂 Dataset Information

The dataset used contains NHS prescription records including:

- Region information
- Supplier information
- Drug names
- Generic drug classifications
- Prescription volume
- Net Ingredient Cost (NIC)
- Quantity prescribed

The dataset represented a single NHS reporting snapshot, so the analysis focuses on comparative insights rather than time-series forecasting.

---

# 🧹 Data Cleaning & Preparation

The raw dataset contained many technical reference fields and duplicate coding columns. To improve performance and readability, the dataset was cleaned in Excel before visualisation.

## Data preparation steps included:

- Removing unnecessary reference code columns
- Retaining important analytical fields
- Standardising data structure
- Handling blank values
- Creating calculated metrics
- Preparing data for Tableau import

## Key fields retained:

- Region Name
- Supplier Name
- Drug Name
- Generic Drug Name
- Prescription Items
- Total Quantity
- Net Ingredient Cost

---

# 📊 Dashboard Features

The final Tableau dashboard includes:

## KPI Cards
- Total NHS Cost
- Total Prescriptions
- Average Cost per Prescription

## Analytical Visualisations
- Regional NHS Spend
- Supplier Spend Analysis
- Cost vs Volume Insight Scatter Plot
- Regional NHS Spend Map

---

# 🧠 Analytical Insights

The dashboard highlights several important findings:

- NHS spending is concentrated among a relatively small number of suppliers and drugs
- Prescription volume does not always correlate with higher cost
- Regional variations exist in prescribing expenditure
- Some drugs generate disproportionately high NHS costs despite lower prescription volume

---

# 🗺 Geographic Analysis

A custom regional mapping layer was created using latitude and longitude coordinates to visualise NHS spending geographically within Tableau.

This involved:
- Creating a separate regional lookup table
- Mapping NHS regions to coordinates
- Building an interactive proportional symbol map

---

# ⚙️ Methodology

## Step 1 — Data Collection
Obtained NHS prescribing data containing prescription records, supplier details, costs, and regional information.

## Step 2 — Data Cleaning in Excel
Removed unnecessary columns, simplified the dataset, and created calculated fields such as average cost per prescription.

## Step 3 — Data Visualisation in Tableau
Imported the cleaned dataset into Tableau Public and created KPI cards, charts, scatter plots, and geographic visuals.

## Step 4 — Dashboard Design
Used Tableau containers and layout structuring to create a clean and professional dashboard suitable for portfolio presentation.

---

# 📈 Skills Demonstrated

- Data Cleaning
- Excel Data Preparation
- Tableau Dashboard Design
- KPI Development
- Healthcare Data Analysis
- Data Visualisation
- Geographic Mapping
- Analytical Storytelling

---

# 📸 Dashboard Preview

_Add dashboard screenshot here_

---

# 🔗 Tableau Public Dashboard

_Add Tableau Public link here_

---

# 📁 Repository Contents

```text id="repo"
├── data/
├── dashboard/
├── screenshots/
├── README.md
└── nhs-prescription-analytics-dashboard.twbx