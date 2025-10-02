# 🧪 Hypothesis Prioritization & A/B Testing – Sprint 9 Project  

This project simulates working as a **data analyst in an e-commerce company**.  
The task was to **prioritize hypotheses for revenue growth** and then **analyze the results of an A/B test** to decide whether a new feature should be implemented.  

---

## 📌 Project Overview  

The analysis was divided into two parts:  

### 1. Hypothesis Prioritization  
- Used the **ICE framework** (Impact, Confidence, Effort) to rank hypotheses  
- Used the **RICE framework** (Reach, Impact, Confidence, Effort) to re-rank and compare results  
- Explained how prioritization changes when using ICE vs. RICE  

### 2. A/B Test Analysis  
- Compared **cumulative revenue** across control (A) and test (B) groups  
- Analyzed **average order value (AOV)** and **conversion rates** over time  
- Calculated **relative differences** between groups  
- Identified **outliers and anomalies** using percentiles (95th, 99th)  
- Tested **statistical significance** of conversion rate and order value differences using both raw and filtered data  
- Drew conclusions on whether to stop, continue, or roll out the test  

---

## 🛠️ Tools & Technologies  
- Python 3.x  
- Jupyter Notebook  
- Libraries:  
  - `pandas`, `numpy` (data processing)  
  - `scipy.stats` (hypothesis testing)  
  - `matplotlib`, `seaborn` (visualizations)  

---

## 📂 Datasets  

1. **Hypotheses** (`hypotheses_us.csv`)  
   - Hypothesis description  
   - Reach (1–10)  
   - Impact (1–10)  
   - Confidence (1–10)  
   - Effort (1–10, higher = more effort)  

2. **Orders** (`orders_us.csv`)  
   - `transactionId` — order ID  
   - `visitorId` — customer ID  
   - `date` — order date  
   - `revenue` — order revenue  
   - `group` — A/B group (A or B)  

3. **Visits** (`visits_us.csv`)  
   - `date` — date  
   - `group` — A/B group  
   - `visits` — number of site visits  

---

## 🎯 Key Learning Outcomes  
- Applied **business prioritization frameworks** (ICE & RICE) to guide testing strategy  
- Practiced **end-to-end A/B test analysis**: cleaning, visualization, significance testing  
- Strengthened ability to detect **outliers** and measure their impact on results  
- Learned to balance **business decision-making with statistical evidence**  

---

## 🚀 Business Insights  
- The prioritization of hypotheses changed significantly when adding **Reach** (RICE > ICE)  
- The A/B test showed differences in conversion and revenue, but **outliers heavily skewed results**  
- After filtering, no statistically significant improvement was found → **recommendation: stop the test and maintain group A**  

---

✍️ **Author**: Eric Moraes  
📍 Dublin, Ireland  
🔗 [LinkedIn](https://linkedin.com/in/eric--moraes)  
