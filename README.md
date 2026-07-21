# COVID-19 Early Case Trend Analysis & Recovery Insights

## 📌 Project Overview

This project analyzes early-stage COVID-19 patient data to understand infection patterns, patient demographics, recovery trends, and regional distribution. It also applies Machine Learning (Linear Regression) to predict patient recovery time based on selected features.

This project was developed as a **Machine Learning Minor Project** using Python and data analysis libraries.

---

## 🏢 Company

**HealthGuard Analytics Pvt. Ltd.**

---

## 👨‍🎓 Student

**Nikhil Kumar Sharma**

---

# 🎯 Objectives

- Analyze patient demographics.
- Identify infection spread patterns.
- Study recovery trends.
- Compare regional COVID-19 cases.
- Predict recovery duration using Machine Learning.
- Generate insights to support public health decisions.

---

# 📂 Project Structure

```
COVID19-Analysis/
│
├── .venv/
│
├── data/
│   ├── dataset.csv
│   └── cleaned_dataset.csv
│
├── notebooks/
│   └── covid_analysis.ipynb
│
├── outputs/
│   ├── final_dataset.csv
│   ├── predictions.csv
│   └── graphs/
│
├── reports/
│   └── report.docx
│
├── presentation/
│   └── presentation.pptx
│
├── requirements.txt
└── README.md
```

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code

---

# 📊 Dataset Features

The dataset includes the following attributes:

- id
- sex
- birth_year
- country
- region
- group
- infection_reason
- infection_order
- infected_by
- contact_number
- confirmed_date
- released_date
- deceased_date
- state

Additional features created during preprocessing:

- Age
- Recovery_Days

---

# 📈 Exploratory Data Analysis

The project includes visualizations such as:

- Gender Distribution
- Age Distribution
- Country Distribution
- Region Distribution
- Infection Reason Analysis
- Infection Order Analysis
- Contact Number Distribution
- Recovery Days Distribution
- Patient State Distribution
- Correlation Heatmap
- Pair Plot
- Scatter Plot
- Box Plot
- Pie Chart

---

# 🤖 Machine Learning Model

### Algorithm

- Linear Regression

### Features Used

- Age
- Contact Number
- Infection Order

### Target Variable

- Recovery_Days

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/COVID19-Analysis.git
```

Open the project folder

```bash
cd COVID19-Analysis
```

Create Virtual Environment

```bash
python -m venv .venv
```

Activate Virtual Environment

### Windows

```bash
.venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

Open Jupyter Notebook

```bash
jupyter notebook
```

Open

```
notebooks/covid_analysis.ipynb
```

Run all cells from top to bottom.

---

# 📁 Output Files

After successful execution, the following files are generated:

- cleaned_dataset.csv
- final_dataset.csv
- predictions.csv
- Graphs (if saved)

---

# 📌 Project Workflow

```
Dataset
      │
      ▼
Data Loading
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Descriptive Statistics
      │
      ▼
Linear Regression
      │
      ▼
Prediction
      │
      ▼
Model Evaluation
      │
      ▼
Results & Insights
      │
      ▼
Conclusion
```

---

# 📊 Results

The project provides insights into:

- Patient demographics
- Infection patterns
- Regional COVID-19 distribution
- Recovery trends
- Factors influencing recovery duration
- Machine Learning-based recovery prediction

---

# 🔮 Future Scope

- Use advanced Machine Learning models such as Random Forest and XGBoost.
- Build an interactive dashboard using Streamlit or Power BI.
- Integrate real-time COVID-19 datasets.
- Improve prediction accuracy with additional clinical features.
- Deploy the model as a web application.

---

# 📚 References

- https://pandas.pydata.org/
- https://numpy.org/
- https://matplotlib.org/
- https://seaborn.pydata.org/
- https://scikit-learn.org/

---

# 📄 License

This project was developed for academic and educational purposes as part of a Machine Learning Minor Project.

---

## ⭐ Thank You

If you found this project useful, consider giving it a ⭐ on GitHub.
