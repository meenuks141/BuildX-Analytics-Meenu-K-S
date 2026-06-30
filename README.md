# College Placement Records Analytics Workflow

A comprehensive, end-to-end data analytics project exploring college recruitment datasets. This workflow bridges the entire pipeline from raw data parsing and cleaning in Python to structured business querying with SQL and deployment via an interactive Power BI Executive Dashboard.

## Project Components & Files

* **`notebook.ipynb`**: Python notebook documenting data exploration, programmatic handling of missing values, layout standardizations, and performance binning.
* **`cleaned_dataset.csv`**: The fully standardized and processed structured placement dataset ready for relational database workflows.
* **`queries.sql`**: Structured SQL business analysis script mapping out targeted insights across performance tiers, professional experience metrics, and domain specialisations.
* **`dashboard.pbix`**: The multi-page interactive Power BI dashboard tracking crucial placement rates, package variances, and recruitment drivers.


## Key Data Insights

* **The Experience Advantage:** Students possessing prior work experience secured the highest overall baseline package tiers in the entire dataset, topping out at an elite **940,000**.
* **The Academic Factor:** Academic consistency stands as a critical recruitment gatekeeper. Students categorized under the academic **Distinction tier achieved a 92% placement rate**, whereas the **Average tier saw placement metrics drop significantly to 31%**.
* **Stream & Domain Dominance:** The undergraduate **Commerce & Management** stream along with the post-graduate **Marketing & Finance** MBA specialisation completely dominated recruitment velocity, overall baseline volume, and top salary distributions.


## Tech Stack & Tools Used
* **Data Processing:** Python (Pandas, NumPy) inside Google Colab
* **Relational Database Analysis:** SQLite / SQLiteOnline Engine
* **Business Intelligence & Data Visualization:** Power BI Desktop (DAX Modeling, KPI Indicators, Interactive Slicers)
