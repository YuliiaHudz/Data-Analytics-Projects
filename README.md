# Data-Analytics-Projects

This repository contains various data analysis projects aimed at extracting, processing, and visualizing data for different business and analytical use cases. The projects utilize tools like Google BigQuery, Python (with libraries such as Pandas, SciPy, and Statsmodels), and Tableau to derive insights from raw data.

## Projects Included

### 1. [A/B Vision: Data-Driven Insights](https://github.com/YuliiaHudz/Data-Analytics-Projects/blob/main/Project_1_A_B_Vision_Data_Driven_Insights.ipynb)

#### Overview
This project focuses on A/B testing analysis by pulling data from Google BigQuery, aggregating session, order, and event data, and visualizing key metrics across different test groups, channels, and devices. The project provides insights into user behavior by analyzing sessions with orders, new accounts, and events.

#### Key Features
- SQL queries for extracting session and event data from BigQuery.
- Aggregation of session data by test groups, channels, devices, and regions.
- Creation of a Pandas DataFrame for data manipulation and further analysis.

#### How to Use
1. Clone the repository.
2. Open the notebook `A/B Vision: Data-Driven Insights.ipynb` in Google Colab.
3. Authenticate your Google Cloud account.
4. Run the notebook cells to execute the query and retrieve insights.

#### Dependencies
- `google.colab`
- `google.cloud`
- `pandas`

---

### 2. [Multi-Tool E-Commerce Analysis: SQL, Python, and Tableau](https://github.com/YuliiaHudz/Data-Analytics-Projects/blob/main/Project_2_Multi_Tool_E_Commerce_Analysis.ipynb)

#### Overview
This project performs in-depth e-commerce analysis by extracting session and order-related data from Google BigQuery, performing statistical tests, and generating visualizations using Python and Tableau. The project aims to provide insights into user sessions, product orders, and correlations between various e-commerce metrics.

#### Key Features
- SQL queries to extract session and order data.
- Analysis of user sessions, product categories, and customer demographics.
- Application of statistical tests such as Chi-Squared, Mann-Whitney U, and Kruskal-Wallis.
- Data visualizations using Plotly, Seaborn, and Tableau.

#### How to Use
1. Clone the repository.
2. Open the notebook `Multi-Tool E-Commerce Analysis.ipynb` in Google Colab.
3. Authenticate your Google Cloud account.
4. Run the notebook cells to execute queries and perform analysis.
5. Use Tableau for visualizing the final results.

#### Dependencies
- `google.colab`
- `google.cloud`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `plotly`
- `scipy`
- `statsmodels`
- `squarify`

---

## How to Run the Projects

### Prerequisites
1. **Google Cloud Project:** Ensure that you have access to a Google Cloud Project with BigQuery enabled.
2. Install necessary libraries (listed in the dependencies section) either in a virtual environment or globally.
3. Authenticate your Google Cloud account in Google Colab using the following code:
   ```python
   from google.colab import auth
   auth.authenticate_user()
