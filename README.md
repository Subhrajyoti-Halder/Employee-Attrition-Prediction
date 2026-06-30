# Employee-Attrition-Prediction

--


### 📌 Project Overview
This project analyzed employee information to identify patterns associated with employee attrition
(employees leaving the company). The analysis found that overtime, job satisfaction, and monthly
income were among the strongest indicators of whether an employee was likely to leave.
Employees with frequent overtime and lower satisfaction showed a higher risk of attrition, while
compensation also influenced retention but was not the only factor. The analysis also identified
departments and job roles with comparatively higher employee turnover, allowing HR to focus
retention efforts where they will have the greatest impact. The predictive model achieved strong
overall performance and can help HR identify employees who may be at higher risk of leaving
before resignations occur. Based on these findings, two key recommendations are: 1. Reduce
excessive overtime and improve work-life balance through better workload planning and flexible
work policies. 2. Conduct regular employee engagement and career development discussions,
especially for employees identified as high risk. This model should be used as a decision-support
tool rather than a replacement for human judgment. Personal circumstances, external job
opportunities, and individual career goals are not included in the available HR data and may also
influence an employee's decision to leave

### 🎯 Objectives
The goal of this project is to build a machine learning model that predicts whether an employee is likely to
leave the organization based on various personal, professional, and workplace-related factors. Such
predictions enable HR departments to identify high-risk employees early and implement retention
strategies before valuable talent is lost.

---
###  Problem Statement

- Employee attrition increases hiring and training costs.
- Losing experienced employees reduces productivity.
- HR needs a system to identify employees at risk of leaving.
- Goal: Build a machine learning model to predict employee attrition and provide actionable HR insights.

---
### 📂 Dataset
Include a table:

| Property	 | Value |
|------|------|
| `Dataset` | IBM HR Analytics |
| `Records` | 1470 Employees |
| `Features` | 35 |
| `Target Variable` | Attrition |
| `Missing Values` | None |

Mention:

- Employee demographics
- Salary
- Job Role
- Department
- Work-Life Balance
- Job Satisfaction
- Overtime
- Years at Company
---
### Data Preprocessing
```
Flowchart:
             Dataset
								│
       Missing Value Check
			          │
     Drop Irrelevant Columns
			          │
    Encode Categorical Variables
			          │
		   Scale Numeric Features
                │
		    Train-Test Split
```
#### Exploratory Data Analysis

Insert charts:

- Attrition by Department
- Attrition by Job Role
- Income vs Attrition
- Work-Life Balance

Key findings:

- Sales department showed higher attrition (or your actual result)
- Lower-income employees were more likely to leave
- Overtime strongly influenced attrition
- Most employees left within the first few years
---
### Machine Learning Models
Comparison table:

| Property	 | Value |
|------|------|
| `Logistic Regression` | Baseline Model |
| `Random Forest` | Ensemble Model |
| `Gradient Boosting` | Advanced Ensemble |

---

### 📈 Feature Importance
Insert the Top 10 Feature Importance chart.

Explain the top predictors, for example:

- Overtime
- Monthly Income
- Job Satisfaction
- Age
- Years at Company
- Work-Life Balance
---
### 💡 Business Recommendations
Recommendations:

- Reduce excessive overtime.
- Conduct regular employee satisfaction surveys.
- Improve career development opportunities.
- Offer mentoring programs.
- Focus retention efforts on high-risk employees.
- Monitor employees with low work-life balance.

---
### Limitations
Mention:

- Based only on historical HR data.
- Cannot capture personal reasons for leaving.
- External job market factors are not included.
- Predictions should support—not replace—HR decisions.

---
### Conclusion
Summarize:

- Successfully built an attrition prediction model.
- Identified the key factors affecting employee turnover.
- Compared three machine learning models.
- Generated actionable HR insights.
- Demonstrated how data analytics can improve employee retention.

---
---
### ▶️ How to Run
Clone the repository
---
  - https://github.com/Subhrajyoti-Halder/Employee-Attrition-Prediction
---

