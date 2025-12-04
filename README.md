# Quantium Data Analytics – Chips Category Analysis (Task 1)

This project contains my solution for **Task 1** of the Quantium Data Analytics Virtual Experience (Forage). The goal is to analyse chip purchasing behaviour and provide insights for the Category Manager, Julia.

---

## 📂 Files
- `chips_analysis.ipynb` – Full analysis in Python  
- `QVI_transaction_data.xlsx` – Transaction dataset  
- `QVI_purchase_behaviour.csv` – Customer dataset  

---

## 🔍 Project Summary

### 1. Data Cleaning
- Converted dates from Excel format  
- Removed salsa products  
- Removed bulk outlier customer  
- Extracted `PACK_SIZE` and `BRAND`  
- Standardised brand names  
- Merged customer + transaction data  

### 2. Segment Analysis
Analysed customer groups by LIFESTAGE and PREMIUM_CUSTOMER.  
Key drivers of sales were:

- **Budget Older Families**  
- **Mainstream Young Singles/Couples**  
- **Mainstream Retirees**

### 3. Target Segment Deep Dive  
Selected **Mainstream Young Singles/Couples** due to:
- Large customer base  
- High total sales  
- Premium brand preference  

**Top brands:** Kettle, Doritos, Pringles, Smiths  
**Top pack sizes:** 150g–175g, 134g Pringles  

---

## 📝 Recommendations
- Focus on premium mid-sized packs (150–175g)  
- Increase visibility of Kettle, Doritos, Pringles, Smiths  
- Use bundle promotions (“2 for X”)  
- Maintain value packs for Family segments  
- Ensure strong stock availability of top sizes  

---

## 🛠 Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

---

## 👩‍💻 Author
**Bhoomi P. Nayak**  
GitHub: [@BhoomiNayak](https://github.com/BhoomiNayak)

