# AI1030 — Individual Assignment 2
## Market Basket Analysis on Groceries

**Course:** AI1030 — Python Programming

---

## 1. Introduction
Perform an end-to-end market basket analysis on a real grocery dataset. Load and inspect the CSV, clean and transform it into a canonical transactions format, assign prices, compute basket totals, and derive co-occurrence statistics for product pairs and triples. Produce clear visualizations and a short report explaining methodology and findings.

---

## 2. Data
**File:** `groceries.csv` (from Moodle). The raw schema may vary:
- One row per transaction with a comma-separated `Items` field, or
- Two columns like `TransactionID, Item` in tall format.

**Canonical schema (post-cleaning):**
- `transaction_id`: string or int  
- `items`: list of product strings  
- `basket_size`: int  
- `basket_total`: float

---