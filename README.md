# Zomato Restaurant Analysis (EDA)

This repository contains a comprehensive **Exploratory Data Analysis (EDA)** of a Zomato restaurant dataset using Python. The analysis provides insights into customer ordering patterns, restaurant ratings, votes, and spending habits, helping understand trends in online and offline orders.

---

## 📂 Project Overview

The project analyzes a dataset of 148 restaurants from Zomato, including the following features:

- `name`: Restaurant name  
- `online_order`: Whether the restaurant accepts online orders  
- `book_table`: Whether table booking is available  
- `rate`: Average rating of the restaurant  
- `votes`: Number of votes received  
- `approx_cost(for two people)`: Approximate cost for two people  
- `listed_in(type)`: Type of restaurant (Buffet, Dining, etc.)

The goal is to understand **customer preferences, spending patterns, and ratings trends**.

---

## 🛠️ Technologies Used

- Python 3.x  
- Pandas & NumPy (data manipulation)  
- Matplotlib & Seaborn (data visualization)  
- Jupyter Notebook (analysis environment)  

---

## 🔍 Key Analysis Questions & Steps

### 1. What type of restaurant do the majority of customers order from?
- Visualized the count of each restaurant type using a **countplot**.  
- **Conclusion:** Majority of customers order from **Dining** type restaurants.

### 2. How many votes has each type of restaurant received from customers?
- Aggregated votes by restaurant type and plotted a **line chart**.  
- **Insight:** Shows which type of restaurant receives more customer engagement.

### 3. What ratings have the majority of restaurants received?
- Plotted a **countplot** of ratings.  
- **Conclusion:** The majority of restaurants have received a rating of **3.8**.

### 4. Average spending by couples on online orders
- Calculated the mean of `approx_cost(for two people)` for restaurants that accept online orders.  
- **Result:** Average spending by couples on online orders: **510.34**.

### 5. Which mode (online or offline) has received the maximum rating?
- Plotted a **boxplot** of `rate` by `online_order`.  
- **Conclusion:** **Online mode** has received the maximum ratings.

### 6. Which type of restaurant received more offline orders?
- Aggregated offline orders by restaurant type and plotted a **bar chart**.  
- **Conclusion:** **Dining** type restaurants received more offline orders, suggesting opportunities for targeted offers.

---

## 📊 Visualizations

- Count plots for **restaurant types** and **ratings**  
- Line plots for **votes per restaurant type**  
- Boxplots for **ratings by order mode**  
- Bar plots for **offline order distribution by restaurant type**  

---

## 📁 Dataset

The dataset (`Zomato_Data.csv`) should be placed in the project folder and contains the following columns:

- `name`  
- `online_order`  
- `book_table`  
- `rate`  
- `votes`  
- `approx_cost(for two people)`  
- `listed_in(type)`  

---

