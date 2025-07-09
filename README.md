# 📝 Global Tech Layoffs Analysis (2022–2025)

**👨‍💻 Author:** Mubasshir Ahmed  
**🛠 Tools Used:** MySQL  
**📊 Project Type:** Data Cleaning + EDA (Exploratory Data Analysis)  
**📂 Dataset Source:** [Kaggle – Tech Layoffs Dataset](https://www.kaggle.com/datasets/swaptr/layoffs-2022)  
**🔗 GitHub Repo:** [MySQL-Mastery-Journey](https://github.com/mubasshirahmed-3712/MySQL-Mastery-Journey)

---

## 🔍 Project Objective

This project aimed to clean and analyze global tech layoff data between **2022 and 2025**, using only **SQL** – without any BI tools or programming frameworks. The goal was to derive **insightful trends, patterns, and red flags** about how tech companies worldwide responded to economic conditions through layoffs.

---

## 🧹 Data Cleaning Summary (6-Step Process)

| ✅ Step | Task Description |
|--------|------------------|
| Step 1 | Created staging tables to preserve original raw data |
| Step 2 | Removed 231 duplicate rows using `ROW_NUMBER()` |
| Step 3 | Standardized inconsistent industry values (e.g., `"CryptoCurrency"` → `"Crypto"`) |
| Step 4 | Cleaned up country names (e.g., `"United States."` → `"United States"`) |
| Step 5 | Converted `date` from **TEXT → DATE** using `STR_TO_DATE()` |
| Step 6 | Dropped 94 rows with missing `total_laid_off` and `percentage_laid_off` |

---

## 📊 EDA (Exploratory Data Analysis) – Key Insights

### 1. 📈 Layoff Volume Over Time  
- **Total layoffs recorded:** 212,000+  
- **Peak month:** January 2023  
- Rolling layoffs nearly **tripled** from 2022 to 2023

### 2. 🏢 Top 3 Companies by Total Layoffs  

| Rank | Company  | Employees Laid Off |
|------|----------|---------------------|
| 1️⃣  | Meta     | 11,000               |
| 2️⃣  | Amazon   | 10,000               |
| 3️⃣  | Google   | 9,000                |

### 3. 🌍 Layoffs by Country  
- **🇺🇸 United States** contributed to **70%+** of global layoffs

### 4. 💼 Top 3 Impacted Industries  

| Industry    | % of Total Layoffs |
|-------------|--------------------|
| FinTech     | 25%                |
| Crypto      | 21%                |
| E-commerce  | 17%                |

### 5. 🚨 Funding vs Collapse  
- **15+ companies** raised over **$100M+** and still laid off **100%** of their employees  
- Example: **Quibi** raised **$1.75B** and completely shut down

### 6. 👩‍🚀 Stage-Based Layoffs  
- Companies in **Series C/D** rounds had the **highest layoffs**, pointing to unsustainable growth models

---

## 📌 Business Impact (Resume Highlights)

- 🧼 Cleaned and standardized **1,937 records** using advanced SQL techniques  
- 📊 Extracted **15+ critical insights** using **Joins, CTEs, Subqueries, and Window Functions**  
- 📈 Enabled actionable business understanding for real-world use cases  
- 💡 Simulated end-to-end **SQL Data Analytics workflow** — from raw to insights

---

## 📷 Dashboard Mockup Preview

*Sample visualization design (for future Power BI / Tableau deployment)*

![Dashboard Preview](assets/Tech%Layoffs%Analysis.png)


---

## 💡 What I Learned

- ✅ Full-cycle SQL: Joins, Subqueries, CTEs, Data Cleaning, Window Functions  
- 🎯 Importance of EDA and understanding business context behind queries  
- 📊 Structured thinking from messy data → cleaned → analyzed → interpreted

---

## 📁 Project Folder Structure

```
Global-Tech-Layoffs-Analysis-2022-2025/
├── Dataset/
│   └── layoffs.csv
├── SQL/
│   └── Global Tech Layoffs Analysis (2022–2025).sql
├── assets/
│   └── Tech_Layoffs_Analysis.png
├── README.md
├── LICENSE
└── Global-Tech-Layoffs-Analysis-2022-2025.pdf
```

---

## ⭐ What’s Next?

- 🛠 Convert insights into a live Power BI / Tableau Dashboard  
- ✍️ Publish a LinkedIn post/article summarizing insights  
- 🧠 (Optional) Forecast layoffs using ML or time-series modeling in Python

---

> 💬 _If you found this helpful, don’t forget to ⭐ the repository and follow me!_  
👉 [Visit GitHub Repo](https://github.com/mubasshirahmed-3712/MySQL-Mastery-Journey)
