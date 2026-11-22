# Big Data Analytics Project – Sample Superstore

An individual university project completed as part of the Big Data Management coursework at TU Clausthal, Germany.

This repository documents a data-analysis workflow using Python: data exploration, data-quality checks, duplicate removal, KPI calculation, aggregation and preparation of an analysis dataset. A Tableau dashboard was also created during the course; its portable version will be added after its data connections have been restored and verified.

## Project workflow

1. Load the original Sample Superstore dataset.
2. Explore its structure, descriptive statistics, data types and missing values.
3. Check duplicate rows and remove the 17 duplicates identified in the original dataset.
4. Calculate business KPIs:
   - Total Sales
   - Total Profit
   - Total Quantity
   - Profit Margin
5. Aggregate sales, profit and quantity by product category.
6. Export the cleaned dataset and document the variables in a data dictionary.

## Repository structure

```text
.
├── data/
│   ├── SampleSuperstore.csv
│   └── SampleSuperstore_clean.csv
├── documentation/
│   └── Datenwoerterbuch.csv
├── notebooks/
│   └── 01_Data_Exploration.ipynb
├── dashboard/        # Tableau files will be added after validation
├── images/           # Dashboard screenshots will be added later
├── README.md
├── requirements.txt
└── .gitignore
```

## Technologies

- Python
- pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Tableau (dashboard component; currently being prepared for portable sharing)

## Run the notebook

Create and activate a virtual environment, then install the dependencies:

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Install packages:

```bash
pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

Open `notebooks/01_Data_Exploration.ipynb` and run the cells from top to bottom.

## Data notes

The original dataset contains 9,994 rows and 13 columns. The cleaned dataset contains 9,977 rows and 13 columns after removing 17 duplicate rows.

Before making this repository public, verify that the dataset's original licence and redistribution terms permit publishing the CSV files. If redistribution is not permitted, remove the CSV files and document where an authorized copy can be obtained.

## Academic context

This is an individual coursework project, not commercial client work. The repository is intended to demonstrate practical learning and should be read in that context.

## Current status

- [x] Exploratory analysis notebook
- [x] Original and cleaned CSV files
- [x] Data dictionary
- [ ] Validate all notebook cells from a fresh environment
- [ ] Restore and verify Tableau data connections
- [ ] Add a packaged Tableau workbook (`.twbx`) if successfully recovered
- [ ] Add dashboard screenshots

## Dataset & License

**Dataset:** Sample Superstore Dataset  
**Author:** Aman Sharma  
**Source:** [Kaggle – Sample Superstore Dataset](https://www.kaggle.com/datasets/bravehart101/sample-supermarket-dataset)  
**License:** CC0 1.0 Universal (Public Domain)

The dataset is made available under the CC0 1.0 Universal license. The original dataset is credited to its author, Aman Sharma, and sourced from Kaggle.

The original and cleaned datasets are included in this repository for educational and portfolio purposes.
