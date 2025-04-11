# 🇰🇪 Kenyan Court Case Analysis

This project presents an exploratory data analysis (EDA) of synthetic Kenyan court case data. The goal was to uncover patterns and insights related to case types, outcomes, and timelines using Python and data science tools.

---

## 📁 Project Files

- `data_exploration.ipynb` — Main notebook used for data cleaning and analysis
- `court_cases_cleaned.csv` — Cleaned version of the dataset
- `data_exploration.html` — Exported HTML version of the notebook (easier to view)
  
---

## 🔍 Summary

We analyzed a dataset of 100 synthetic Kenyan court cases with the following columns:
- **Case Type**: e.g., Criminal, Civil, Constitutional
- **Outcome**: e.g., Guilty, Not Guilty, Dismissed, Settled
- **Duration (days)**: Time taken from filing to conclusion
- **Filing Year**: Year when the case was filed

### ✨ Key Insights

- Criminal and Civil cases were the most common.
- Outcomes varied by case type, with many criminal cases ending in convictions.
- Some years showed spikes in case filings.
- Case duration had a wide range, with outliers identified and removed for better accuracy.

---

## 📊 Tools & Libraries

- **Python 3**
- `pandas` for data wrangling
- `matplotlib` and `seaborn` for data visualization
- Jupyter Notebook in VS Code

---

## 📈 Visualizations

Visual insights were provided using count plots, box plots, and line charts showing trends in case filings and durations over the years.

---

## 📬 How to View

You can open the interactive notebook here:  
🔗 [`data_exploration.ipynb`](./data_exploration.ipynb)

Or view a clean HTML version of the report:  
📄 [`data_exploration.html`](./data_exploration.html)

---

## 🤝 About

This project was created as a hands-on data science exercise combining law and tech, focused on building real-world analytical skills using public-interest data.

