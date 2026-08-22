# 📚 Books Web Scraping & EDA

## 📌 Project Overview

This project demonstrates an end-to-end data analysis workflow using book data collected from the **Books to Scrape** website.

The project combines **web scraping, data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization** to investigate book prices, customer ratings, and their relationship.

The main objective is to identify pricing patterns, rating distributions, potential outliers, and whether customer ratings are associated with higher book prices.

## 🎯 Objectives

* Collect book information using web scraping
* Clean and preprocess the collected data
* Analyze book prices and customer ratings
* Investigate the relationship between price and rating
* Identify potential price outliers
* Create informative data visualizations
* Generate meaningful insights from the dataset

## 📊 Dataset

The dataset was collected from the **Books to Scrape** website and contains information about **1,000 books collected from 50 pages**.

### Features

| Column         | Description                     |
| -------------- | ------------------------------- |
| `Title`        | Book title                      |
| `Price`        | Book price in GBP               |
| `Rating`       | Customer rating from 1 to 5     |
| `Availability` | Availability status of the book |

## 🛠️ Technologies Used

* **Python**
* **Requests** — Web requests
* **BeautifulSoup** — HTML parsing and web scraping
* **Pandas** — Data manipulation and analysi
* **Matplotlib** — Data visualization
* **Jupyter Notebook** — Interactive analysis environment

## 🔎 Project Workflow

1. Web scraping
2. Data collection
3. Data cleaning
4. Data preprocessing
5. Exploratory Data Analysis
6. Statistical analysis
7. Data visualization
8. Insight generation

## 📈 Exploratory Data Analysis

The analysis covers the following areas:

* **Price Analysis** — Distribution, range, mean, and median of book prices
* **Rating Analysis** — Distribution of books across five rating levels
* **Price vs Rating** — Investigation of the relationship between book price and customer rating
* **Correlation Analysis** — Measurement of the relationship between price and rating
* **Outlier Analysis** — Identification of potential price outliers using the IQR method
* **Summary Statistics** — Descriptive statistics for numerical variables
* **Data Visualization** — Charts used to communicate the main findings

## 📌 Key Insights

* A total of **1,000 books** were collected from **50 pages** of the Books to Scrape website.
* Book prices range from approximately **£10 to £60**.
* The dataset contains books across all **five rating levels**.
* The average price is relatively similar across different rating groups.
* The correlation between **book price and rating is 0.028**, indicating a **very weak relationship**.
* Higher-rated books are not necessarily more expensive.
* The IQR-based analysis identified **no significant price outliers** in the dataset.
* Overall, the analysis suggests that **customer rating has little influence on book price** within this dataset.

## 📊 Results

The analysis provides visual and statistical insights into:

* Book price distribution
* Rating distribution
* Average price by rating
* Relationship between price and rating
* Price outlier detection
* Descriptive statistics

All analysis results and visualizations are available in the Jupyter Notebook.

## 📁 Project Structure

```text
Books_Web_Scraping_EDA/
│
├── notebooks/
│   └── Books_Web_Scraping_EDA.ipynb
│
├── .gitignore
│
└── README.md
```

## 💡 Key Skills Demonstrated

This project demonstrates practical experience in:

* Web Scraping
* Data Collection
* Data Cleaning
* Exploratory Data Analysis
* Statistical Analysis
* Data Visualization
* Python Programming
* Pandas Data Manipulation
* Data Interpretation
* Insight Generation

## 👩‍💻 Author

**Vusala Mammadova**

Data Analyst | SQL • R • Excel • Data Analysis • Data Visualization
