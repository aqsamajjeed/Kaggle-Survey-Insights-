# Kaggle Data Science Survey (2017–2021) Analysis  

## 📌 Project Overview  
This project analyzes the **Kaggle Data Science & Machine Learning Survey (2017–2021)** to clean messy data, standardize categorical variables, and generate insights about the global data science community.  

The survey includes responses from thousands of professionals, students, and enthusiasts across the world. The focus of this project is on **data cleaning, categorical handling, and insight generation**.  

---

## 🛠️ Key Steps  
1. **Data Loading & Renaming**  
   - Imported raw CSV and renamed ambiguous column labels for clarity.  

2. **Data Cleaning**  
   - Standardized **Gender** and **Education** categories.  
   - Filled missing values with appropriate defaults/medians.  
   - Converted survey duration into integer values.  

3. **Feature Engineering**  
   - Transformed **Age ranges** into numerical midpoints.  
   - Encoded **Coding Experience** into numeric years (e.g., `<1 years` → 0.5, `20+ years` → 23).  

4. **Summary Tables & Insights**  
   - Distribution of respondents by **year, gender, and country**.  
   - Top job roles and education levels.  
   - Median coding experience and survey duration by year.  
   - Time-based insights, such as changes in participation trends.  

---

## 📊 Key Insights  
- **Dominance of Students & Early-Career Professionals**: Many respondents are either students or new professionals in the data field.  
- **Global Reach**: Majority participation from India, USA, and other top 10 countries.  
- **Rising Engagement**: Survey completion times and participant diversity evolved across years.  
- **Experience Gap**: A large portion of respondents have less than 5 years of coding experience.  

---

## 🚀 Tools & Libraries  
- **Python** (Pandas, NumPy)  
- **Matplotlib, Seaborn** for visualization  

---

## 📈 Bonus (Future Work)  
- Develop a **dashboard** (Power BI / Tableau) for interactive exploration.  
- Extend analysis to deeper **career trends** across years.  

 
