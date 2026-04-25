# ACC102-GDP-Analysis
## Project Overview
This project is a mini assignment for ACC102, which performs a data analysis of the annual GDP growth rates of five major global economies (China, the United States, Germany, Japan, and the United Kingdom) from 2020 to 2024 using Python. The analysis includes data cleaning, descriptive statistics, and trend visualization.

## Data Source & Format
- **Dataset**: GDP Annual Growth Rate (%)
- **Source**: World Bank Open Data
- **Access Date**: April 25, 2026
- **Format Note**: The code is tailored for the provided `gdp_growth.csv` dataset from the World Bank, which has specific formatting with metadata in the first 4 rows. The `skiprows=4` parameter in the `pd.read_csv()` function is used to skip these non-data lines.

## Tools & Methodology
- **Libraries Used**: 
  - `pandas`: For data loading, filtering, cleaning, and descriptive statistics
  - `matplotlib`: For visualizing GDP growth trends
- **Analysis Workflow**:
  1. Load the raw dataset and skip metadata rows
  2. Filter data to keep only the target countries and years (2020-2024)
  3. Clean the dataset by removing missing values
  4. Calculate basic descriptive statistics (mean, max, min, etc.)
  5. Create a line chart to compare growth trends across countries

## Key Findings
1. **Pandemic Impact (2020)**: All five economies experienced a significant GDP growth decline in 2020, with Germany seeing the largest drop.
2. **Post-Pandemic Recovery (2021)**: A strong rebound was observed in all countries in 2021, especially China and the United States.
3. **Growth Stability**: China maintained relatively stable and positive growth compared to other developed economies from 2022 to 2024.
4. **Developed Economies**: Growth rates in Germany, Japan, and the UK remained relatively low and volatile throughout the period.

## File Structure
ACC102-GDP-Analysis/
├── ACC102_GDP_Analysis.ipynb # Complete Jupyter Notebook with code, outputs, and visualizations
├── gdp_growth.csv # Raw GDP growth dataset from the World Bank
└── README.md # This project description file

## How to Run the Project
1. Ensure you have **Anaconda** installed with Python 3 and the required libraries (`pandas`, `matplotlib`).
2. Download all files from this repository and keep them in the same folder.
3. Open Anaconda Navigator and launch **Jupyter Notebook**.
4. Open `ACC102_GDP_Analysis.ipynb` in Jupyter.
5. Run all cells in order to reproduce the analysis and visualizations.

## Limitations
- The analysis only covers a 5-year period (2020-2024), which may not capture long-term economic trends.
- No advanced statistical or econometric models are used in this basic analysis.
- The dataset only includes annual growth rates, without considering quarterly or sector-level data.
