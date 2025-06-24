# Agro-Data-Analytics

**Analyzing Decadal Trends in Vegetables and Beans: Production, Stocks, and Imports (1970–2020)**

This project explores patterns in the U.S. vegetables and beans supply chain using historical agricultural datasets. Developed for AIT-614, it combines cloud-based data engineering, statistical modeling, and machine learning techniques to identify insights about scarcity, surplus, and supply chain efficiency.

---

## Team Members
- Aravind Panchanathan  
- Suparna Mannava  
- Mayuri Jadhav  
- Sujatha Ganesan  

---

## Research Objectives

### Core Research Question:
Do decadal trends in domestic availability correlate with ending stock ratios, and can these trends signal potential periods of scarcity or surplus?

### Sub-questions:
1. **Impact of Imports on Availability & Stocks:**  
   Does increased availability reduce imports and ending stocks? Or do high imports suppress domestic production?

2. **Shelf Life & Stock Depletion Efficiency:**  
   How does product type (fresh, canned, frozen) influence the difference between beginning and ending stocks?

---

## Data Mining Techniques

- **K-Means Clustering**  
  - Feature selection & normalization  
  - Clustering trends across decades  
  - Evaluated using silhouette scores  

- **Forecasting with ARIMA**  
  - Time-series modeling of domestic availability and ending stocks  
  - Diagnostic and statistical tests for forecast validation  

- **Classification using Random Forest**  
  - Classification of scarcity/surplus years  
  - Evaluated using ROC curves & confusion matrices  

---

## Data Engineering & Architecture

- **Data Source**: USDA ERS Vegetables and Pulses Yearbook (1970–2020)  
- **Storage**: AWS S3  
- **Processing**: Databricks Notebooks  
- **Visualization**: Tableau  
- **Version Control**: GitHub integrated with Databricks Repos  

---

## Dataset Overview

### Vegetables (1970–2020)  
- Fresh, Canned, Frozen, Processed  
- Metrics: Beginning Stocks, Production, Imports, Exports, Ending Stocks, Seed Use, Feed Loss  

### Beans (1980–2020)  
- Metrics include storage categories & spoilage  

---

## Visual Analysis Highlights

- Long-term trends across decades  
- Differences in depletion rates between fresh vs. frozen/canned  
- Import-to-stock ratios signaling reliance patterns  
- Stock buffers in times of production shortages  
