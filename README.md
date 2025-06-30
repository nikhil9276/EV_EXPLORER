# ⚡ EV Performance Explorer 🚗🔋

A Power BI Dashboard project for analyzing Electric Vehicle (EV) performance across multiple dimensions such as battery capacity, electric range, efficiency, acceleration, and brand-level insights.

---

## 📊 Project Objective

To create an interactive, user-friendly dashboard that allows exploration of:
- EV performance metrics (range, battery, torque, speed)
- Manufacturer-wise efficiency and acceleration stats
- Insights into EV segments, top brands, and outlier models

---

## 📁 Project Structure

This Power BI project consists of **4 pages**:

### 🔹 Page 1 – Overview
- **Avg Range** (KM), **Avg Battery Capacity**, **Range per kWh**
- Scatter Plot: **Battery Capacity vs Range**
- Pie Chart: **Top Vehicle Segments**

### 🔹 Page 2 – Performance & Efficiency
- Max values: **Range**, **Towing Capacity**, **Battery**
- Bar Charts: **Top Speed by Brand**, **Torque by Brand**
- Pie Chart: **Model Distribution by Efficiency Category**
- Donut Chart: **Brand Efficiency (Wh/km)**

### 🔹 Page 3 – Brand-Level Breakdown
- **Most Efficient Brand**
- **Top 10 EVs by Range per kWh**
- **Acceleration Score (0–100 km/h)**
- Visual: **Torque vs Range vs Acceleration**

### 🔹 Page 4 – Key Insights (Text)
- Summary of 7 key takeaways from the visuals above

---

## ✅ Key Features

- Built using **Power BI Desktop**
- Uses **bar, pie, donut, scatter, and card visuals**
- Interactivity via **slicers and filters**
- Clear layout for stakeholders or consumers comparing EVs

---

## 💡 7 Key Insights

1. 🔋 **Higher battery capacity strongly correlates with longer range**.
2. 🏎️ **Porsche and Tesla** dominate in both torque and top speed performance.
3. 📊 Majority of EVs fall into the **"Average Efficiency"** category (76%).
4. 🌿 **Dacia** is identified as the **most efficient brand** (111.5 Wh/km).
5. 🔝 **Model 3 Highland** and **Cooper E** are top in **range per kWh**, indicating superb efficiency.
6. 📉 Some brands deliver **very high torque** without proportional top speeds — showing a weak correlation.
7. 🚙 **Medium and Large vehicle segments** dominate the EV market based on model count.

---

## 🧩 Data Fields Used

- `Range (km)`
- `Battery Capacity (kWh)`
- `Efficiency (Wh/km)`
- `Torque (Nm)`
- `Top Speed (km/h)`
- `Segment`, `Brand`, `Model`
- `Acceleration (0–100 km/h)`
- `Number of Battery Cells`
- Derived Fields:
  - `Range_per_kWh`
  - `Efficiency Category`

---

## 🛠️ Getting Started

### 1. **Requirements**
- Power BI Desktop (latest version)
- Dataset: Electric Vehicles performance dataset (CSV/Excel)
- Optional: Custom fonts, icons for design enhancements

### 2. **Setup**
- Open Power BI Desktop
- Load the dataset(s)
- Ensure calculated columns like `Range_per_kWh` are added
- Build each page as described above or import the `.pbix` file if available

---

## 🧭 Usage Guidelines

- Use **filters** to slice data by brand, segment, or efficiency
- Hover over visuals to view **tooltips**
- Customize visuals per presentation need (dark/light mode, highlight brands, etc.)
- For performance comparison, use Page 3 visuals (Range per kWh and acceleration)

---

## 📌 Future Enhancements

- Add **forecasting** using time-series if data is available
- Embed in a website or **Power BI Service** for live interaction
- Include a **cost analysis** for ROI and purchase decisions

---

## 🙋‍♂️ Author

**Nikhil Kumar**  
Data Science & Analytics Enthusiast  
🎯 Tools: Python | Power BI | SQL  
📍 From Patna, India

---

