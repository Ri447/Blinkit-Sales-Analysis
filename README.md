# Blinkit Sales Data Analysis 📊

An Exploratory Data Analysis (EDA) project on Blinkit grocery sales data using Python, Pandas, Matplotlib, and Seaborn.

---

## 📌 Project Overview

This project analyzes Blinkit sales data to discover insights about:

- Total sales performance
- Customer ratings
- Item categories
- Outlet establishment trends
- Sales by outlet size and location
- Fat content distribution

The project includes data cleaning, preprocessing, KPI calculations, and visualizations.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure

```bash
Blinkit-Sales-Analysis/
│
├── blinkit_analysis.ipynb
├── blinkit_data.csv
├── README.md
└── requirements.txt
```

---

## 📈 KPIs Analyzed

- Total Sales
- Average Sales
- Number of Items Sold
- Average Rating

---

## 📊 Visualizations Included

### Sales by Item Fat Content
- Pie chart analysis

### Sales by Item Type
- Bar chart visualization

### Outlet Establishment Trend
- Line graph over years

### Sales by Outlet Location
- Comparative analysis across tiers

### Outlet Size Distribution
- Small, Medium, and High outlet comparison

---

## 🧹 Data Cleaning

```python
df['Item Fat Content'] = df['Item Fat Content'].replace({
    'LF': 'Low Fat',
    'low fat': 'Low Fat',
    'reg': 'Regular'
})
```


## 📦 Requirements

```txt
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## ✨ Future Improvements

- Interactive dashboards
- Machine learning predictions
- Streamlit deployment
- Advanced visualizations
- Correlation analysis

---

## 👩‍💻 Author

**Risika Singh**

---

## ⭐ Support

If you like this project, consider giving it a star ⭐
