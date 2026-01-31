# Advanced GenAI Internship – Hackathon Project

## Project Overview
This project is part of the **Innomatics Research Labs Advanced GenAI Internship Hackathon**.  
The goal of this project is to **analyze a food delivery dataset** by combining data from multiple sources and performing data analysis to answer business-related questions.

Three datasets were provided in different formats:
1. `orders.csv` – Transactional order data
2. `users.json` – User master data
3. `restaurants.sql` – Restaurant master data

The project demonstrates:
- Data cleaning and preprocessing
- Merging datasets from CSV, JSON, and SQL
- Exploratory Data Analysis (EDA) on user behavior, city-wise and cuisine-wise revenue, membership impact, and restaurant performance
- Generating actionable insights for business decisions

## Steps Performed
1. Load CSV, JSON, and SQL datasets using **pandas** and **sqlite3**.
2. Merge datasets using LEFT JOINs to create a **final_food_delivery_dataset.csv**.
3. Clean and preprocess columns: dates, numeric types, and ratings.
4. Perform analysis to answer hackathon questions:
   - Total orders and revenue by city, membership, and cuisine
   - Average order value (AOV) for Gold and Regular members
   - Orders based on restaurant rating
   - Quarter-wise revenue trends
   - Top-performing restaurants and cuisine combinations

## Key Libraries Used
- pandas
- sqlite3
- matplotlib / seaborn (optional for visualization)

## Output
The final merged dataset: `final_food_delivery_dataset.csv`  
This dataset is used as the **single source of truth** for all questions and analysis.

## How to Run
1. Clone or download this repository.
2. Open the notebook `Innomatics_GenAI_Hackathon.ipynb`.
3. Ensure the dataset files (`orders.csv`, `users.json`, `restaurants.sql`) are in the same folder.
4. Run all cells sequentially to generate results.

## Author
**Your Name:** MVC Deep  
**Email:** mvcdeep2005@gmail.com  
**LinkedIn:** [https://www.linkedin.com/in/mvc-deep-84b569322](https://www.linkedin.com/in/mvc-deep-84b569322)

---

