I'm Valeria, a self-taught Data Analytics enthusiast
I am currently working on my portfolio and on upgrading the following skills:

1.Gathering and Cleaning data through Spreadsheets and Reports in Microsoft Office

2.Data Analysis the data with Bigquery and R

3.Visualizing the data through Tabelau

I am looking to collaborate on exciting new projects specifically in the field of Risk Intelligence since I have experience.

### 🛠 Technical Challenge: Data Standardization
**The Problem:** The raw dataset contained inconsistent date formats (including `YYYY.MM.DD`, `MM/DD/YYYY`, and `DD-Mon-YY`) and a duplicate header row that interfered with BigQuery's auto-detection.

**The Solution:** * **SQL Transformation:** Implemented a `CASE` statement with `SAFE.PARSE_DATE` in BigQuery to manually map and unify 4+ different string formats into a standard ISO date type.
* **Data Integrity:** Identified an invalid calendar date (`2026-22-03`). I opted to set this value to `NULL` to preserve the record's existence while ensuring time-series analysis remains accurate.
* **Clean Dataset:** The finalized data is available here: [retail_orders_final.csv](https://github.com/val-data/val-data/blob/main/retail_orders_final.csv).
