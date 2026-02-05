> **An in-depth analysis of sales performance, consumer behavior, and growth trends (2022-2025).**

## 📝 Project Overview
This project performs a comprehensive analysis of an E-Commerce dataset consisting of 3,500 transactions. The goal was to transform raw sales data into actionable business intelligence using Python. The project covers data processing, advanced feature engineering, and a deep dive into time-series forecasting trends.

## 🚀 Key Features & Engineering
- **Advanced Metrics:** Calculated `Profit_Margin_Pct`, `COGS`, and `Unit_Profit` to evaluate item efficiency.
- **Behavioral Features:** Developed `Is_Weekend` and `Order_Intensity` tags to categorize customer buying habits.
- **Temporal Analysis:** Processed `Order Date` to extract seasonality trends across years, months, and days.

---

## 📈 Strategic Observations

### **Observation 1: Product Performance**
* **The MVP (Laptop):** Highest profit margin and sales volume.
* **The Efficiency King (Camera):** Low unit cost with high-volume sales, representing a low-risk/high-reward product.
* **The Laggard (Keyboard):** Lowest profit margin (~16.9%), requiring a pricing strategy review.

### **Observation 2: Time Series & Growth**
* **Cumulative Revenue:** The business hit a **$10 Million milestone** by Jan 2025 with consistent, linear growth.
* **Stability:** While monthly sales fluctuate (peaking at $400k), profit remains stable below $75k, indicating a well-managed but fixed-margin cost structure.

### **Observation 3: Weekly Seasonality**
* **Peak Shopping:** **Sunday** is the highest-performing day (>$1.6M), while **Wednesday** is the slowest (~$1.4M).
* **Action Plan:** Launch mid-week "Flash Sales" on Wednesdays to optimize inventory turnover during slow periods.

---

## 🛠️ Tech Stack
- **Language:** Python 3.10+
- **Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 📂 Project Structure
- `E-Commerce Dataset.ipynb` - Main analysis and visualization notebook.
- `ecommerce_sales_data.csv` - The raw transaction data.
- `requirements.txt` - Required libraries for reproduction.

---