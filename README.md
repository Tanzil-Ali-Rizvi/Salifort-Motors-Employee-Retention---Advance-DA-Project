# Employee Retention Analysis: Salifort Motors  
**Google Advanced Data Analytics Capstone Project**

## 📌 Project Overview
Salifort Motors, a global leader in alternative energy vehicles, is experiencing high employee turnover. This project uses data analytics and machine learning to identify the key factors driving attrition and to build a predictive model that enables HR teams to proactively support employees at risk of leaving.

The analysis focuses on employee workload, satisfaction, tenure, and performance metrics, translating insights into actionable, ethical, and business-focused recommendations.

---

## 🚀 Key Outcomes
- **Predictive Accuracy**: Built a Random Forest model achieving **Recall > 0.80**, prioritizing the identification of at-risk employees.
- **Primary Drivers of Attrition**:
  - High workload (number of projects)
  - Burnout (average monthly hours)
- **Business Impact**:
  - Recommended project load caps and revised overtime policies
  - Potential to save millions in recruitment, onboarding, and training costs

---

## 🛠️ Tech Stack & Skills
**Language**
- Python 3.x

**Libraries**
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

**Techniques**
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Logistic Regression
- Decision Trees
- Random Forest
- Hyperparameter Tuning
- Model Evaluation (Recall, F1-Score)

---

## 📂 Repository Structure

├── data/
│ └── hr_dataset.csv # Employee survey and HR data
├── notebooks/
│ ├── salifort_eda.ipynb # Data cleaning and exploratory analysis
│ └── salifort_modeling.ipynb # Model training and evaluation
├── reports/
│ └── executive_summary.pdf # Business-facing insights and recommendations
├── PACE_strategy_doc.md # Detailed project roadmap
└── README.md


---

## 📊 The PACE Workflow

### 1. Plan
- Defined the business problem: **Why are employees leaving Salifort Motors?**
- Established project scope and success metrics
- Considered ethical implications of predictive models in HR decision-making

### 2. Analyze
Conducted exploratory data analysis to uncover patterns:
- **Burnout Risk**: Employees working more than **240 hours/month** showed a sharp increase in attrition
- **Over-specialization**: Employees handling **6+ projects** were twice as likely to leave compared to those managing 3–4

### 3. Construct
Built and compared multiple models:
- **Logistic Regression**: High interpretability for understanding feature impact
- **Random Forest / XGBoost**: Superior predictive performance and ability to model non-linear relationships

### 4. Execute
- Evaluated models using **Recall** and **F1-Score**
- Delivered an executive summary with three core recommendations:
  - **Project Caps**: Limit employees to a maximum of 5 projects
  - **Hours Threshold**: Monitor employees exceeding 220 monthly hours
  - **Promotion Review**: Reassess promotion timelines for employees stagnant for 5+ years

---

## 📈 Key Takeaway
This project demonstrates how data-driven HR analytics can move beyond descriptive reporting to proactive decision-making—helping organizations reduce attrition, improve employee well-being, and strengthen long-term organizational stability.

---
