# AI1030 — Individual Assignment 2  
## Market Basket Analysis on Groceries  

### Course
AI1030 — Python Programming  

### Student
Rui Gao


---

## Overview
This project performs a **Market Basket Analysis** on the `groceries.csv` dataset.  
It processes raw transaction data, cleans and structures it into a canonical format, assigns prices, computes co-occurrence statistics (pairs/triples), and produces visualizations such as top items, frequent pairs, co-occurrence heatmaps, and network graphs.  

All required tasks from the project brief have been **completed**, including:
- Data loading, cleaning, and transformation  
- Price assignment and basket total computation  
- Co-occurrence statistics for pairs and triples  
- Configurable `min_count` and `top_k`  
- Multiple visualizations (bar charts, heatmap, distribution plots)  

Additionally, the following **extensions** were implemented:
- **Netowrk Grpah:** Graphed a network figure of co-occurence matrix and selected top pairs/triples to display correlation
- **Association Rules:** Computed *confidence* and *lift* for top pairs/triples and interpreted which are most informative.  
- **Revenue Scenarios (Partial):** Random ±10% price perturbations simulated to observe effects on basket totals and top revenue-contributing pairs.  

---

## Files Included
- `data.ipynb` — main notebook with all data processing, analysis, and visualization steps  
- `groceries.csv` — input dataset  
- `outputs/` — folder containing generated CSVs and figures  
- `photo dump/` - pictures embedded in report
- `AI1020_Individual_Assignment_2_Report_Rui_Gao` - main project report that would be submitted.
---

## How to Run
### Requirements
Python 3.9+  
Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn networkx pyarrow
```
Then run the data.ipynb file cell by cell to see the intended performance