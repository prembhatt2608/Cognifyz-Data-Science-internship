# 🍽️ Restaurant Data Analysis & Machine Learning Project

## 📌 Project Overview

This project performs **end-to-end data analysis and machine learning** on a restaurant dataset. It covers everything from **data exploration and visualization** to **geospatial insights and predictive modeling** to understand customer behavior and restaurant performance.

---

## 🎯 Objectives

* Perform **Descriptive Analysis** of restaurant data
* Conduct **Geospatial Analysis** using latitude & longitude
* Analyze **Customer Preferences** based on cuisines & votes
* Create **Data Visualizations** to uncover insights
* Build **Predictive Models** to estimate restaurant ratings

---

## 📂 Dataset Description

The dataset includes:

* 📍 Location: Latitude, Longitude, City, Country Code
* 🍴 Cuisines (multiple per restaurant)
* ⭐ Aggregate Rating
* 👍 Votes (customer engagement)
* 💰 Price Range & Average Cost

---

## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**
* **Folium (Geospatial Visualization)**
* **Scikit-learn (Machine Learning)**

---

# 📊 1. Descriptive Analysis

### ✔ Tasks Performed:

* Calculated **mean, median, standard deviation**
* Explored distribution of:

  * Country Codes
  * Cities
  * Cuisines
* Identified:

  * Top cities with most restaurants
  * Most common cuisines

### 🔍 Insights:

* Dataset is **skewed toward specific cities**
* Certain cuisines dominate the dataset

---

# 🌍 2. Geospatial Analysis

### ✔ Tasks Performed:

* Plotted restaurant locations using **latitude & longitude**
* Created **interactive maps (Folium)**
* Analyzed distribution across cities & countries
* Checked correlation between **location & ratings**

### 🔍 Insights:

* Restaurants are **clustered in major cities**
* **No strong correlation** between location and rating

---

# 🍜 3. Customer Preference Analysis

### ✔ Tasks Performed:

* Analyzed **cuisine vs rating**
* Identified **popular cuisines using votes**
* Found **high-rated cuisines**

### 🔍 Insights:

* Popular cuisines ≠ always highest rated
* Some niche cuisines have **higher ratings but fewer votes**
* Weak correlation between **votes and ratings**

---

# 📈 4. Data Visualization

### ✔ Visualizations Created:

* 📊 Histogram of ratings
* 📊 Bar charts (cities, cuisines, ratings)
* 📊 Scatter plots (votes vs rating, cost vs rating)
* 🔥 Correlation heatmap

### 🔍 Insights:

* Ratings mostly fall between **3.0 – 4.5**
* No strong linear relationships between features

---

# 🤖 5. Predictive Modeling

### ✔ Models Implemented:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

### ✔ Evaluation Metrics:

* RMSE (Root Mean Squared Error)
* R² Score

### 🏆 Best Model:

* **Random Forest Regressor** performed best

### 🔍 Insights:

* Votes and price range influence ratings
* Location has **minimal impact on prediction**
* Data is **non-linear**, hence tree-based models perform better

---

## 📁 Project Structure

```
📦 Restaurant-Analysis
 ┣ 📜 Dataset.csv
 ┣ 📜 analysis.ipynb
 ┣ 📜 README.md
 ┣ 📜 restaurant_map.html
 ┗ 📂 outputs/
     ┣ charts/
     ┗ results/
```

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/restaurant-analysis.git
```

2. Install dependencies:

```
pip install pandas numpy matplotlib seaborn folium scikit-learn
```

3. Run Jupyter Notebook:

```
jupyter notebook
```

---

## 📌 Key Results Summary

* 📍 Restaurants concentrated in few cities
* 🍴 Certain cuisines dominate dataset
* ⭐ Ratings mostly mid-to-high range
* 👍 Votes ≠ always higher ratings
* 🤖 Random Forest gives best prediction accuracy

---

## 🚀 Future Improvements

* Add **Deep Learning models**
* Build **interactive dashboard (Streamlit / Power BI)**
* Use **real-time API data**
* Deploy model as a **web app**

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit pull requests.

---

## 📬 Contact

For queries or collaboration:

* GitHub: your-username
* LinkedIn: your-profile

---

⭐ If you found this project useful, give it a star!
