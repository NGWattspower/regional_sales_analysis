# regional_sales_analysis

Sales Data Exploratory Data Analysis (EDA) Project
Project Overview

This project performs Exploratory Data Analysis (EDA) on a sales dataset covering multiple years, products, regions, and sales channels.
The goal is to uncover key trends, growth opportunities, and actionable insights that can inform sales strategy and business decisions.

The project includes:

📑 Jupyter Notebook (.ipynb) with all EDA steps, data cleaning, and visualizations.

📂 Excel dataset used for analysis.

📘 PDF (PowerPoint export) summarizing insights, key visualizations, and recommendations.

├── data/
│   └── sales_data.xlsx       # Raw dataset

├── notebooks/

│   └── sales_eda.ipynb       # Jupyter Notebook (EDA analysis)

├── reports/

│   └── sales_insights.pdf    # PDF with charts & insights

├── README.md                 # Project documentation


Tools & Libraries

Python 3.11+

Pandas (data wrangling)

Matplotlib & Seaborn (visualizations)

Jupyter Notebook (interactive analysis)

Excel (raw dataset storage)

Key Analysis Performed

Data Cleaning & Preparation: handled missing values, validated integrity, ensured consistency.

Trend Analysis: sales and profit trends over time.

Regional Analysis: sales distribution and profit across US regions.

Channel Performance: revenue and profit by Wholesale, Distributor, and Export.

Product Insights: top-performing products by revenue and margin.

Budget vs Actual: comparison of planned vs achieved revenue.

Advanced Visuals: heatmaps, opportunity matrix, and cumulative growth analysis.

Key Insights

Wholesale dominates sales (~$670M revenue, ~$248M profit).

Export lags in revenue but has higher profit margins (~38%), showing growth potential.

West region leads in revenue, but opportunities exist in the Northeast.

Top products (e.g., Product 25 & 26) contribute disproportionately to revenue.

Seasonal effects observed in Q1 and Q4 sales peaks.

How to Run

Clone this repository:

git clone https://github.com/yourusername/sales-eda.git
cd sales-eda


Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook notebooks/sales_eda.ipynb


Review insights in the PDF report under reports/.

Next Steps / Future Work

Build predictive models to forecast future sales.

Perform customer segmentation for targeted marketing.

Integrate external market data for validation.

Explore automated dashboarding (Tableau, Power BI, or Plotly Dash).

Author

Robert Frederiqque

🔗 LinkedIn Profile
 | Portfolio
