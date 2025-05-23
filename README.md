# 🛒 Retail-Transactions-Data-Analysis

Python-based analysis of Kosatec's product assortment overlap with e-commerce shops. This Jupyter Notebook uses data merging, deduplication, fuzzy matching, and product count statistics to uncover competitive insights for strategic portfolio development.

---

## 📌 Project Objective

To analyze and compare the product assortments of **Kosatec** with 22 leading online retailers in order to:
- Identify common products and market trends.
- Evaluate overlap and gaps in Kosatec’s offerings.
- Highlight top brands and product categories.
- Recommend strategic enhancements for Kosatec's catalog.

---

## 📊 Key Features

- Merges 22 CSV files with different schemas into a unified format.
- Applies prioritized product matching (EAN > MPN > Article Number).
- Calculates product frequency across shops to assess demand.
- Highlights missing products in Kosatec’s portfolio.
- Identifies most represented brands and categories.
- Provides visual analysis and strategic insights.

---

## 🧪 Methodology

1. **Data Cleaning & Normalization**  
   Standardizes columns like `product_ean`, `manufacturer_number`, and `article_number`.

2. **Deduplication & Matching Logic**  
   Ensures unique product listings using available identifiers.

3. **Shop Count & Overlap Analysis**  
   Calculates how many shops carry each product and maps overlap with Kosatec.

4. **Gap & Brand Analysis**  
   Quantifies what Kosatec is missing and highlights market leaders.

5. **Visualization**  
   Generates bar charts and pie charts to illustrate findings clearly.

---

## 📂 File Structure

- `Data Analysis Codes.ipynb`: Main analysis notebook.
- `Strategic Analysis 23 Retailers.docx`: Executive summary report with charts and insights.
- `data/`: Folder for input CSV files (excluded here for privacy).

---

## 📈 Sample Findings

- **84.76%** overlap between Kosatec and market offerings.
- **54.67%** market assortment is missing from Kosatec's portfolio.
- Top brands: **Phs-Memory**, **Lenovo**, **Apple**, **HP Enterprise**.
- Leading categories: **PC Components**, **IT & Multimedia**, **Smartphones**.

---

## 🚀 How to Use

```bash
# Clone the repository
git clone https://github.com/your-username/Retail-Transactions-Data-Analysis.git

# Open Jupyter Notebook
jupyter notebook "Data Analysis Codes.ipynb"
