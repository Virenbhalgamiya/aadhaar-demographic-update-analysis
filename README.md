# Unlocking Societal Trends in Aadhaar Demographic Updates

This project analyzes Aadhaar demographic update patterns across Indian districts to identify systemic friction points, regional inefficiencies, and opportunities for proactive service planning.

Unlike enrolment, Aadhaar demographic updates reflect continuous citizen interaction with identity infrastructure, driven by mobility, address changes, and contact detail updates. Understanding these patterns is essential for improving operational efficiency and citizen experience.

---

## 📊 Dataset Overview

The analysis uses aggregated datasets provided by UIDAI:

- Aadhaar Demographic Update Dataset (primary)
- Aadhaar Enrolment Dataset (contextual)

Key characteristics:
- 904 districts
- 42 states and union territories
- District-level aggregation
- Age-wise disaggregation for updates and enrolments

Raw data files were provided as paginated CSV exports and were programmatically reconstructed prior to analysis.

---

## 🧠 Methodology

- Reconstruction of full datasets from paginated CSV files
- Data cleaning and validation to handle pagination artifacts
- District-level aggregation for administrative relevance
- Feature engineering:
  - Total demographic updates
  - Total enrolments
  - Update-to-Enrolment Ratio
  - Adult update share
- Stability filtering to avoid distortion from low-volume districts

---

## 🔍 Key Insights

- Aadhaar demographic updates are overwhelmingly driven by adults
- Update activity is highly concentrated in a limited set of districts
- On average, districts experience approximately 11 demographic updates per enrolment
- Several districts exhibit extremely high update-to-enrolment ratios, indicating sustained demographic churn
- Update demand reflects continuous service needs rather than one-time enrolment corrections

---

## 📈 Visualisations

The project includes:
- Age-wise distribution of demographic updates
- Top districts by update volume
- Districts with highest update-to-enrolment ratios

All visualisations are available in the `figures/` directory.

---

## 🏛️ Impact and Applications

The findings can support:
- Targeted infrastructure and staffing allocation
- Predictive planning for update service demand
- Reduction of service bottlenecks in high-friction regions
- Improved citizen experience in Aadhaar update workflows

---

## 🧪 Reproducibility

All analysis steps are implemented in reproducible Python notebooks.
The final report is written in LaTeX and available in the `report/` directory.

---

## 📄 Report

The complete project report is available as a PDF:
- `report/final_report.pdf`

---

## ⚠️ Note on Data Availability

Raw UIDAI datasets are not included in this repository due to size and licensing constraints.
Users can obtain the data directly from the official UIDAI open data portal.
