# College Placement Records Analytics Workflow

A comprehensive, end-to-end data analytics project exploring college recruitment datasets. This workflow bridges the entire pipeline from raw data parsing and cleaning in Python to structured business querying with SQL and deployment via an interactive Power BI Executive Dashboard.

## Dataset Selection & Motivation

* **Dataset Selected:** [Factors Affecting Campus Placement (Kaggle)](https://www.kaggle.com/datasets/benroshan/factors-affecting-campus-placement)
* **Why I Selected It:** As a student navigating academic milestones, understanding the exact data-driven drivers behind corporate recruitment is highly relevant. This dataset provides a perfect real-world framework to analyze how academic performance tiers, secondary board choices, degree streams, and prior work experience directly correlate with final job placement success and salary package distributions.

## Tech Stack & Tools Used

* **Data Processing & Feature Engineering:** Python (`pandas`, `numpy`) inside Google Colab
* **Relational Database Analysis:** SQL (SQLite / SQLiteOnline Engine)
* **Business Intelligence & Visualization:** Power BI Desktop (DAX Modeling, KPI Tooltips, Interactive Slicers)
* **Version Control & Portfolio Hosting:** GitHub

## Business Questions Answered

Through this workflow, the following three core business and recruitment questions were analyzed and resolved:
1. **The Academic Gatekeeper Question:** How do different undergraduate academic performance tiers (`Average`, `First Class`, `Distinction`) affect a student's final placement rate and maximum salary package?
2. **The Specialisation ROI Question:** Which postgraduate MBA specialisation (`Marketing & Finance` vs. `Marketing & HR`) yields a higher financial return on investment based on average package benchmarks?
3. **The Experience Premium Question:** Does prior professional work experience significantly influence recruitment velocity, and does it guarantee a higher package ceiling compared to freshers?


## Key Data Insights

* **The Experience Advantage:** Students possessing prior work experience secured the highest overall baseline package tiers in the entire dataset, topping out at an elite maximum package of **3940,000**.
* **The Academic Factor:** Academic consistency stands as a critical recruitment gatekeeper. Students categorized under the engineered academic `Distinction` tier achieved a stellar **92% placement rate**, whereas the `Average` tier saw placement metrics drop significantly to **31%**.
* **Stream & Domain Dominance:** The undergraduate `Commerce & Management` stream along with the post-graduate `Marketing & Finance` MBA specialisation completely dominated recruitment velocity, overall baseline volume, and top salary distributions across the board.


## Project Components & Repository Structure

* **`notebook.ipynb`**: Python notebook documenting data exploration, programmatic handling of missing values (imputing unpaid/unplaced fields), text layout standardizations, and performance binning.
* **`cleaned_dataset.csv`**: The fully standardized, processed, and clean placement dataset ready for relational database workflows.
* **`queries.sql`**: Structured SQL business analysis script mapping out targeted insights using `WHERE`, `GROUP BY`, `HAVING`, and advanced conditional `CASE WHEN` aggregation logic.
* **`dashboard.pbix`**: The multi-page interactive Power BI dashboard tracking crucial placement rates, package variances, and core recruitment drivers.


## Tech Stack & Tools Used
* **Data Processing:** Python (Pandas, NumPy) inside Google Colab
* **Relational Database Analysis:** SQLite / SQLiteOnline Engine
* **Business Intelligence & Data Visualization:** Power BI Desktop (DAX Modeling, KPI Indicators, Interactive Slicers)
