# 🍽️ Zomato Restaurants Bengaluru – Data Analysis 
[Check my Zomato Analysis Notebook](https://github.com/Rakesh00966/ZOMATO-Restaurants-EDA/blob/main/Zomato-dataset-EDA.ipynb)

[Check my Zomato Analysis Notebook Kaggle](https://www.kaggle.com/code/rakesh00966/zomato-dataset-cleaning)


## 📌 Project Overview  
This project explores the **Zomato Bengaluru Restaurants Dataset**, which contains details about 50,000+ restaurants.  
The goal was to perform **data preprocessing** and **exploratory data analysis (EDA)** to uncover insights about restaurant types, cuisines, locations, ratings, and customer preferences.  

---

## 🔧 Technologies Used  
- **Python** – Data cleaning & analysis  
- **Pandas, NumPy** – Data wrangling  
- **Matplotlib, Seaborn** – Data visualization  
- **Jupyter Notebook** – Development environment  

---

## 🛠️ Steps Performed  

### 1. Data Preprocessing  
- Handled missing values, duplicates, and inconsistent categories  
- Cleaned text columns (e.g., cuisines, location names)  
- Converted categorical/numerical variables into usable formats  

### 2. Exploratory Data Analysis (EDA)  
- Distribution of restaurants across Bengaluru  
- Top cuisines and restaurant types  
- Correlation between ratings, price range, and online delivery  
- Identified top 10 locations with the most restaurants  
- Created pivot tables  to analyze trends  

---

## 🔑 Key Insights  

1. **Top Restaurant Locations**  
   - The highest concentration of restaurants is in **Others (8007)**, **BTM (5056)**, **HSR (2494)**, and **Koramangala 5th Block (2479)**.  
   - This shows strong clustering in a few popular food hubs across Bengaluru.  

2. **Most Common Restaurant Types**  
   - **Quick Bites (19,010)** and **Casual Dining (10,253)** dominate the market.  
   - Niche categories like **Fine Dining (345)** and **Lounges (395)** are far less common, indicating most restaurants cater to affordable and casual preferences.  

3. **Online Ordering Trends**  
   - Around **60% of restaurants (30,228)** support online orders, while **40% (20,814)** don’t.  
   - Locations like **Koramangala & Indiranagar** show higher online ordering availability, while areas like **Electronic City** still have a large offline presence.  

4. **Table Booking Availability**  
   - Table booking is less common overall but shows higher availability in premium areas like **Indiranagar, Koramangala 5th Block, and JP Nagar**.  
   - Suggests dine-in culture is stronger in high-demand locations with nightlife and fine dining options.  

5. **Impact on Ratings**  
   - Restaurants that provide **both online ordering & table booking** have the **highest average rating (~4.14)**.  
   - Restaurants without either service average lower ratings (~3.6).  
   - This suggests **convenience (online orders) and experience (table booking)** both positively impact customer satisfaction.  
 

---

🚀 Future Work

Build a restaurant recommendation system.

Apply machine learning models to predict restaurant ratings.

Deploy insights on a dashboard (Streamlit / Power BI).

