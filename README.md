# Credit Risk Analytics Project

This project demonstrates **credit portfolio modeling, risk analysis, and Monte Carlo simulations** using Python, SQL, and Excel. It is designed to showcase financial modeling skills for asset and risk management.

---

## Project Structure
```text
credit-risk-analytics/
│
├── data/
│   ├── raw/               # Raw input datasets (e.g., credit portfolio CSV)
│   ├── interim/           # Intermediate datasets during processing
│   ├── processed/         # Processed datasets and simulation outputs
│   └── temp/              # Temporary files
│
├── notebooks/             # Jupyter notebooks for each step
│   ├── GeneratePortfolioData.ipynb
│   ├── EDA.ipynb
│   ├── BuildModels.ipynb
│   ├── MonteCarloSimulation.ipynb
│   ├── GenerateReports.ipynb
│   ├── SQLQueries.ipynb
│   ├── OrganizeScripts.ipynb
│   └── TestingValidation.ipynb
│
├── reports/
│   ├── figures/           # Charts and visualizations
│   └── outputs/           # Excel or HTML reports
│
├── src/                   # Reusable functions and scripts
│   ├── credit_risk/       # Model functions (PD, LGD, EAD)
│   └── risk_models/       # Simulation and risk-related functions
│
├── scripts/               # Optional standalone scripts
│   └── README.md
│
├── tests/                 # Unit tests and validation scripts
│   └── README.md
│
├── sql/                   # SQLite database and queries
│
├── venv/                  # Python virtual environment (optional)
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
| `OrganizeScripts.ipynb` | Organize reusable code into scripts for GitHub |
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

