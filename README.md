# Vanguard Digital Experiment – A/B Testing Analysis

## 📘 Overview
This project analyzes Vanguard’s digital A/B experiment evaluating whether a redesigned user interface (UI) improves client engagement and completion of a multi-step online process.  
Using demographics, digital activity logs, and experiment assignments, this analysis measures the redesign’s effectiveness and identifies opportunities for further improvement.

---

## 📂 Data Sources
- **Client Profiles** – Demographic details including age, balance, tenure, and gender.  
- **Digital Footprints** – Step-level interaction data capturing user behavior.  
- **Experiment Roster** – Control vs. Test group assignments for A/B evaluation.

After cleaning (including removing NaN values in the `variation` field) and merging all datasets, the final dataset contained **50,500 unique client IDs**.

---

## 👥 Client Behavior Insights
Demographic patterns across Test and Control groups were consistent:

- **Age:** Most active users were between **30–49** and **50–69**.  
- **Balance:** Highest engagement from clients with **$10k–$50k**.  
- **Tenure:** Strongest activity from users with **6–10 years** of tenure.

These trends help contextualize overall experiment performance.

---

## 📊 Key Performance Indicators (KPIs)
To evaluate the design’s success, three metrics were prioritized:

1. **Completion Rate** – % of users completing the final "confirm" step  
2. **Time Spent per Step** – Average time per stage of the process  
3. **Error Rate** – % of sessions where errors occurred  

---

## 🧪 Hypothesis Testing Summary

### **1. Completion Rate (Test vs. Control)**
- **Result:** The Test group showed a significantly higher completion rate.  
- **Conclusion:** The UI redesign positively impacted user completion.

### **2. Cost-Effectiveness Threshold (≥ 5% improvement)**
- **Result:** Improvement exceeded Vanguard’s 5% minimum threshold.  
- **Conclusion:** Redesign is both effective and cost-efficient.

### **3. Demographic Differences (Age, Tenure, Gender)**
- **Result:** No significant differences across groups.  
- **Conclusion:** Test and Control groups were balanced; results not driven by demographic skew.

---

## 🧭 Experiment Evaluation
- **Design Quality:** Random assignment ensured unbiased comparison.  
- **Duration:** The experiment ran from **3/15/2017 to 6/20/2017**, providing sufficient data.  
- **Additional Data Recommended:**
  - User surveys for qualitative insights  
  - Post-experiment follow-up to measure long-term behavior  
  - More granular segmentation for targeted insights  

---

## 🏁 Conclusion
The redesigned UI demonstrated clear strengths:

### ✔ Significant improvement in completion rate  
### ✔ Improvement exceeded the 5% cost-effectiveness threshold  
### ✔ Cleaner, faster overall process experience  

However, two areas require further optimization:
- **Steps 2 and 3** showed slower performance and could be streamlined.  
- **Higher error rates** in the Test group suggest possible UI friction.

Overall, the redesign is impactful, but refinement will further enhance user experience and process efficiency.

---

