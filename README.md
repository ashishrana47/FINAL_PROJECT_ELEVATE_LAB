# HR Analytics & Employee Attrition Report

## 1. Objective
The purpose of this analysis is to examine the factors influencing **employee attrition** within the organization, using both **Python-based exploratory analysis** and a **Power BI interactive dashboard**. Together, these tools help HR teams identify trends, monitor workforce composition, and design strategies to improve employee retention.

---

## 2. Data Overview
The dataset (`HR-Employee-Attrition.csv`) used in both the Jupyter Notebook and Power BI report contains employee-level information, including:
- **Demographic Attributes** – Age, Gender, Education, Marital Status  
- **Employment Factors** – Department, Job Role, Job Level, Years at Company, Overtime  
- **Performance Metrics** – Monthly Income, Job Satisfaction, Work–Life Balance, Performance Rating  
- **Target Variable** – Attrition (Yes/No)

The data was cleaned and analyzed using Python for pattern discovery, then visualized in Power BI for interactive exploration.

---

## 3. Python Notebook Analysis
The notebook `Hr Employee Attrition.ipynb` performs detailed **Exploratory Data Analysis (EDA)** using Pandas, Seaborn, and Plotly.

### 3.1 Data Preparation
- Imported libraries (`pandas`, `numpy`, `seaborn`, `matplotlib`, `plotly`).
- Loaded the HR dataset and created a working copy (`df_copy`).
- Checked for missing values, duplicates, and data types — minimal data cleaning required.

### 3.2 Key Insights
- **Attrition Rate:** Around **16–18%** of total employees had left the organization.  
- **Age Distribution:** Majority of attrition occurs between **25–35 years**, indicating mid-level career transitions.  
- **Job Role Impact:** Sales Executives and Laboratory Technicians show the **highest attrition rates**.  
- **Overtime Effect:** Employees working overtime are **2–3x more likely** to leave.  
- **Income Relationship:** Attrition tends to decrease as **monthly income increases**.  
- **Job Satisfaction:** Lower satisfaction scores correlate strongly with higher attrition.  
- **Tenure:** Employees with **<3 years** of service represent most of the exits.

Visualizations such as bar charts, correlation heatmaps, and boxplots were used to highlight these relationships.

---

## 4. Power BI Dashboard Summary
The **HR Analytics Dashboard.pbix** provides a high-level overview of workforce metrics and attrition patterns.

### 4.1 Dashboard Components
- **KPIs:** Overall Attrition %, Average Age, Average Salary, and Average Tenure.  
- **Attrition by Department:** Visual comparison across HR, Sales, and R&D.  
- **Attrition by Gender and Age Group:** Helps identify diversity trends in turnover.  
- **Job Role & Overtime Analysis:** Interactive visuals linking workload to exit rate.  
- **Income vs. Attrition Visualization:** Correlates compensation with retention.  
- **Filters:** Allow slicing by department, job level, and marital status.

### 4.2 Dashboard Insights
- **Sales** department consistently experiences the **highest attrition**.  
- **Younger employees (25–30)** exhibit the **most mobility**.  
- **Low job satisfaction + high overtime** is the most common combination leading to exit.  
- **Retention improves** in roles offering better **work–life balance** and compensation fairness.

---

## 5. Recommendations
1. **Enhance Compensation Structure:** Benchmark pay for high-attrition roles to improve retention.  
2. **Work–Life Balance Initiatives:** Reduce mandatory overtime and promote flexible work hours.  
3. **Targeted Engagement:** Focus retention efforts on employees with <3 years of tenure.  
4. **Satisfaction Surveys:** Regularly track and act on job satisfaction scores.  
5. **Predictive Monitoring:** Deploy attrition prediction models for proactive interventions.

---

## 6. Conclusion
This combined analysis demonstrates how **Python EDA** and **Power BI dashboards** complement each other in uncovering attrition trends. The insights suggest that **income, satisfaction, and workload balance** are key levers to improve retention. Implementing data-driven HR policies will likely reduce attrition and strengthen organizational stability.
