# HR-Analytics-Attrition
HR Analytics project analyzing employee attrition, retention patterns, employee experience, and HR recommendations using Python and Power BI.
# HR Analytics — Employee Attrition & Retention

## 📌 Project Overview

This project analyzes employee attrition and workforce patterns to help HR identify potential retention risks and understand employee experience.

The analysis combines **Python exploratory data analysis (EDA)** with an interactive **Power BI dashboard** to transform employee-level data into actionable HR insights.

## 🎯 Business Problem

Employee turnover can increase recruitment costs, reduce productivity, and affect workforce stability.

This project aims to answer:

- What is the overall employee attrition rate?
- Which departments and job roles have higher attrition?
- How does tenure relate to employee attrition?
- How does job satisfaction relate to retention?
- Are certain employee-experience segments more vulnerable to attrition?
- What areas should HR prioritize for retention efforts?

## 🗂️ Dataset

The dataset contains **4,327 employee records** and includes information about:

- Demographics
- Department and job role
- Monthly income
- Business travel
- Years at company
- Years since last promotion
- Job satisfaction
- Environment satisfaction
- Work-life balance
- Job involvement
- Performance rating
- Attrition

The dataset was cleaned and prepared before analysis.
## 🛠️ Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - SciPy
- **Power BI**
  - DAX
  - Data modeling
  - Interactive dashboards
- **GitHub**
  - Project documentation
  - Versioned portfolio files

## 🔎 Analytical Approach

### 1. Exploratory Data Analysis — Python

The Python analysis examined:

- Overall attrition distribution
- Attrition by department
- Attrition by job role
- Monthly income
- Employee tenure
- Job satisfaction
- Environment satisfaction
- Work-life balance
- Job involvement
- Training
- Performance rating
- Promotion patterns

Statistical tests were also used to evaluate selected relationships between employee characteristics and attrition.

### 2. Power BI Dashboard

The findings were transformed into a three-page interactive dashboard.

#### Page 1 — Workforce Overview

Provides an executive overview of:

- Total employees
- Employees who left
- Overall attrition rate
- Average age
- Average monthly income
- Attrition by department
- Attrition by job role
- Workforce distribution

#### Page 2 — Retention & Attrition

Focuses on identifying employee groups with higher observed attrition.

Key dimensions include:

- Tenure
- Job satisfaction
- Work-life balance
- Tenure × job satisfaction
- Tenure × work-life balance

#### Page 3 — Employee Experience & HR Actions

Examines:

- Job satisfaction
- Environment satisfaction
- Work-life balance
- Key HR findings
- Recommended actions

## 📊 Key Findings

### Overall Attrition

- **4,327 employees** were analyzed.
- **701 employees** had left the organization.
- Overall attrition rate: **16.2%**.

### Tenure & Retention

Employee tenure was one of the strongest patterns identified.

- **0–2 years:** 30.2% attrition
- **3–5 years:** 13.9%
- **6–10 years:** 12.2%
- **11+ years:** 8.3%

This suggests that employees in the early stages of their tenure represent an important retention-risk group.

### Department

Observed attrition varied across departments.

Human Resources showed the highest departmental attrition rate at approximately **29.8%**, compared with the overall rate of 16.2%.

This should be treated as a signal for further investigation rather than evidence that the department itself causes attrition.

### Job Satisfaction

Lower job satisfaction was associated with higher observed attrition.

Employees with the lowest job-satisfaction level showed approximately **22.9% attrition**, compared with lower levels among employees reporting higher satisfaction.

### Early-Tenure Experience

The combination of tenure and employee experience revealed stronger risk signals.

Among employees with **0–2 years of tenure**:

- Low job satisfaction → approximately **43.1% observed attrition**
- Low work-life balance → approximately **46.8% observed attrition**

These segments may warrant closer HR monitoring.

---

## 📈 Statistical Validation

Selected relationships were tested statistically during the Python analysis.

For example:

- Chi-square statistic: **199.26**
- p-value: **6.10 × 10⁻⁴³**

Another test produced:

- Test statistic: **51.21**
- p-value: **4.41 × 10⁻¹¹**

The very small p-values provide statistical evidence that the tested variables are associated with attrition.

**Important:** Statistical association does not establish causation. The findings should therefore be used to identify areas for further HR investigation rather than claiming that a specific factor directly causes employees to leave.

---

## 💡 HR Recommendations

### 1. Strengthen Early-Tenure Retention

Focus on employees during their first two years through:

- Structured onboarding
- Regular manager check-ins
- Early-career development
- Feedback mechanisms

### 2. Monitor Employee Satisfaction

Identify employees reporting low job satisfaction and investigate the underlying reasons.

### 3. Monitor Work-Life Balance

Pay particular attention to early-tenure employees showing low work-life balance.

### 4. Investigate Department-Level Differences

The high observed attrition in Human Resources should trigger a deeper review of workload, management practices, and employee experience rather than assuming department membership itself causes attrition.

---

## 📁 Project Files

| File | Description |
|---|---|
| `HR_Analytics_EDA.ipynb` | Python exploratory data analysis |
| `HR_Analytics_Cleaned.csv` | Cleaned HR dataset |
| `HR_Analytics_Dashboard.pbix` | Power BI dashboard |

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization
- Power BI Dashboard Development
- DAX
- Business Analysis
- HR Analytics
- Insight Generation
- Data Storytelling
- Business Recommendations

---

## 👩‍💻 Author

**Nadia**

Data Analyst | Python | SQL | Power BI | Excel
