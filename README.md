# 📊 Big Data Analytics Project – Sample Superstore

An individual university project developed as part of the **Big Data Management** coursework at **TU Clausthal, Germany**.

This project demonstrates an end-to-end data analytics workflow using Python and Tableau, covering data exploration, data quality assessment, data cleaning, KPI calculation, aggregation and visualization.

## 🎯 Project Objectives

- Explore and understand a real-world retail sales dataset.
- Assess data quality and identify duplicate records.
- Clean and prepare data for further analysis.
- Calculate relevant business Key Performance Indicators (KPIs).
- Analyze sales and profitability across different business dimensions.
- Present key findings through an interactive Tableau dashboard.

## 🔄 Project Workflow

1. **Data Loading:** Import the original Sample Superstore dataset.
2. **Data Exploration:** Examine the dataset structure, data types, descriptive statistics and missing values.
3. **Data Cleaning:** Identify and remove 17 duplicate records.
4. **KPI Calculation:** Calculate the main business performance indicators.
5. **Data Aggregation:** Analyze sales, profit and quantity across product categories and regions.
6. **Data Documentation:** Create a data dictionary describing the dataset variables.
7. **Data Visualization:** Build a Tableau dashboard to present the results.

## 📈 Key Performance Indicators (KPIs)

The dashboard presents four main indicators:

| KPI | Value |
|---|---:|
| Total Sales | 2,296,196 |
| Total Profit | 286,241 |
| Total Quantity | 37,820 |
| Average Sales | 230.15 |

*Values are based on the current dashboard.*

## 📊 Tableau Dashboard

The dashboard provides an overview of sales performance through four visual analyses:

- **Sales by Category:** Compares sales across Technology, Furniture and Office Supplies.
- **Sales by Region:** Examines sales distribution across the West, East, Central and South regions.
- **Profit by Category:** Compares profitability across product categories.
- **Sales by Segment:** Shows the contribution of Consumer, Corporate and Home Office customers.

**Dashboard file:** `dashboard/Superstore_Dashboard.twbx`

Open the packaged workbook with Tableau Desktop to explore the visualizations.

## 🗂️ Repository Structure

```text
Big-Data-Analytics-Project/
│
├── dashboard/
│   └── Superstore_Dashboard.twbx
│
├── data/
│   ├── SampleSuperstore.csv
│   └── SampleSuperstore_clean.csv
│
├── documentation/
│   └── Datenwoerterbuch.csv
│
├── notebooks/
│   └── 01_Data_Exploration.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

## 🛠️ Technologies Used

- **Python** – Data processing and analysis
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Interactive analysis environment
- **Tableau** – Dashboard development
- **Git & GitHub** – Version control

## ⚙️ Installation and Execution

### 1. Clone the repository

```bash
git clone https://github.com/NgonCarine/Big-Data-Analytics-Project.git
cd Big-Data-Analytics-Project
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Activate the environment

**Windows PowerShell:**

```powershell
.venv\Scripts\Activate.ps1
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `notebooks/01_Data_Exploration.ipynb` and execute the cells from top to bottom.

## 📂 Dataset Information

- **Dataset:** Sample Superstore Dataset
- **Author:** Aman Sharma
- **Source:** [Kaggle – Sample Superstore Dataset](https://www.kaggle.com/datasets/bravehart101/sample-supermarket-dataset)
- **License:** CC0 1.0 Universal (Public Domain)

The original dataset contains **9,994 rows and 13 columns**. After removing 17 duplicate records, the cleaned dataset contains **9,977 rows and 13 columns**.

The original dataset is credited to its author and source.

## 📌 Project Status

**Implemented:**
- Data exploration notebook
- Data quality checks and duplicate removal
- Original and cleaned datasets
- KPI calculations and aggregations
- Data dictionary
- Tableau packaged dashboard

**Further validation and improvements:**
- Validate all notebook cells in a fresh environment.
- Review dashboard data connections and portability.
- Refine dashboard presentation and documentation.

## 🎓 Academic Context

This is an individual academic project completed as part of the Big Data Management coursework at TU Clausthal, Germany.

It demonstrates practical experience with data preparation, exploratory data analysis, business KPI calculation and data visualization.
