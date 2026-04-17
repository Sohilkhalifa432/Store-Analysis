# Store-Analysis
A comprehensive data analysis project that examines store performance metrics and customer insights. Built with Python, Pandas, and Tableau, this dashboard provides actionable business intelligence on sales trends, inventory patterns, and customer behaviour.

# 🏪 Store Data Analysis

> Analyzing retail store performance to drive smarter business decisions.

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python) ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat&logo=pandas) ![Tableau](https://img.shields.io/badge/Tableau-Dashboard-E97627?style=flat&logo=tableau)

---

## 📌 Overview

This project explores a retail store dataset to uncover what drives revenue differences across stores. Using Python and Tableau, I analyzed property types, store age, checkout counters, and store size to deliver real business recommendations.

---

## 🔍 Key Business Questions

| # | Question |
|---|----------|
| 1 | Which property type generates the most revenue? |
| 2 | Do old stores outperform new ones? |
| 3 | Does adding more checkout counters increase revenue? |
| 4 | Why do stores in the same area have different revenue? |

---

## 📊 Insights

### 1. 🏠 Property Type Analysis

| Property Type | Avg Revenue | Total Revenue | Stores |
|---------------|-------------|---------------|--------|
| **Owned** | **2.49 Cr** ✅ | 936.79 Cr | 376 |
| Rental/Corporate | 2.40 Cr | 290.85 Cr | 121 |
| Rental | 2.33 Cr | 616.02 Cr | 264 |
| Corporate | 2.31 Cr | 551.97 Cr | 239 |

**💡 Insight:** Owned stores have the highest average revenue (2.49 Cr) and the largest total revenue (936.79 Cr). Corporate stores have the lowest average despite a high store count — indicating operational inefficiency.

---

### 2. 🆕 Old vs New Store Performance

| Type | Store Count | Avg Revenue | Total Revenue |
|------|-------------|-------------|---------------|
| **Old** | 126 | **2.65 Cr** ✅ | 333.37 Cr |
| New | 874 | 2.36 Cr | 2062.26 Cr |

**💡 Insight:** Old stores individually outperform new ones (2.65 Cr vs 2.36 Cr avg). New stores lead total revenue only because of higher count. Old stores benefit from customer loyalty and operational maturity.

---

### 3. 🧾 Checkout Counters vs Revenue

| Checkout Counters | Avg Revenue |
|-------------------|-------------|
| 1 counter | 1.15 Cr |
| 3 counters | 1.30 Cr |
| 5 counters | 2.68 Cr |
| 7 counters | 3.21 Cr |
| 10 counters | 5.24 Cr ✅ |

**💡 Insight:** A clear positive trend — stores with 10 counters earn ~4.5x more than stores with 1 counter. More counters = larger store = more customers = more revenue. Revenue peaks around 10 counters, after which growth fluctuates.

---

### 4. 🚀 Advanced — Same Area, Different Revenue

**Problem:** Two stores in the same location, but very different revenue. Why?

**Root Causes Found:**
- 🔴 Fewer checkout counters → lower customer throughput
- 🔴 Rental/Corporate property → higher costs, lower margins
- 🔴 Newer store → still building customer base
- 🔴 Lower product variety → less footfall

**💡 Insight:** Location alone doesn't determine performance. Internal factors — property type, store age, and counter count — are the real revenue drivers.

---

## ✅ Recommendations

- Prioritize **Owned properties** for future store expansion
- Support **new stores** with targeted promotions to accelerate growth
- Optimize **checkout counters** — avoid under-staffing large stores
- Use a **multi-factor scoring model** to evaluate store performance beyond just location

---

## 🗂️ Project Structure

```
store-analysis/
├── data/
│   └── store_data.csv
├── notebooks/
│   └── store_analysis.ipynb
├── visuals/
│   └── charts/
└── README.md
```

---

## 🛠️ Tools Used

- **Python** — Pandas, Matplotlib, Seaborn
- **SQL** — Data extraction & aggregation
- **Tableau** — Interactive dashboards

---



## 📺 Live Dashboard
 
🔗 **[View Tableau Dashboard](https://public.tableau.com/app/profile/sohil.khalifa8336/viz/Book2_17764467951850/Dashboard3?publish=yes)**
 
Interactive dashboard built on Tableau Public — explore store performance, property type breakdown, and revenue trends visually.
 
![Store Analysis Dashboard](https://github.com/Sohilkhalifa432/Store-Analysis/blob/main/SUPER%20STORE/Dashboard%203.png?raw=true)


## 👤 Author

**[Sohil khalifa]** — Data Analyst
[GitHub](https://github.com/sohilkhalifa432) · [LinkedIn](https://linkedin.com/in/sohilkhalifa)

---

> ⭐ If you found this project useful, consider starring the repository!
