# 🏠 USA Real Estate Market – Python Data Analysis Project  
📊 **Advanced Python EDA | Data Cleaning | Insightful Visualizations | Real-World Dataset**  

<img src="/Real_Estate_Image.png" />

---

## 🔍 Project Overview  
This project provides a comprehensive **exploratory data analysis (EDA)** of the **U.S. real estate market**, transforming a raw dataset into **meaningful business insights** using Python.

### 🚀 Key Objectives  
✅ Clean and preprocess a large real estate dataset (2.2M+ rows)  
✅ Explore housing prices, size, state/city-based trends  
✅ Identify patterns using visualizations and statistical summaries  
✅ Present findings in a way that's clear to both analysts and business stakeholders

---

## 📂 Dataset Summary  
📁 **Source:** [Kaggle – USA Real Estate Dataset](https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset)  
📏 **Size:** ~2.2 million property listings across the United States  
🧩 **Key Columns:**  
- `price`: Property price  
- `bed`, `bath`: Bedrooms, bathrooms  
- `house_size`: Interior size  
- `acre_lot`: Exterior size  
- `city`, `state`, `zip_code`, `brokered_by`  

---

## 🧹 Data Cleaning Highlights  
✅ Removed `prev_sold_date` due to excessive nulls  
✅ Filled missing values:
- Numeric columns → with median  
- Categorical columns → with placeholder text  
✅ Converted `zip_code` to string  
✅ Cleaned column names (snake_case)  
✅ Final dataset: **100% ready for EDA**

---

## 📊 Key Visual Insights  

### 🔸 Distribution of House Prices  
<img src="output/Distribution of House Prices.png" width="700"/>  
Most homes are priced under **$400K**, with a steep drop-off after. The market is **skewed toward lower-priced properties**.

---

### 🔸 Correlation Between Numeric Features  
<img src="output/Correlation Heatmap.png" width="450"/>  
Price is only **weakly correlated** with features like `bed`, `bath`, and `house_size`.  
🧠 Interpretation: Other untracked factors (e.g., location quality, amenities) influence price more.

---

### 🔸 Price vs. Number of Bedrooms  
<img src="output/Price by Number of Bedrooms.png" width="700"/>  
Price **tends to increase with bedroom count**, but outliers exist even at low bedroom counts (e.g., luxury small homes).

---

### 🔸 Price vs. Number of Bathrooms  
<img src="output/Price with Number of Bathrooms.png" width="700"/>  
Higher bathroom count **shows a clearer upward trend** in price — likely due to luxury features.

---

### 🔸 States with the Most Listings  
<img src="output/States with Most Listings.png" width="700"/>  
🏆 **Florida, California, and Texas** dominate the U.S. market in terms of listing volume.

---

### 🔸 Top 10 Most Expensive Cities  
<img src="output/Top 10 Most Expensive Cities.png" width="700"/>  
The city `International` appears incorrectly — likely due to **data entry issues** (flag for further cleaning).  
Other cities like **Woody Creek** and **Golden Oak** are known luxury zones.

---

### 🔸 Top 10 States by Average Price  
<img src="output/Top 10 States by Average Price.png" width="700"/>  
💰 **Hawaii, California, New York** top the list — consistent with real-world housing costs.

---

## ❓ Business Questions Answered  

✅ What’s the average price by state and city?  
✅ Do more bedrooms/bathrooms increase price?  
✅ Which states dominate the real estate market?  
✅ Are there suspicious outliers or bad data?  

---

## 🛠 Tools & Technologies  
- `Python`  
- `pandas`, `matplotlib`, `seaborn`  
- Jupyter Notebook (`.ipynb`)  
- Real-world dataset from Kaggle  

---

👨‍💻 About Me
Hi, I'm Shareef Ali, a passionate Data Analyst with expertise in Power BI, SQL, and Python.

📬 Let’s connect! Check out my other projects or reach out:

🔗 GitHub Portfolio
🔗 LinkedIn
🔗 Personal Website

📢 If you find this project valuable, give it a ⭐ on GitHub! ⭐
