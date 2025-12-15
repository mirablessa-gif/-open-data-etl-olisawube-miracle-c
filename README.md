# Exchange Rates ETL Project

## 📌 Data Source
The dataset used in this ETL is from:
https://raw.githubusercontent.com/datasets/exchange-rates/refs/heads/main/data/daily.csv

## 📌 ETL Steps Performed
1. **Extract**  
   - Loaded CSV directly from the public GitHub dataset.

2. **Transform**
   - Selected key columns.
   - Renamed columns.
   - Filtered rows (kept only USD).
   - Added computed column: rate_adjusted.

3. **Load**
   - Saved cleaned file as: `clean_exchange_rates.csv`

## 📌 Files in this Repository
- `etl_notebook.ipynb` – Full ETL code.
- `clean_exchange_rates.csv` – Clean processed dataset.

## 📌 Author
<olisawube mirace c>
