# U.S Import Volatility by Trading partners
A beginner-friendly analysis of how U.S import values fluctuate over time across major trading partners.

## Overview
This project looks at U.S. monthly import data to understand how much import values go up and down from month to month for different countries.

Instead of focusing on long-term trends or policy decisions, the goal is to compare volatility (how stable or unstable imports appear over time) across several major U.S. trading partners.

This type of analysis can be useful for understanding supply chain consistency, planning, and risk exposure.
---

## Countries Included
- China
- Vietnam
- Mexico
- Canada
All countries are analyzed using the same data structure and time scale to keep comparisons consistent.

---

## What This Project Does
- Uses monthly U.S. import data by country
- Measures how much import values change from one month to the next
- Compares volatility levels across countries
- Visualizes differences in a clear, simple way

> Note: The notebook is written to be descriptive. It does not attempt to explain why volatility occurs or evaluate trade policy decisions.

---

## What This Project Does NOT Do
- Ut dies bit oreduct future imports
- It does not assess policy effectiveness
- It does not assign cause or blame
- It does not include freight, port, or logistics data

The focus is strictly on observed patterns in the data.
---

## Tools
- Python
- pandas
- matplotlib
-Jupyter notebook

---

## Files in This Repository
- import_volatility_analysis.ipynb
Main analysis notebook containing data preparation, calculations, and visualizations.
- imports_monthly_by_country.csv
Monthly U.S. import values by country.

---

## Key Takeaway
Different trading partners show different levels of month-to-month variability in U.S import values.  Visualizing this variability helps highlight which trade relationships appear more stable and which fluctuate more over time.

---

## About This project
This project was created as a learning exercise in time-based dataanalysis, feature engineering, and visualization using real-world economic data.

---

## How to Run This Notebook

### Option 1: Run locally (Anaconda / Jupyter)
1. Download or clone this repository
2. Make sure the following files are in the same folder:
   - `import_volatility_analysis.ipynb`
   - `imports_monthly_by_country.csv`
3. Open Anaconda Navigator
4. Launch **Jupyter Notebook**
5. Open `import_volatility_analysis.ipynb`
6. Click **Kernel → Restart & Run All**

### Option 2: Run in Google Colab (no installation)
1. Open the notebook file in this repo
2. Click **Download** (or copy the notebook URL)
3. Go to Google Colab and open the notebook
4. Upload `imports_monthly_by_country.csv` into the Colab session
5. Run all cells
---
## Author
Kenya Moorer

