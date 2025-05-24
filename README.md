# 🎓 Retention Analysis: Predicting Student Retention Rate in Higher Education

## 📌 Overview

This project explores and visualizes key factors influencing undergraduate student retention in higher education. We investigate how demographic, academic, socioeconomic, and economic indicators impact student outcomes—whether students drop out, remain enrolled, or successfully graduate.

By leveraging **interactive data visualizations**, this analysis aims to empower educational institutions to make data-driven decisions that improve student outcomes and academic support systems.

---

## 🧠 Problem Statement

Understanding the underlying factors that lead to student dropouts or success is crucial for universities aiming to improve retention. This project analyzes various variables including:

- 🧑‍🎓 Demographics: Age, gender, marital status
- 💰 Socioeconomic: Scholarship status, application methods
- 📚 Academic: Approved credits, course performance
- 🌍 External Economics: GDP, inflation, and unemployment trends

Our goal is to uncover patterns and at-risk groups through interactive data visualization, enabling real-time filtering and decision-making for educational stakeholders.

---

## 🔍 Dataset

- **Source:** [Kaggle - Higher Education Predictors of Student Retention](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention)
- **Type:** Structured
- **Attributes include:**
  - Marital status, nationality
  - Application mode/order, course, attendance
  - Mother/father's occupation & education
  - Tuition fees, scholarship holder status
  - Age at enrollment, gender
  - Curricular unit metrics (credits, enrollment, approval, evaluations)

There were **no missing values or outliers** in this dataset, minimizing the need for deep preprocessing.

---

## 🔧 Methodology

### 1. **Data Collection**
- Dataset obtained from Kaggle.

### 2. **Preprocessing**
- Checked for and confirmed no missing values.
- Verified and corrected data types.
- Removed irrelevant columns.

### 3. **Transformation**
- Created new variables like success rates.
- Selected feature categories: demographics, socioeconomics, academics, and economics.

### 4. **Interactive Visualization**
- Used modern tools to create dynamic charts and dashboards.
- Designed a responsive dashboard interface.

### 5. **Exploration & Insight Generation**
- Visual analytics were used to uncover dropout patterns and retention indicators.

---

## 📊 Visualizations & Tools Used

This project integrates several tools to create a comprehensive interactive experience:

- **Power BI & Tableau** – Dashboards with slicers, filters, and trend lines.
- **Altair.py, Plotly.py** – Python-based plotting for EDA and interactivity.
- **D3.js** – Custom visualizations for advanced interactivity and animations.

**Key Visualization Types:**
- Bar charts for retention rates
- Scatter plots for demographic-academic relationships
- Time-series for economic impact trends
- Heatmaps for dropout hotspots
- Dashboard filters for category-wise exploration

> See the `phase1-powerbi` and `phase2-code-visualizations` folder and dashboard embeds for examples.

```
student-retention-visualization/
│
├── README.md
├── LICENSE
├
│
├── 📁 data/
│   └── student_retention_dataset.csv 
│
├── 📁 docs/
│   └── project1_group4.pdf          
│
├── 📁 phase1-powerbi/
│   ├── dashboards/
│   │   └── screenshots/             
│   ├── powerbi-dashboard.pbix        
│   └── embed-code.txt                
│
├── 📁 phase2-code-visualizations/
│   ├── 📁 plotly/
│   │   ├── notebook.ipynb            
│   │   └── charts/                 
│   │
│   ├── 📁 altair/
│   │   ├── notebook.ipynb
│   │   └── charts/
│   │
│   ├── 📁 d3js/
│   │   ├── 📁 visualizations/
│   │   │   └── vis1.html, vis2.html  
│   │   ├── 📁 data/
│   │   │   └── processed.json       
│   │   └── index.html              
│
└── 

```

## 📈 Key Insights

- Scholarship holders have a higher retention and graduation rate.
- Marital status and age at enrollment show strong correlation with dropouts.
- Academic performance metrics are the strongest indicators of retention.
- Economic indicators like national unemployment rates influenced continuation decisions.

---

## 🚀 How to Run

If you're using Python for the interactive charts:

1. Clone the repository:
   ```bash
   git clone https://github.com/gnevercodes/student-retention-visualization.git
   cd student-retention-visualization

