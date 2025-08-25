# Credit Risk Analytics

This project demonstrates a complete end-to-end workflow for credit portfolio analytics using Python, SQL, and Excel.

---

## Project Overview

The project includes:

1. **Synthetic credit portfolio generation**
2. **Exploratory Data Analysis (EDA)**
3. **Credit risk model building** (PD, LGD, EAD)
4. **Monte Carlo simulation of portfolio losses**
5. **Reporting and visualization** (charts, Excel reports)
6. **SQL queries for storing and summarizing data**
7. **Validation and testing of results**

---

## Project Structure


```text
credit-risk-analytics/
├── data/
│ ├── raw/ # Raw input datasets (e.g., credit portfolio CSV)
│ ├── interim/ # Intermediate datasets during processing
│ ├── processed/ # Processed datasets and simulation outputs
│ └── temp/ # Temporary files
├── notebooks/
│ ├── GeneratePortfolioData.ipynb
│ ├── EDA.ipynb
│ ├── BuildModels.ipynb
│ ├── MonteCarloSimulation.ipynb
│ ├── GenerateReports.ipynb
│ ├── SQLQueries.ipynb
│ └── TestingValidation.ipynb # Notebook for validation and testing
├── reports/
│ ├── figures/ # Charts and visualizations
│ └── outputs/ # Excel or HTML reports
├── scripts/ # Optional standalone scripts
├── tests/ # Placeholder for future tests (.gitkeep)
├── sql/ # SQLite database and queries
├── README.md
└── .gitignore
```
---

## Steps / Notebooks

| Notebook | Purpose |
|----------|---------|
| `GeneratePortfolioData.ipynb` | Generate synthetic credit portfolio |
| `EDA.ipynb` | Exploratory data analysis |
| `BuildModels.ipynb` | Build PD, LGD, and EAD models |
| `MonteCarloSimulation.ipynb` | Portfolio loss simulation using Monte Carlo |
| `GenerateReports.ipynb` | Generate charts, tables, and Excel reports |
| `SQLQueries.ipynb` | Store portfolio and simulation data in SQLite and run queries |
| `TestingValidation.ipynb` | Test and validate data, models, and simulation outputs |

---

## How to Run

1. Clone the repository:

```bash
git clone git@github.com:saurabh97kum/credit-risk-analytics.git
cd credit-risk-analytics
```

2. Create a Python virtual environment and install dependencies:

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt  # create this file with pandas, numpy, matplotlib, seaborn, xlsxwriter, etc.
```

3. Launch Jupyter:

```bash
jupyter notebook
```

4. Run notebooks **in order** from `GeneratePortfolioData.ipynb` → `TestingValidation.ipynb`.

---

## Dependencies

- Python 3.10+  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- xlsxwriter  
- sqlite3 (built-in)  

---

## Notes

- The `reports/` folder contains generated figures and Excel reports.  
- The `src/` folder has reusable functions to keep notebooks clean.  
- The `tests/` folder contains validation scripts for reproducibility.  
- Ensure paths in notebooks match your local project folder.  

---

## Author

**Saurabh Kumar**  
- GitHub: [saurabh97kum](https://github.com/saurabh97kum)

