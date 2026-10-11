# Walsoft Student Success Analytics & What-If Simulator 📊

An executive-grade, 3-page interactive Power BI dashboard created for the Walsoft Student Success challenge. This suite translates raw academic performance data into strategic insights, diagnostic risk tracking, and leadership-facing "What-If" capacity simulations.

---

## 🚀 Key Business Insights
* **Predictability Driver:** Quantitative analysis proves **study effort (studyHOURS) accounts for 66.8%** of student success predictability, whereas **entrance exams account for only 18.9%**.
* **Strategic Recommendation:** Shift institutional focus from strict entrance exam cutoffs toward foundational onboarding bridge programs targeting dedicated, high-effort students.

---

## 🛠️ Dashboard Architecture (3 Pages)

### Page 1: Admissions & Strategy
* High-level leadership summary featuring core KPIs (Cohort Count, Python Average, Entrance Exam Average).
* Correlation scatter plot mapping study effort against academic scores.
* Education level breakdown highlighting performance across prior backgrounds.

### Page 2: At-Risk Monitoring
* Diagnostic roster isolating students requiring immediate intervention (`studyHOURS < 150`).
* Comparative skill-gap bar chart analyzing subject deficiencies across Python and Database management.
* Demographic distribution donut chart across housing/residence types.

### Page 3: What-If ROI & Capacity Simulator
* Dynamic Tile Slicer allowing academic leadership to test variable study hour targets (e.g., 120h, 140h, 160h).
* Custom DAX measures (`Simulated At Risk Count`, `Simulated Pass Rate %`) dynamically recalculating cohort qualification rates in real time.
* Education level breakdown of remaining at-risk students under active simulation thresholds.

---

## 🔧 Technical Stack & Tools
* **Data Analysis & Modeling:** Python (Pandas, NumPy, Scikit-learn) via Google Colab (`walsoft_data_analysis.ipynb`)
* **BI & Visualization:** Power BI Desktop
* **Data Transformation:** Power Query Editor (ETL, categorical unifications, typo resolution)
* **Modeling:** Data Analysis Expressions (DAX)


