# Data Science Foundations

**Python notebooks for data cleaning, array operations, and visualization.**

This is a learning repository. It contains small exercises using pandas, NumPy, and Matplotlib, rather than a trained predictive model or a production analytics application.

## Notebook guide

| Notebook | Topics | Input |
| --- | --- | --- |
| [pandas_employee_operations.ipynb](pandas_employee_operations.ipynb) | DataFrames, filtering, missing-value replacement, and column updates | Inline sample employee data |
| [employee_data_cleaning.ipynb](employee_data_cleaning.ipynb) | Filtering, filling missing designations, renaming, and age updates | Inline synthetic employee records |
| [numpy_array_reshaping.ipynb](numpy_array_reshaping.ipynb) | Array creation and reshaping into 4×4 and 2×8 matrices | Generated numeric arrays |
| [matplotlib_chart_basics.ipynb](matplotlib_chart_basics.ipynb) | Line subplots, bar charts, titles, and axis labels | Generated and inline sample values |
| [house_price_missing_values.ipynb](house_price_missing_values.ipynb) | Null counts, missing-value percentages, and summaries | External `House Price.csv` in Google Drive |

The house-price CSV is not included. That notebook uses Google Colab and mounts a Drive folder; update its path to your own authorized dataset before running it.

## Run

Use Google Colab for the notebook with Drive integration, or a local Jupyter environment for the self-contained exercises:

```bash
git clone https://github.com/vvsanjay/DATA-SCIRNCE-.git
cd DATA-SCIRNCE-
python -m venv .venv
source .venv/bin/activate
# Windows PowerShell: .venv\Scripts\Activate.ps1
pip install -r requirements.txt
jupyter lab
```

Run notebook cells in order. Some cells mutate a DataFrame, so rerunning only those cells can change results; restart the kernel and run from the top when checking reproducibility.

## Learning outcomes

- Inspect structured data and missing values.
- Filter and transform records with pandas.
- Understand NumPy shapes and reshaping.
- Create basic charts with labeled axes.
- Recognize the difference between a practice exercise and an evaluated data-science project.

## Repository cleanup

Notebook filenames now describe their subject. The original notebook contents and saved outputs are preserved in Git history and in the renamed files.
