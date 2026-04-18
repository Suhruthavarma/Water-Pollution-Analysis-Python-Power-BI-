# 🌊 Water Pollution Analysis (Python + Power BI)

## 📌 Abstract
This project presents a comprehensive analysis of water quality across 10 monitoring stations over five years (2020–2024). A Water Quality Index (WQI) is computed using 13 physicochemical parameters. A Random Forest model achieves ~93.8% accuracy and anomaly detection flags ~5% abnormal readings.

---

## 🎯 Objectives
- Analyze multi-station water quality data
- Compute WQI
- Identify seasonal and spatial trends
- Build ML models for prediction
- Detect anomalies
- Develop Power BI dashboards

---

## 📊 Dataset
- 2,610 samples
- 10 monitoring stations
- 2020–2024 timeline

### Parameters:
- Physical: pH, TDS, Turbidity, Temperature
- Chemical: DO, Nitrate, Phosphate
- Biological: BOD, COD, Coliform
- Heavy Metals: Lead, Arsenic, Chromium

---

## ⚙️ Methodology
- Data cleaning with median imputation
- Feature engineering (time variables)
- WQI computation using weighted parameters
- Visualization (8 charts)
- ML: Random Forest (93.8% accuracy)
- Anomaly detection using Isolation Forest

---

## 📈 Exploratory Data Analysis
- High-risk stations show lower WQI
- Strong correlation: BOD, COD, Coliform
- Negative correlation: DO vs BOD
- Summer shows worst pollution
- Monsoon improves water quality

---

## 📉 Key Statistics
- Mean WQI: 75.22
- Mean pH: 7.03
- Mean DO: 6.64
- Mean BOD: 4.03

---

## 🤖 Machine Learning
- Model: Random Forest
- Accuracy: ~93.8%
- Top features: BOD, DO, Coliform

---

## ⚠️ Key Findings
- Most polluted: Musi Lowland, Patancheru, Nacharam
- Cleanest: Osmansagar, Himayat Sagar
- Worst season: Summer
- Heavy metals exceed WHO limits

---

## 💡 Recommendations
- Zero liquid discharge systems
- Real-time monitoring sensors
- Increased summer sampling
- Heavy metal audits
- Improve sewage treatment

---

## 📊 Power BI Dashboard
Includes:
- KPI cards
- Trend analysis
- Risk classification

---

## 📄 Full Report
See detailed report:
report/Project_Report.pdf

---

## 👨‍💻 Author
Dachiraju Suhrutha  
suhruthavarma@gmail.com
