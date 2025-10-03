# VOIS_AICTE_Oct2025_Ravi_kumar
# 🏨 Airbnb Hotel Booking Analysis

This project analyzes Airbnb listings data (New York City) to uncover trends and insights in the short-term rental market.  
It involves **data cleaning, wrangling, exploratory data analysis (EDA), and visualization** to answer key business questions.  

---

## 📌 Problem Statement
The hospitality industry has been transformed by online platforms like Airbnb.  
This project explores **Airbnb Open Data** to address the following questions:

1. What are the different property types in the dataset?  
2. Which neighborhood group has the highest number of listings?  
3. Which neighborhood group has the highest average prices for Airbnb listings?  
4. Is there a relationship between the construction year of property and price?  
5. Who are the top 10 hosts by calculated host listing count?  
6. Are hosts with verified identities more likely to receive positive reviews?  
7. Is there a correlation between the price of a listing and its service fee?  
8. What is the average review rate for listings, and does it vary by neighborhood group and room type?  
9. Are hosts with higher listing counts more likely to maintain higher availability throughout the year?  

---

## ⚙️ Technologies Used

- **Programming Language:** Python  
- **Libraries:**  
  - [Pandas](https://pandas.pydata.org/) – data cleaning & manipulation  
  - [NumPy](https://numpy.org/) – numerical operations  
  - [Matplotlib](https://matplotlib.org/) – basic plots  
  - [Seaborn](https://seaborn.pydata.org/) – statistical visualizations  
  - [Plotly Express](https://plotly.com/python/plotly-express/) – interactive charts  

- **Development Environment:** Jupyter Notebook (`.ipynb`)  
- **Data Source:** Excel file (`Data.xlsx`)  

---

## 📊 Data Wrangling & Cleaning

- Removed duplicate records.  
- Dropped columns with insufficient data (`house_rules`, `license`).  
- Cleaned **price** and **service fee** columns (removed `$` and commas).  
- Renamed columns to include currency symbols (`price_$`, `service_fee_$`).  
- Corrected spelling issues (`brookln` → `Brooklyn`).  
- Handled missing values and incorrect data types.  
- Treated outliers in availability column (`availability_365`).  

---

## 🔍 Exploratory Data Analysis (EDA)

The notebook explores:  
- Property type distribution  
- Listings count across neighborhoods  
- Price variations  
- Host activity (top hosts by listings)  
- Review patterns  
- Availability vs listing count  

Visualizations are created using **Matplotlib, Seaborn, and Plotly** for better insights.  

---

## 👥 End Users

- **Airbnb Management:** To optimize pricing strategies & market expansion.  
- **Hosts:** To compare pricing & availability with competitors.  
- **Guests (Travelers):** To identify affordable neighborhoods & reliable hosts.  
- **Researchers / Data Analysts:** To study urban tourism trends.  
- **City Planners / Policymakers:** To monitor Airbnb’s effect on housing and regulations.  

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/airbnb-data-analysis.git
   cd airbnb-data-analysis
