# Exploratory Data Analysis Workshop

A hands-on workshop on Exploratory Data Analysis (EDA) using a synthetic bike-sharing dataset.

## Prerequisites

- Python 3.8+
- Required packages:
  ```bash
  pip install pandas numpy matplotlib seaborn jupyter
  ```
- Optional (for missing data visualization):
  ```bash
  pip install missingno
  ```

## Git workflow for students

This workshop doubles as git practice. Follow these steps:

1. **Fork** this repository on GitHub (top-right button)
2. **Clone** your fork:
   ```bash
   git clone https://github.com/<YOUR-USERNAME>/Workshop-EDA.git
   cd Workshop-EDA
   ```
3. **Create a branch** for your work:
   ```bash
   git checkout -b eda-workshop
   ```
4. **Open the notebook** and start working:
   ```bash
   jupyter notebook eda_workshop.ipynb
   ```
5. **Commit** your progress after each part:
   ```bash
   git add eda_workshop.ipynb
   git commit -m "Complete Part 1: first contact with data"
   ```
6. **Push** when you are done:
   ```bash
   git push -u origin eda-workshop
   ```
7. **Open a Pull Request** from your fork back to the original repository

## Workshop structure

| Part | Topic | Time | Key skills |
|------|-------|------|------------|
| 0 | Git Setup | ~5 min | Fork, clone, branch |
| 1 | First Contact | ~20 min | Loading, inspecting, describing data |
| 2 | Data Quality | ~25 min | Duplicates, inconsistencies, outliers |
| 3 | Missing Values | ~30 min | MCAR, MAR, MNAR analysis |
| 4 | Distributions & Visualization | ~25 min | Histograms, box plots, correlations |
| 5 | Synthesis | ~15 min | Writing an EDA summary |
| Wrap-up | Push & PR | ~5 min | Commit, push, open PR |

Total: ~2 hours

## Difficulty levels

- ⭐ Basic — everyone should complete these
- ⭐⭐ Intermediate — aim for these if you are comfortable with pandas
- ⭐⭐⭐ Challenge — stretch goals for experienced students

## Dataset

`data/bike_sharing_eda.csv` — ~800 records from a fictional city bike-sharing system. The data includes trip details, user demographics, weather conditions, and satisfaction scores.

**The data is intentionally messy.** You will find: missing values (with different missingness mechanisms), duplicate rows, inconsistent category labels, and outliers.

## Files

```
Workshop-EDA/
├── README.md
├── eda_workshop.ipynb          ← student notebook
├── 20260408 EDA W.pdf          ← presentation slides
└── data/
    └── bike_sharing_eda.csv    ← the dataset
```

## License

Free to use for teaching purposes.
