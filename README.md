# Zomato Data Analysis & BI Dashboard 📊🥤


## 📌 Project Overview
This project focuses on analyzing the restaurant landscape using a Zomato dataset. The objective was to transition from Exploratory Data Analysis (EDA) performed in Python to a Business Intelligence (BI) Dashboard in Power BI. The project identifies market trends, consumer preferences, and "Hidden Gems" restaurants that offer high quality at a budget-friendly price.

## 🛠️ Tech Stack
• Data Cleaning & Analysis: Python (Pandas, Matplotlib, Seaborn)

• Environment: Google Colab

• Business Intelligence: Power BI (DAX, Power Query)

• Data Source: Zomato Restaurant Dataset (CSV)

## 🚀 Phase 1: Python Data Analysis (Google Colab)
The initial phase involved data extraction and cleaning using Python. 
- **Data Cleaning:** Handled missing values, formatted currency strings into integers, and normalized ratings to a 5-point decimal scale.
- **Library Stack:** `Pandas`, `Matplotlib`, `Seaborn`.
- **Key Findings:** Identified a correlation between "Book Table" facilities and higher average user ratings.

## 📊 Phase 2: Power BI Dashboard
I transformed the cleaned dataset into an interactive dashboard to enable stakeholders to filter and explore data intuitively.

### Key Features:
* **Executive Metrics:** Real-time tracking of Total Restaurants, Average Ratings (3.63), and Average Cost for Two (₹418).
* **Market Segmentation:** Analyzed restaurant distribution across categories like **Buffet, Cafes, and Dining**.
* **Value for Money Analysis:** A scatter plot identifying "Hidden Gems"—restaurants with high ratings (>4.0) but low average costs.
* **Service Impact:** Dynamic slicers to compare the performance of restaurants offering Online Orders vs. those that do not.


## 🛠️ Technical Workflow
1.  **ETL (Extract, Transform, Load):** Cleaned data in Python and performed further transformations in **Power Query** (including conditional columns for Price Ranges).
2.  **Data Modeling:** Established relationships and created custom **DAX Measures** for weighted ratings and popularity indices.
3.  **Visualization:** Built an insight-driven layout following UI/UX best practices for data storytelling.

## 📈 Insights Captured
* **High-End vs. Budget:** Only a small percentage of restaurants fall into the "Luxury" category, yet they account for a significant portion of user engagement (votes).
* **Dining Trends:** Cafes tend to have higher average ratings compared to standard Dining outlets in the sampled dataset.
* **Delivery Power:** Restaurants offering **Online Orders** see a higher volume of user reviews and votes on average.

## 📁 Repository Structure
* `Zomato_Data_Analysis.ipynb`: Original Google Colab notebook for EDA.
* `cleaned_data.csv`: The processed dataset used for the dashboard.
* `Zomato_Data_Analysis.pbix`: Power BI source file.
* `Dashboard_Preview.png`: Screenshot of the final interactive report.

## How to Use
1. Clone the repository.
2. Open the `.ipynb` file to view the data processing logic.
3. Open the `.pbix` file in Power BI Desktop to interact with the dashboard.

## 🤝 Contributing
Contributions are welcome! If you have suggestions for improvement, please fork the repo and create a pull request.


### Author: Mitali Khot

Project Link: https://github.com/mitalikhot/Zomato-Data-Analysis 
