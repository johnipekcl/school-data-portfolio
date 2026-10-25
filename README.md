# School Data Portfolio

Exploratory analysis of school-level data using Python and Jupyter notebooks.

## Setup

1. **Create the environment** (first time only)

   ```bash
   conda create -n school-data python=3.12 pandas openpyxl jupyter -y
   ```

2. **Activate before each session**

   ```bash
   conda activate school-data
   ```

3. **Launch Jupyter**

   ```bash
   jupyter notebook
   ```

## Repository layout

```
school-data-portfolio/
├── data/
│   ├── raw/          # Source files — never edited directly
│   └── processed/    # Cleaned / transformed outputs
├── notebooks/        # Analysis notebooks (.ipynb)
├── src/              # Reusable helper modules
├── reports/          # Final charts, tables, and write-ups (committed)
└── docs/             # Background reference material
```

## Key dependencies

| Package   | Purpose                                   |
|-----------|-------------------------------------------|
| pandas    | Data loading, cleaning, and aggregation   |
| openpyxl  | Read / write `.xlsx` files                |
| jupyter   | Interactive notebook environment          |

## Data sources

| Dataset | Source | Format | Notes |
|---------|--------|--------|-------|
| — | — | — | Add rows as datasets are acquired |

## Notes

- `data/raw/` is gitignored — add source files manually after cloning.
- `reports/` is committed — place finalised charts and tables here.
