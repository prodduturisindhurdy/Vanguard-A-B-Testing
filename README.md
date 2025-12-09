# Vanguard CX A/B Testing Project

## 📌 Overview
The project focuses on analyzing an A/B test conducted by Vanguard’s Customer Experience (CX) team to evaluate whether a redesigned digital interface improves client process completion rates compared to the traditional interface.

## 🎯 Project Context
- **Company:** Vanguard (US-based investment management firm)  
- **Control Group:** Clients using the traditional online process  
- **Test Group:** Clients using the new digital interface with in-context prompts  
- **Goal:** Determine if the new design leads to higher completion rates and improved user experience  

## 🛠 Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn) – Data cleaning, EDA, visualization  
- **Statsmodels / Scikit-learn** – Hypothesis testing, performance metrics, experiment evaluation  
- **Tableau** – Interactive dashboards and final presentation visuals  
- **Kanban Board (Trello/Jira/GitHub Projects)** – Project management and task tracking  

## 📊 Methodology
1. **Data Cleaning & Preparation**  
   - Handle missing values, duplicates, and formatting issues  
   - Create derived variables (completion flags, step drop-off rates)  

2. **Exploratory Data Analysis (EDA)**  
   - Funnel analysis of client progression through steps  
   - Compare distributions between control and test groups  

3. **Performance Metrics**  
   - Conversion rate calculation  
   - Step-by-step completion tracking  

4. **Hypothesis Testing**  
   - Null Hypothesis: No difference in completion rates between groups  
   - Alternative Hypothesis: Test group has higher completion rates  
   - Statistical tests: Two-proportion z-test, chi-square test  

5. **Experiment Evaluation**  
   - Assess statistical and practical significance  
   - Discuss limitations and potential biases  

6. **Visualization & Reporting**  
   - Tableau dashboards for funnel visualization and group comparison  

## ✅ Deliverables
- Cleaned dataset with documented transformations  
- Statistical analysis report (hypothesis testing results)  
- Tableau dashboard with key insights  

## 👥 Team Collaboration
- Work conducted in **pairs**  
- Tasks divided using a **Kanban board** with stages: *Backlog → In Progress → Review → Done*  

---

### 🚀 How to Use This Repository
1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/vanguard-ab-test.git# Vanguard-A-B-Testing
