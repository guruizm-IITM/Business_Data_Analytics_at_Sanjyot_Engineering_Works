# 🏭 OEE & Regression Analysis for Sanjyot Engineering Works

This project combines **Overall Equipment Effectiveness (OEE) Analysis** and **Regression Analysis** to evaluate how **machine downtime** and **employee attendance** influence the **sales performance** of *Sanjyot Engineering Works*.  
By analyzing production efficiency, performance losses, and workforce patterns, the study aims to provide **data-driven insights** and **recommendations** to improve operational productivity.

---

## 📊 Project Overview

**Objective:**  
To understand the relationship between machine downtime, attendance, and sales using statistical and regression modeling — and to quantify production efficiency through OEE metrics.

**Key Analyses:**
- **OEE Analysis:**  
  - Measured *Availability*, *Performance*, and *Quality* to assess overall equipment effectiveness.  
  - Visualized deviations from expected performance levels using clustered column charts.  

- **Regression Analysis:**  
  - Modeled the impact of **machine downtime** and **employee attendance** on **sales**.  
  - Identified how absenteeism and attrition contribute to unplanned downtime.  
  - Established correlations to guide productivity and manpower planning decisions.

---

## ⚙️ Methodology

1. **Data Collection:**  
   - Historical data of machine uptime, downtime, sales, and employee attendance.

2. **OEE Computation:**  
   - (OEE = Availability × Performance × Quality)

3. **Regression Modeling:**  
   - Used **Multiple Linear Regression** to correlate downtime and attendance with sales.
   - Evaluated model fit using **R²** and **p-values** for significance testing.

4. **Visualization:**  
   - Generated clustered column and scatter plots using **Matplotlib** and **Seaborn** to interpret trends.

---

## 🧠 Insights

- **Availability** losses were primarily due to unplanned maintenance and absenteeism.  
- **Performance** efficiency showed moderate gaps, indicating potential for process optimization.  
- **Quality** remained strong but was slightly affected by inconsistent machine operations.  
- Regression results confirmed a **negative correlation** between downtime and sales, and a **positive correlation** between attendance and sales.

---

## 🛠️ Tech Stack

- **Languages:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Environment:** Jupyter Notebook / VS Code  

---

## 📈 Results

- **OEE Score:** 67.72%  
- **Key Drivers of Inefficiency:** High machine downtime and inconsistent attendance  
- **Recommendations:**
  - Implement predictive maintenance scheduling.  
  - Improve manpower allocation to reduce absenteeism impact.  
  - Monitor real-time OEE metrics for better decision-making.

---

## 🧾 Author

**Abhishek Guru**  
*BS in Data Science and Applications, IIT Madras*  
 
---

> “Improving what you can measure — OEE and regression together provide the clarity to act.”
