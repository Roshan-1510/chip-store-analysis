# Data-Driven Retail Insights: Chip Category Review & Store Trial Performance

## 🧠 Overview
This project explores retail data to uncover insights into customer purchasing behavior and evaluate the success of a store trial initiative.

**Tools Used:** Python (Pandas, Matplotlib, Seaborn), Google Colab, PowerPoint

**Deliverables:**
- Insightful visuals and charts
- Executive-ready PowerPoint using pyramid structure
- Two case studies with recommendations

---

## 📦 Dataset Summary
- **Transactions Dataset:** Includes date, store number, product name, quantity sold, and total sales.
- **Customer Dataset:** Includes customer ID, life stage, and affluence level.

---

## 📊 Case Study 1: Chip Purchase Behavior

### 🎯 Goal
Identify the highest-value customer segments and their chip buying behavior.

### 🔍 Methodology
- Merged transaction and customer data on loyalty card number
- Created a `Segment` column combining Life Stage and Premium Customer status
- Aggregated sales by segment and visualized performance

### 📈 Key Visuals
- Total sales by customer segment
- Monthly sales trends
- Average spend per transaction

### 🧠 Insights
- **Top Segment:** Older Families - Budget
- **Preferred Products:** Bold-flavored value packs (e.g., Kettle, Doritos)
- **High Spenders:** This group leads in total and average transaction value
- **Seasonality:** Sales peak in mid-year (June–August)

### ✅ Recommendation
Target the Older Families - Budget segment with seasonal promotions on value packs. Prioritize popular brands and capitalize on mid-year demand.

---

## 🧪 Case Study 2: Store Trial Performance

### 🎯 Goal
Evaluate if test stores (77, 86, 88) outperformed similar control stores.

### 🔍 Methodology
- Computed: total sales, customer count, and average transactions per customer
- Selected control stores using magnitude distance (Euclidean similarity)
- Compared performance across trial months (Feb–Apr)

### 🔍 Control Store Matches
- Store 77 → Control: 46
- Store 86 → Control: 229
- Store 88 → Control: 40

### 📈 Sample Metrics for Store 77
| Metric                  | Trial Store 77 | Control Store 46 |
|-------------------------|----------------|------------------|
| Total Sales (Feb–Apr)   | $1,331.20      | $1,358.40        |
| Customer Count          | 142            | 115              |
| Transactions/Customer   | 3.12           | 3.14             |

### ✅ Recommendation
Store 77 outperformed its control in sales and customer engagement. Recommend scaling trial to stores with similar profiles to Store 77.

---

## 📁 Outputs
- `chip-purchase-analysis.ipynb` (Python notebook)
- `store-trial-analysis.ipynb` (Python notebook)
- `Final_PPT_Deck.pptx` (Executive Summary presentation)
- Exported charts (PNG format)

---

## 🚀 Learnings
- Retail segmentation using demographics
- Merging and cleaning large datasets
- Visual analytics with Seaborn/Matplotlib
- Statistical similarity for control-test matching
- Executive storytelling with data

---

## 💬 Contact
For questions, reach out via [LinkedIn](https://www.linkedin.com/) or open an issue.

> Project by [Your Name] | April 2025
