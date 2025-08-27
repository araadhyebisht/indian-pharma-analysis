# Indian Pharma Data Analysis  

## 📌 Overview  
This project performs an **Exploratory Data Analysis (EDA)** of Indian pharmaceutical product data.  
The analysis highlights **pricing trends, pack-size distribution, and manufacturer dominance** to provide insights useful for:  
- Product Managers  
- Pharma Analysts  
- Data Scientists  

---

## 📂 Dataset  
- **Source**: Public dataset of Indian medicines (structured CSV)  
- **Size**: ~250,000+ rows  
- **Key Columns**:  
  - `manufacturer_name` – Manufacturer  
  - `pack_size_label` – Pack size (e.g., strip of 10 tablets)  
  - `price(₹)` – Price in INR  
  - `form` – Form of drug (tablet, syrup, injection, etc.)  

---

## 🔍 Analysis Performed  
1. **Data Cleaning**  
   - Removed duplicates  
   - Handled missing values  
   - Standardized column formats  

2. **Exploratory Data Analysis (EDA)**  
   - Top manufacturers by number of products  
   - Price distribution across drugs  
   - Most common pack sizes  
   - Comparison of manufacturers based on affordability  

3. **Visualization**  
   - Bar plots for top manufacturers  
   - Price distribution histograms  
   - Pack-size usage trends  

---

## 📊 Key Insights  
- **Serum Institute of India** and a few others dominate large portions of the dataset.  
- **Strip of 10 tablets** is the most common pack size across pharma companies.  
- Pricing varies widely between manufacturers for the same pack size.  
- Affordable generics are concentrated among a small group of companies.  

---

## ⚙️ How to Run  
```bash
git clone https://github.com/araadhyebisht/pharma-data-analysis.git
cd pharma-data-analysis
pip install -r requirements.txt
jupyter notebook "project analysis cv.ipynb"
