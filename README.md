# Amazon India Sales (2019): Data Analytics & Business Intelligence
### Transforming 42k Raw Records into 12k High-Impact Business Insights

## Project Overview
This project involves a comprehensive **Exploratory Data Analysis (EDA)** of Amazon India product listings from 2019. I have sourced this dataset from Kaggle. The core objective was to identify the drivers behind sales performance and customer satisfaction. 

By applying advanced data cleaning and statistical filtering, I transformed a noisy dataset into a high-fidelity analytical model to uncover the "True Revenue" and performance metrics of top-tier products.

---

## Analytical Tools Used
* **Data Transformation:** Microsoft Excel (Power Query)
* **Statistical Analysis:** Pivot Tables & Advanced Filtering
* **Business Intelligence:** Tableau Desktop
* **Optimization:** Excel Binary Workbook (.xlsb) for efficient data handling

---

## The Data Analytics Workflow (Excel & Power Query)
The raw dataset was a 41.8k-row CSV that required significant "scrubbing" and cleaning before any analysis could take place. So this is how i went about the process:

### **Data Cleaning & Standardization:**
1.  **Metric Formatting:** Stripped currency symbols and converted `list_price` and `discounted_price` into **Decimal** values for financial calculations.
2.  **String Parsing:** Extracted sales volume from text strings (e.g., *"10k+ bought last month"*) and converted them into **Integer** values to allow for quantitative summing.
3.  **Title Optimization (Standardization):** Many product names were excessively long (50+ characters) with redundant technical specs. I used string functions to **trim and standardize product titles**, ensuring they were concise enough for clean visualization in Tableau without losing brand identity.
4.  **Data Quality Filtering:** * Identified that many records had `0` or missing values for Price and Ratings. 
    * **Analytical Decision:** Applied a strict filter to keep only "Feature-Complete" records. 
    * **Impact:** Reduced the dataset to **12,105 high-quality rows**. This ensured that all correlations (Price vs. Rating) are based on verified data, not "garbage" entries.

---

## Business Intelligence & Pivot Analysis
Before visualizing, I used Pivot Tables to validate my hypothesis and aggregate key performance indicators (KPIs):

* **Revenue Modeling:** Calculated the **True Revenue** of the refined 12k dataset, which amounts to a massive **₹80.2 Crores**.
* **Organic vs. Sponsored Analysis:** Compared the **Average Ratings** of sponsored products against organic ones across different sales volume tiers.
* **Price Tier Segmentation:** Bucketized products by price range (from budget to premium) to observe how customer sentiment shifts as price increases.

---

## Interactive Tableau Dashboard
I exported the cleaned data to **Tableau** to build an executive-level dashboard for real-time analysis.

-> View the live interactive dashboard here: [Amazon Sales Analysis](https://public.tableau.com/views/AmazonSalesAnalysis_17788486659930/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

-> View My Tableau Public Profile: [Saideep Macherla - Vizzes](https://public.tableau.com/app/profile/saideep.macherla/vizzes)

### **Key Dashboard Features:**
* **Executive Summary:** High-level KPIs showing Total Units Sold (4.3M+), Total Revenue (₹80.2 Cr), and Total Reviews.
* **Dynamic Action Filters:** Clicking any product in the "Top 20" sheet triggers a global filter, updating the entire dashboard to show that specific product's price-to-rating ratio.
* **Visual Storytelling:** Used horizontal bar charts for better readability of product names and color-coded "Product vs. Price" charts to identify outliers.

---

## Why This Project Stands Out 
* **Quality-Driven Analysis:** I prioritized **Data Integrity** over volume. By trimming the data to a 12k "Gold Standard" sample, I eliminated bias from missing values.
* **End-to-End Analytics Lifecycle:** I demonstrated the full cycle: **Data Sourcing → Cleaning (Power Query) → Exploratory Analysis (Pivots) → Visual Storytelling (Tableau).**
* **Business Value Focus:** Rather than just "cleaning data," I focused on a business outcome: calculating **True Revenue** and comparing **Market Performance** which you can take a look inside the dashboard.

---

### 📂 Repository Structure
* `/data`: `cleaned_amazon_data.xlsb` (The final cleaned, 12k row dataset).
* `/visualizations`: Dashboard screenshots.
* `/tableau`: `.twbx` file for interactive dashboard exploration.

## Connect with me!
* If you're interested in data analytics, or just want to discuss this project, feel free to reach out!
[LinkedIn](https://www.linkedin.com/in/saideepmacherla).
---

