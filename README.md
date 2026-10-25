# School Data Portfolio

Exploratory analysis of school-level data using Python and Jupyter notebooks.

## Setup

1. **Create the environment** (first time only)

   ```bash
   conda env create -f environment.yml
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
| Absence by geographic level — autumn & spring combined | [DfE Explore Education Statistics](https://explore-education-statistics.service.gov.uk/data-catalogue/data-set/b452323a-9c6c-4d24-929e-200b5a368116) | CSV | National/regional/LA level; 2016/17–2025/26; published 15 Oct 2026 |

## Notes

- `data/raw/` is gitignored — add source files manually after cloning.
- `reports/` is committed — place finalised charts and tables here.
