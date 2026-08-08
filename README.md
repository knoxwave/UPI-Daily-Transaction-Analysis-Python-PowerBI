# 📊 UPI Daily Transaction Analysis Dashboard

### End-to-End Data Analytics Project | Python • Pandas • Web Scraping • Power BI • DAX

An **end-to-end data analytics project** analyzing **daily UPI transaction statistics from June 2021 to June 2026**.

This project covers the complete analytics lifecycle — from **NPCI data collection and Python web scraping** to **data cleaning, validation, feature engineering, Power BI data modeling, DAX calculations, interactive dashboards, and business insights**.

---

## 📌 Table of Contents

* [📊 Project Overview](#-project-overview)
* [🎯 Project Objectives](#-project-objectives)
* [🌐 Data Source](#-data-source)
* [🕷️ Data Collection & Web Scraping](#️-data-collection--web-scraping)
* [🧹 Data Cleaning](#-data-cleaning)
* [⚙️ Feature Engineering](#️-feature-engineering)
* [🛠️ Tools & Technologies](#️-tools--technologies)
* [🔄 Project Workflow](#-project-workflow)
* [📂 Dataset](#-dataset)
* [📊 Power BI Dashboard](#-power-bi-dashboard)
* [📑 Dashboard Pages](#-dashboard-pages)
* [📈 Key KPIs](#-key-kpis)
* [📐 DAX Analysis](#-dax-analysis)
* [💡 Key Business Insights](#-key-business-insights)
* [🖼️ Dashboard Screenshots](#️-dashboard-screenshots)
* [📁 Project Structure](#-project-structure)
* [🚀 Live Power BI Dashboard](#-live-power-bi-dashboard)
* [🎥 Project Explanation Video](#-project-explanation-video)
* [💼 LinkedIn Post](#-linkedin-post)
* [⚙️ Installation & Usage](#️-installation--usage)
* [🔮 Future Improvements](#-future-improvements)
* [🏆 Skills Demonstrated](#-skills-demonstrated)
* [👨‍💻 Author](#-author)
* [⭐ Support](#-support)

---

# 📊 Project Overview

**Unified Payments Interface (UPI)** has become one of India's major digital payment systems.

This project analyzes daily UPI transaction statistics to understand how digital payment activity has evolved over time.

The analysis focuses on:

* Transaction volume
* Transaction value
* Average transaction value
* Monthly and yearly trends
* Year-over-Year growth
* Moving and rolling averages
* Weekday transaction patterns
* Transaction volume per second
* Transaction value across different time intervals
* Long-term growth patterns
* Key business and operational insights

### 📅 Analysis Period

**June 2021 – June 2026**

The project combines **Python-based data collection and processing** with **Power BI analytics and visualization** to convert raw UPI statistics into an interactive business intelligence solution.

---

# 🎯 Project Objectives

The main objectives of this project are:

* Analyze daily UPI transaction volume over time
* Analyze total transaction value
* Identify monthly and yearly transaction trends
* Calculate average transaction value
* Analyze transaction activity by weekday
* Measure Year-over-Year (YoY) growth
* Calculate moving and rolling averages
* Analyze transaction volume per second
* Analyze transaction value across different time periods
* Identify significant growth and transaction patterns
* Build an interactive Power BI dashboard
* Generate meaningful business insights from UPI data

---

# 🌐 Data Source

The data used in this project is based on **UPI statistics published by the National Payments Corporation of India (NPCI)**.

### Source

**NPCI – UPI Product Statistics**

https://www.npci.org.in/what-we-do/upi/product-statistics

The collected information was transformed into a structured dataset covering daily UPI statistics from **June 2021 to June 2026**.

> **Disclaimer:** This project is created for educational and analytical purposes using publicly available NPCI statistics.

---

# 🕷️ Data Collection & Web Scraping

Instead of manually collecting every record, a Python-based data collection process was used to automate the extraction and preparation of UPI statistics.

## 🔄 Data Collection Process

```text
                ┌─────────────────────┐
                │    NPCI Website     │
                │  UPI Statistics     │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │ Python Web Scraping │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │    Raw Dataset      │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │  Data Validation    │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │   Data Cleaning     │
                │   & Processing      │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │ Feature Engineering │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │   Clean CSV Data    │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │      Power BI       │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │    DAX Measures     │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │ Interactive         │
                │ Dashboard           │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │ Business Insights   │
                └─────────────────────┘
```

---

# 🧹 Data Cleaning

The collected data was processed using **Python and Pandas** before being loaded into Power BI.

### Data cleaning activities included:

* Handling missing values
* Removing unnecessary records
* Standardizing column names
* Converting date fields into proper datetime format
* Validating transaction values
* Checking duplicate records
* Validating numerical columns
* Sorting data chronologically
* Checking data consistency
* Preparing the final analytical dataset

---

# ⚙️ Feature Engineering

Additional analytical features were created to support deeper analysis.

### Important engineered features include:

| Feature                     | Purpose                           |
| --------------------------- | --------------------------------- |
| `Date`                      | Daily transaction analysis        |
| `Year`                      | Yearly trend analysis             |
| `Month`                     | Monthly analysis                  |
| `Month-Year`                | Monthly time-series visualization |
| `Quarter`                   | Quarterly analysis                |
| `Weekday`                   | Weekday transaction analysis      |
| `Day Type`                  | Weekday vs Weekend analysis       |
| `Transaction Volume`        | Volume analysis                   |
| `Transaction Value`         | Value analysis                    |
| `Average Transaction Value` | Transaction behavior              |
| `YoY Growth`                | Annual growth analysis            |
| `Rolling Average`           | Trend smoothing                   |
| `Transactions Per Second`   | Transaction processing activity   |

---

# 🛠️ Tools & Technologies

### Programming & Data Processing

* 🐍 **Python**
* 🐼 **Pandas**
* 🔢 **NumPy**
* 📓 **Jupyter Notebook**

### Data Collection

* 🌐 **Python Web Scraping**
* 🔎 **NPCI Public Data**
* 📡 **HTTP/API Data Collection**

### Business Intelligence

* 📊 **Microsoft Power BI**
* 🔄 **Power Query**
* 📐 **DAX**

### Data Visualization

* 📊 Power BI Charts
* 📈 Line Charts
* 📊 Column Charts
* 📌 KPI Cards
* 📅 Time-Series Analysis
* 🔍 Interactive Filters & Slicers

### Version Control

* 🐙 **Git**
* 🐙 **GitHub**

---

# 🔄 Project Workflow

```text
NPCI Public Data
       ↓
Python Web Scraping
       ↓
Raw Data Collection
       ↓
Data Validation
       ↓
Data Cleaning
       ↓
Feature Engineering
       ↓
Clean Dataset
       ↓
Power Query
       ↓
Data Modeling
       ↓
DAX Measures
       ↓
Power BI Dashboard
       ↓
Interactive Analysis
       ↓
Business Insights
```

---

# 📂 Dataset

The project contains both raw and cleaned UPI transaction datasets.

### Dataset Coverage

**June 2021 – June 2026**

### Main Dataset Files

```text
UPI_Daily_Statistics_2021_2026.csv
UPI_Daily_Statistics_Clean.csv
```

The cleaned dataset is used as the primary source for Power BI analysis.

---

# 📊 Power BI Dashboard

The Power BI report contains multiple pages designed for different analytical purposes.

### Dashboard Navigation

```text
🏠 Executive Overview
        ↓
📈 Trend Analysis
        ↓
🕒 Time Intelligence
        ↓
📊 Growth Analysis
        ↓
🔍 Transaction Insights
```

The dashboard provides interactive analysis through:

* Date filters
* Year filters
* Month filters
* KPI cards
* Trend charts
* Growth indicators
* Time-based analysis
* Transaction performance metrics

---

# 📑 Dashboard Pages

## 🏠 1. Executive Overview

Provides a high-level summary of UPI transaction performance.

### Includes:

* Total Transaction Volume
* Total Transaction Value
* Average Transaction Value
* Overall Growth
* Latest Transaction Statistics
* Historical Performance

---

## 📈 2. Trend Analysis

Focuses on long-term transaction trends.

### Includes:

* Daily transaction trends
* Monthly transaction trends
* Yearly transaction trends
* Transaction volume growth
* Transaction value growth
* Rolling average analysis

---

## 🕒 3. Time Intelligence

Analyzes transaction behavior across different time periods.

### Includes:

* Monthly performance
* Quarterly performance
* Weekday analysis
* Weekend vs Weekday comparison
* Transactions per second
* Time-based transaction patterns

---

## 📊 4. Growth Analysis

Focuses on the growth of UPI transactions.

### Includes:

* Year-over-Year growth
* Monthly growth
* Transaction volume growth
* Transaction value growth
* Growth trends
* Rolling averages

---

## 🔍 5. Transaction Insights

Provides deeper analytical insights into transaction behavior.

### Includes:

* Average transaction amount
* Highest transaction periods
* Lowest transaction periods
* Transaction volume patterns
* Value vs Volume analysis
* Key performance indicators

---

# 📈 Key KPIs

The dashboard focuses on several important KPIs.

| KPI                          | Description                          |
| ---------------------------- | ------------------------------------ |
| 💳 Total Transactions        | Total number of UPI transactions     |
| 💰 Total Transaction Value   | Total monetary value of transactions |
| 📊 Average Transaction Value | Average value per transaction        |
| 📈 YoY Growth                | Year-over-Year transaction growth    |
| 🔄 Rolling Average           | Smoothed transaction trend           |
| ⚡ Transactions/Second        | Average transaction processing rate  |
| 📅 Monthly Transactions      | Total transactions by month          |
| 📆 Yearly Transactions       | Total transactions by year           |

---

# 📐 DAX Analysis

DAX was used in Power BI to create calculated measures and analytical metrics.

### Examples of analysis performed:

* Total Transactions
* Total Transaction Value
* Average Transaction Value
* YoY Growth %
* Previous Year Transactions
* Monthly Growth %
* Rolling Average
* Transactions Per Second
* Transaction Value Growth
* Maximum Transaction Value
* Minimum Transaction Value

Example:

```DAX
Total Transactions =
SUM('UPI Data'[Transaction Volume])
```

Example YoY calculation:

```DAX
YoY Growth % =
DIVIDE(
    [Total Transactions] - [Previous Year Transactions],
    [Previous Year Transactions],
    0
)
```

> DAX measures may vary depending on the final Power BI data model and column names.

---

# 💡 Key Business Insights

The dashboard helps identify important trends in India's digital payment ecosystem.

### Key areas of analysis include:

* 📈 Long-term growth in UPI transaction activity
* 💳 Increasing transaction volumes
* 💰 Growth in overall transaction value
* 📅 Differences between monthly and yearly transaction activity
* 📊 Changes in average transaction value
* ⚡ Growth in transaction processing activity
* 🕒 Transaction behavior across different time periods
* 🔄 Long-term growth trends using rolling averages

The dashboard can help analysts understand how UPI adoption and transaction activity have evolved over time.

---

# 🖼️ Dashboard Screenshots

### 🏠 Executive Overview

![Executive Overview](Dashboard%20Screenshots/Executive%20Overview.png)

### 📈 Trend Analysis

![Trend Analysis](Dashboard%20Screenshots/Trend%20Analysis.png)

### 🕒 Time Intelligence

![Time Intelligence](Dashboard%20Screenshots/Time%20Intelligence.png)

### 📊 Growth Analysis

![Growth Analysis](Dashboard%20Screenshots/Growth%20Analysis.png)

### 🔍 Transaction Insights

![Transaction Insights](Dashboard%20Screenshots/Transaction%20Insights.png)

---

# 📁 Project Structure

```text
UPI-Daily-Transaction-Analysis/
│
├── 📁 Dataset/
│   ├── UPI_Daily_Statistics_2021_2026.csv
│   └── UPI_Daily_Statistics_Clean.csv
│
├── 📁 Python/
│   ├── 03_data_cleaning.ipynb
│   └── data_check.ipynb
│
├── 📁 Dashboard Screenshots/
│   ├── Executive Overview.png
│   ├── Trend Analysis.png
│   ├── Time Intelligence.png
│   ├── Growth Analysis.png
│   └── Transaction Insights.png
│
├── 📁 Power BI/
│   └── UPI_Daily_Transaction_Analysis.pbix
│
├── 📁 Scraper/
│   └── UPI data collection scripts
│
├── README.md
└── requirements.txt
```

---

# 🏆 Project Highlights

```text
🌐 NPCI Public Data
        ↓
🕷️ Python Web Scraping
        ↓
📁 Raw Dataset
        ↓
🧹 Data Cleaning
        ↓
⚙️ Feature Engineering
        ↓
📊 Clean Dataset
        ↓
🔄 Power Query
        ↓
🗃️ Data Modeling
        ↓
📐 DAX Measures
        ↓
📈 Power BI Dashboard
        ↓
💡 Business Insights
```

### What makes this project end-to-end?

✅ Automated data collection
✅ Data validation
✅ Data cleaning
✅ Feature engineering
✅ Analytical data modeling
✅ DAX calculations
✅ Interactive Power BI dashboard
✅ Business insights
✅ GitHub documentation

---

# 🚀 Live Power BI Dashboard

🔗 **Power BI Dashboard:**
*Add your published Power BI report link here.*

> The live dashboard link can be added once the Power BI report is published to the web or Power BI Service.

---

# 🎥 Project Explanation Video

🎬 **Project Video:**
*Add your YouTube or project explanation video link here.*

---

# 💼 LinkedIn Post

I shared this project on LinkedIn:

🔗 **LinkedIn Post:**
*Add your LinkedIn project post URL here.*

---

# ⚙️ Installation & Usage

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/knoxwave/UPI-Daily-Transaction-Analysis.git
```

## 2️⃣ Navigate to the Project

```bash
cd UPI-Daily-Transaction-Analysis
```

## 3️⃣ Install Python Dependencies

```bash
pip install -r requirements.txt
```

## 4️⃣ Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the notebooks inside the `Python/` folder.

## 5️⃣ Open Power BI

Open:

```text
Power BI/
└── UPI_Daily_Transaction_Analysis.pbix
```

---

# 🔮 Future Improvements

Potential improvements for future versions include:

* [ ] Automate daily NPCI data collection
* [ ] Add an automated data refresh pipeline
* [ ] Build a Power BI Service refresh workflow
* [ ] Add more UPI-related metrics
* [ ] Add state-level UPI analysis if suitable data becomes available
* [ ] Add payment category analysis
* [ ] Add forecasting models
* [ ] Implement time-series forecasting using Python
* [ ] Add anomaly detection
* [ ] Create an automated data-quality report
* [ ] Add API-based data ingestion where officially available

---

# 🏆 Skills Demonstrated

### 🐍 Python

* Pandas
* NumPy
* Data Cleaning
* Data Validation
* Web Scraping
* Data Transformation
* Jupyter Notebook

### 📊 Power BI

* Power Query
* Data Modeling
* DAX
* KPI Development
* Interactive Dashboards
* Time Intelligence
* Data Visualization

### 📈 Data Analytics

* Exploratory Data Analysis
* Trend Analysis
* Growth Analysis
* Time-Series Analysis
* KPI Analysis
* Business Intelligence
* Data Storytelling

### 🐙 GitHub

* Repository Management
* Project Documentation
* Version Control
* Data Project Publishing

---

# 👨‍💻 Author

## Ajit Kumar

**Data Analytics Learner | Python | SQL | Power BI | Excel**

I'm continuously improving my analytical skills by building practical, end-to-end data analytics projects and transforming raw data into meaningful business insights.

### 📧 Email

**[sri1.server@gmail.com](mailto:sri1.server@gmail.com)**

### 💼 LinkedIn

https://www.linkedin.com/in/ajit-kumar-950039128/

### 🌐 Portfolio

https://ajit.msgjob.in/

### 🐙 GitHub

https://github.com/knoxwave

---

# ⭐ Support

If you found this project useful or interesting:

⭐ **Star this repository**
🍴 **Fork the repository**
💬 **Share your feedback**
🔗 **Connect with me on LinkedIn**

Thank you for visiting this project! 🙌

---

## 📌 Project Summary

> **UPI Daily Transaction Analysis Dashboard** is an end-to-end data analytics project that demonstrates how publicly available NPCI UPI statistics can be collected, cleaned, transformed, analyzed, and visualized using **Python, Pandas, Web Scraping, Power Query, DAX, and Power BI**.

**From raw NPCI data → to Python → to Power BI → to actionable insights.** 📊🚀
