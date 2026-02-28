# 🎮 Video Game Sales Market Analysis  
EDA, Regional Market Profiling & Hypothesis Testing (2016 snapshot)

---

## 📖 Project Overview

This project analyzes historical video game sales, user and critic reviews, genres, platforms, and ESRB ratings to identify patterns associated with commercial success. The goal is to support campaign planning by highlighting promising platforms and genres and by profiling regional market behavior (NA, EU, JP) using data-driven insights.

---

## 🎯 Business Objective

Identify patterns associated with commercially successful video games to support marketing campaign planning for 2017.

- Identify trends that correlate with successful game sales  
- Understand platform life cycles and shifting popularity over time  
- Build regional user profiles to support localized campaign decisions  
- Validate business assumptions through statistical hypothesis testing  

---

## 🗂 Dataset

The dataset includes:
- Game metadata (platform, release year, genre, ESRB rating)  
- Sales by region (NA, EU, JP, Other)  
- Critic and user scores  

A global sales feature is created by aggregating regional sales.

---

## 🛠️ Methodology

### 1️⃣ Data Preparation
- Standardization of column names and data types  
- Handling missing values and "TBD" user scores  
- Feature creation (global sales)  

### 2️⃣ Exploratory Data Analysis (EDA)
- Release trends over time and relevance of recent years  
- Platform sales dynamics and life cycle analysis  
- Cross-platform comparisons using boxplots  
- Relationship between scores and sales (correlation + scatter plots)  
- Genre profitability analysis  

### 3️⃣ Regional Market Profiling
For NA, EU, and JP:
- Top platforms and market share differences  
- Top genres and regional preferences  
- ESRB rating impact on sales by region  

### 4️⃣ Hypothesis Testing
- Null hypothesis (H0) 
- Alternative hypothesis (H1))  
- Alpha level
- Test result
- Interpretation

---

## 📈 Key Deliverables

- Platform and genre recommendations for campaign planning  
- Regional market profiles to support localized strategies  
- Statistical conclusions supported by hypothesis testing  

---

## 🧰 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- SciPy  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## Strategic Conclusion

Recent platform trends suggest focusing marketing investments on growing platforms with stable global sales performance. Regional differences indicate that campaign strategies should be localized, particularly considering genre preferences and ESRB sensitivity in Japan versus North America and Europe.

Statistical testing supports evidence-based decision-making rather than assumption-driven strategy.
