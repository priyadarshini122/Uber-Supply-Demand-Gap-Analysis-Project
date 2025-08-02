# 🚗 Uber Supply-Demand Gap Analysis

This project analyzes ride request data from Uber to identify critical supply-demand gaps across different time slots and pickup locations using Python.

---

## 📌 Objective

To uncover when and where Uber experiences the highest number of:
- Cancellations
- No cars available
- Demand exceeding supply

---

## 🔧 Tools Used

- Python (Pandas, NumPy)
- Matplotlib & Seaborn (Data Visualization)
- Jupyter Notebook
- SQL (for queries)
- Excel (for dashboards and summary)

---

## 📊 Key Steps

1. **Data Cleaning & Wrangling**
   - Converted timestamps to datetime
   - Handled missing values in `Driver ID` and `Drop timestamp`
   - Extracted `hour` and created a `Time Slot` feature

2. **Exploratory Data Analysis (EDA)**
   - Overall status distribution
   - Requests by time slot and pickup point
   - Supply-demand gap detection using visualizations

3. **Visualizations**
   - Status distribution by time slot
   - Requests by pickup point
   - Requests by hour of the day

---

## 💡 Key Insights

- High **cancellations** in the Early Morning and Morning hours
- **No Cars Available** mostly during Night and Late Night slots
- **City pickups** have high cancellations; **Airport pickups** face more unavailability at night

---

## ✅ Business Recommendations

- Offer **driver incentives** during Early Morning and Night hours
- Implement **night shifts** at Airport
- Use demand prediction models to pre-allocate drivers dynamically

---

## 📁 Files Included

- `Uber_Supply_Demand_EDA.ipynb` – Python analysis notebook
- `Uber_Request_Cleaned.csv` – Cleaned dataset
- `Uber_Supply_Demand_Queries.sql` – SQL queries for insights
- `Uber_Supply_Demand_Insights.pdf` – Key insights report (optional)
- `README.md` – Project documentation

---

## 🎥 Demo

You can watch the project explanation video [here](https://your-video-link.com) *(Add your Loom or Zoom recording link)*

---

## 👩‍💻 Author

**[Your Name]**  
Aspiring Data Analyst | Python | Power BI | SQL  
📧 [YourEmail@example.com] | 🌐 [LinkedIn/GitHub Profile]

