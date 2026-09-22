# Aadhaar Enrollment & Update Gap Analysis

**AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026**  
Conducted by **BharatCares** in association with AICTE

---

## Project Title
**Aadhaar Enrollment & Update Gap Analysis using UIDAI Open Data**

---

## Project Description

This project performs an end-to-end Data Analytics study on Aadhaar enrollment and update activity using publicly available UIDAI open datasets.

The goal is to identify **regional and temporal gaps** in Aadhaar enrollment and update activity (known as "Update Deserts") and convert public data into actionable insights that can support better resource allocation and policy decisions.

The project follows a complete analytics workflow:

**Data Collection → Data Understanding → Cleaning → Feature Engineering → Exploratory Data Analysis → Gap Analysis → Visualization → Insights & Recommendations**

---

## Business Problem

While Aadhaar enrollment has reached near-saturation, the maintenance of digital identity (biometric and demographic updates) remains uneven across regions and age groups.

This analysis identifies specific regions and demographics where citizens are enrolled but digitally dormant due to accessibility barriers.

---

## Dataset

The project uses three UIDAI open datasets:

1. **Aadhaar Enrollment Data** – Baseline user base
2. **Demographic Update Data** – Voluntary citizen engagement
3. **Biometric Update Data** – Mandatory lifecycle updates

**Source:** UIDAI Open Data Platform
https://drive.google.com/drive/folders/1x1q23tNxY35wXovhKmWxEM1Snpji26J4?usp=sharing

---

## Key Features of the Analysis

- Custom metric: **Update Ratio** = Total Updates / Total Enrollment
- Age Cohort Segmentation (Children 0-5, Students 5-17, Adults 18+)
- Identification of "Update Deserts" and Dormant Zones
- State-wise and Age-wise Gap Analysis
- Actionable recommendations for UIDAI and MeitY

---

## Technologies Used

| Tool / Library              | Purpose                                      |
|----------------------------|----------------------------------------------|
| Python                     | Main programming language                    |
| Pandas & NumPy             | Data cleaning, transformation & analysis     |
| Matplotlib & Seaborn       | Data visualization                           |
| Jupyter / Google Colab     | Analysis environment                         |
| AI Tools (Gemini / ChatGPT)| Code assistance, insight framing & documentation |

---

## Project Structure

```text
Aadhaar-Enrollment-Update-Gap-Analysis/
│
├── YawanKumar_AadhaarGapAnalysis.ipynb   # Main analysis notebook
├── requirements.txt                      # Python dependencies
├── README.md                             # Project overview
└── YawanKumar_ProjectReport.docx         # Project Report
