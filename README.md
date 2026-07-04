# Customer Shopping Behavior Analysis & Dashboard

An end-to-end data analytics project exploring customer shopping profiles, subscription trends, purchase motivations, and product line revenues using **Python (Pandas)** for data cleaning, **MySQL** for relational querying, and **Power BI** for interactive visual reporting.

---

## Project Structure

This repository contains the full source code and reports for the complete data lifecycle:
* **`Customer shoping behavior analysis.ipynb`**: Jupyter Notebook detailing initial data loading, exploratory data analysis (EDA), value cleaning, and direct SQL database ingestion.
* **`customer behavior.sql`**: Comprehensive script containing optimized MySQL queries solving 10 core business and behavioral questions.
* **`customer_behavior.pdf`**: Complete snapshot overview of the finished, interactive stakeholder dashboard report.

---

## Key Features & Visualizations

The final analytical report tracks metrics across **7.8K total customers** with a baseline average evaluation benchmark of **$59.76 per purchase** and a consistent **3.75 customer review rating**:

* **Subscription Conversion Profile:** Identifies overall platform subscription distribution showing a 27% Subscriber vs 73% Non-Subscriber baseline split.
* **Demographic Revenue Concentration:** Visualizes total order distribution and value weight trends across segmented age cohorts (Young Adult, Adult, Middle-aged, Senior).
* **Category Dominance:** Tracks customer sales frequency and revenue generation weights across key store inventory segments like *Clothing*, *Accessories*, *Footwear*, and *Outerwear*.
* **Logistics & Delivery Analysis:** Comparative reporting matrices separating performance and purchase behavior across diverse shipping methods including *Express, 2-Day Shipping, Next Day Air, Free Shipping, Standard,* and *Store Pickup*.

---

## Built With

* **Data Engineering & EDA:** Python 3 (Pandas, NumPy, SQLAlchemy)
* **Relational Database Storage:** MySQL Server
* **Business Intelligence Tool:** Power BI Desktop

---

## Business Questions Answered (SQL Queries)

The included `customer behavior.sql` file provides reproducible solutions evaluating:
1. Total revenue generation splits by Customer Gender.
2. High-spending customer profiles filtering on discount-assisted purchases beating the global platform spend average.
3. Top 5 highly-rated platform products determined by mean review ratings.
4. Logistics expense impacts tracking purchase amounts across Standard vs. Express options.
5. Overall customer life-time-value metrics comparing total subscribers directly to non-subscribers.
6. Product markdown analysis ranking the top 5 inventory lines with the heaviest discount utilization.
7. Customer loyalty segmentation categories labeling accounts into *New*, *Returning*, and *Loyal* clusters based on purchase history frequencies.
8. Dynamic window rankings capturing the Top 3 individual inventory products inside every product category.
9. Subscription likelihood indices among repeat target profiles holding over 5 previous platform interactions.
10. Contribution revenue metrics cleanly distributed across separate target generation bins.

---

## Getting Started

### Prerequisites
* **Python Environments:** Jupyter Notebook or VS Code with `pandas` and `sqlalchemy` libraries installed.
* **Database Engine:** An active instance of MySQL Server to host and source the relational schema.
* **Report Viewers:** Power BI Desktop to interact with dashboard configurations, or a PDF reader to examine layout structures.

### Installation & Execution
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/parasharlabhanshu-cloud/customer-behavior-analysis.git](https://github.com/parasharlabhanshu-cloud/customer-behavior-analysis.git)
