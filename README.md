# Vendor-Performance-Analysis
# Vendor Performance Analysis

This project analyzes vendor performance using real business data to identify
profitable vendors, evaluate inventory turnover, understand pricing impacts, 
and support data-driven decision making.

## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- SQL (SQLite Database)
- Power BI for Interactive Dashboard
- Jupyter Notebook

## Key Metrics Calculated
- Gross Profit & Profit Margin
- Stock Turnover Ratio
- Sales-to-Purchase Ratio
- Freight Cost Impact

## Project Structure
- `data/` : Input datasets
- `notebooks/` : EDA and vendor analysis notebooks
- `scripts/` : Data ingestion and processing scripts
- `dashboard/` : Power BI report
- `report/` : Final PDF report document

## Results & Insights
- Business heavily depends on top vendors (~65% contribution).
- Some vendors show high margin but low sales — pricing optimization needed.
- $2.7M worth of inventory remains unsold — efficiency improvement recommended.

## How to Run
1. Install dependencies 
2. Load CSV files using `ingestion_db.py`
3. Run analysis notebooks from `/notebooks`
4. Open Power BI dashboard for visual insights


