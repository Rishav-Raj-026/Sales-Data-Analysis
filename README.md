# Sales Data Analysis Project

This project demonstrates a standard data analysis workflow using Python, Pandas, Matplotlib, and Seaborn. It is designed to simulate a real-world scenario where uncleaned raw sales data is processed to extract meaningful business insights.

## Project Structure
- `sales_data.csv`: A sales dataset containing records of transactions across different regions.
- `Sales_Analysis.ipynb`: A well-commented Jupyter Notebook that loads, cleans, explores, and visualizes the dataset.
- `*.png` files: Standalone visual exports of the charts generated during the analysis.
- `Summary.md`: A concise summary of the business findings derived from this data.

## Getting Started
### Prerequisites
Make sure you have Python 3 installed along with the required libraries. They can be installed via pip:
```bash
pip install pandas matplotlib seaborn jupyter
```

### Running the Notebook
To view the analysis, launch Jupyter Notebook from your terminal in this directory:
```bash
jupyter notebook Sales_Analysis.ipynb
```

## Key Tasks Accomplished
1. **Data Cleaning:** Handled missing values by using median imputation for numerical quantities and deriving revenue metrics programmatically.
2. **Exploratory Data Analysis (EDA):** Derived summary statistics, confirming total revenue and item volume.
3. **Trend Analysis:** Analyzed monthly seasonality and total revenue trendlines.
4. **Product Segmentation:** Visualized which products drive the most revenue vs. volume.
5. **Geographical Distribution:** Evaluated the performance parity across regional sales.

## Visualization Highlights
- **Monthly Trend**: Demonstrates the variance in sales over a 12-month period.
- **Product Performance**: Highlights that while some products sell high volumes, premium items drive total revenue.
- **Regional Revenue**: Provides a structural view of where sales originate, indicating strategic strengths or weaknesses.

*Personal Data Analysis Portfolio Project.*
