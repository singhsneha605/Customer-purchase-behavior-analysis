# Customer Purchase Behavior Analysis
**Tools:** Python · Pandas · NumPy · Matplotlib · Seaborn  
**Dataset:** UCI Online Retail II — Real UK e-commerce transactions (1M+ rows)



## Dataset
**Kaggle link:** https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci



## How to Run
```bash
pip install pandas numpy matplotlib seaborn
python customer_analysis.py
```


## What the Code Does
1. **Data Cleaning** — removes cancelled orders, missing Customer IDs, negative quantities
2. **EDA** — summary stats, revenue by country, top products
3. **Repeat Customer Analysis** — one-time vs repeat buyers
4. **RFM Segmentation** — classifies customers into 4 segments using Recency, Frequency, Monetary scoring
5. **Visualisations** — 6 charts 
6. **Export** — saves RFM segment output as CSV



## Key Insights (from real data)
- Dataset contains **1M+ real transactions** from a UK gift retailer (2009–2011)
- **38+ countries** represented
- Real data messiness handled: cancellations, missing IDs, negative quantities
- RFM segmentation identifies Champions, Loyal, Potential, and At-Risk customers



## Output Files
```
CUSTOMER PURCHASE BEHAVIOR.ipynb  ← 6 visualisation charts
rfm_segments_output.csv        ← customer segment assignments
```



## Skills Demonstrated
`Data Cleaning` · `EDA` · `RFM Segmentation` · `Customer Analytics` · `Data Visualisation` · `Business Reporting`
