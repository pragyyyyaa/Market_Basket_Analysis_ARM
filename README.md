# Market Basket Analysis using Association Rule Mining

This project applies **Market Basket Analysis** and **Association Rule Mining (Apriori algorithm)** to uncover customer purchasing patterns from transaction data.  
The goal is to identify meaningful product associations that can support cross-selling, bundling, shelf optimization, and promotional strategy decisions.

---

## 📌 Project Overview

Market Basket Analysis helps businesses move beyond knowing *what* customers buy to understanding *how* they buy.  
By analyzing co-occurrence of items in shopping baskets, this project reveals statistically significant relationships between products commonly purchased together.

The analysis focuses on:
- Identifying frequent itemsets
- Generating high-confidence association rules
- Translating statistical results into actionable business insights

---

## 🎯 Objectives

- Discover frequent product combinations
- Identify complementary and cross-category purchase patterns
- Analyze directional buying behavior
- Support data-driven merchandising and promotion planning
- Increase average basket value through strategic recommendations

---

## 🗂️ Repository Structure

- `MBA_Association_Rule_Mining.ipynb` → Main notebook with Apriori analysis  
- `Response Sheet.xlsx` → Transaction-level input data  
- `Market Basket Analysis.pptx` → Business presentation & insights  
- `README.md` → Project documentation  
- `requirements.txt` → Python dependencies  

---

## 🔧 Methodology

1. **Data Preparation**
   - Convert survey-based binary data into transaction lists
   - Clean and structure transaction-level records

2. **Frequent Itemset Mining**
   - Apply Apriori algorithm
   - Minimum support threshold: **20%**

3. **Association Rule Generation**
   - Generate directional rules (X → Y)
   - Minimum confidence threshold: **60%**

4. **Strategic Filtering**
   - Filter rules with **Lift > 1** to remove random associations
   - Focus on statistically meaningful co-purchase behavior

---

## 📊 Key Metrics Explained

- **Support**: How frequently an itemset appears in all transactions  
- **Confidence**: Probability of purchasing item Y given item X  
- **Lift**: Strength of association beyond random chance  

---

## 📈 Key Insights

- Staple products (e.g., Atta, Rice) act as anchors for most baskets
- Strong complementary pairs enable bundle creation
- Shoppers frequently bridge grocery and personal care categories
- Directional rules identify trigger products for recommendations
- Filtered rules provide a reliable framework for merchandising decisions

---

## 🛠️ Tools & Technologies

- Python
- Pandas & NumPy
- Mlxtend (Apriori & association rules)
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🚀 How to Run the Project

1. Clone the repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the notebook:
   ```bash
   jupyter notebook MBA_Association_Rule_Mining.ipynb
   ```

---

## 👤 Author

**Pragya Gupta**  
MBA | Data Analytics | Business Intelligence
