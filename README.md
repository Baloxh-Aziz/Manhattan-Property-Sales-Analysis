# 🏙️ Manhattan Property Sales Analysis

Exploratory data analysis of Manhattan's rolling property sales data (2012–2013), done as part of my **Introduction to Data Science (IDS)** Assignment 1 at Dawood University of Engineering & Technology, Karachi.

The goal is to understand how property prices change by **location** and by **time**, and to spot **outliers** in the sale prices.

---

## 📊 What This Project Covers

| # | Analysis | Chart | What it shows |
|---|----------|-------|---------------|
| 1 | Top 10 neighborhoods by average sale price | Bar chart | Prices differ a lot from one neighborhood to another, so location strongly affects property value |
| 2 | Average sale price over time (month by month) | Line chart | Prices are not constant and fluctuate over the months |
| 3 | Average sale price by calendar month | Line chart | Some months have higher average prices than others, which may point to seasonal trends or market changes |
| 4 | Sale price outliers | Boxplot | A few properties are priced far above or below the rest of the data |

Each chart has a short written **insight** below it in the notebook.

---

## 📁 Project Structure

```
├── IDS_Assignment1.ipynb          # Main notebook (analysis + insights)
├── rollingsales_manhattan.xls     # Dataset (Manhattan rolling sales)
└── README.md
```

> **Note:** If the dataset file is not in the repo, download the Manhattan rolling sales file from the NYC Department of Finance website and keep it in the same folder as the notebook.

---

## 🛠️ Tools Used

- **Python**
- **Pandas** for loading and grouping data
- **Matplotlib** for charts
- **Jupyter Notebook**

---

## 🔍 Key Findings

- **Location matters:** some neighborhoods have much higher average prices than others.
- **Prices change over time:** monthly averages go up and down during the year.
- **Outliers exist:** the boxplot shows extreme sale prices that can affect the averages, so they need careful handling in deeper analysis.

---

## 🚀 Possible Improvements

- Clean the data first (remove `$0` sales, which are usually ownership transfers, and extreme outliers)
- Use the **median** instead of the mean, since outliers pull the average up
- Compare prices by building class or property size
- Add more charts, such as price per square foot

---

## 👤 Author

**Azizullah Asad**
[GitHub](https://github.com/Baloxh-Aziz) | [LinkedIn](https://www.linkedin.com/in/azizullah-asad-203789345)
