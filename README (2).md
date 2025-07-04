
# 🚗 US Traffic Accident Analysis (EDA)

This project analyzes US traffic accident data to uncover patterns related to time, weather, and road conditions. It also visualizes accident hotspots across the country using an interactive Folium heatmap.

---

## 📁 Dataset
- **Source**: [Kaggle - US Accidents EDA](https://www.kaggle.com/code/harshalbhamare/us-accident-eda)
- **Records**: ~2.8 million accidents (2016–2021)
- **Features**: Time, location, weather, severity, road features, etc.

---

## 🔍 Project Objectives

- Analyze accident frequency by **hour**, **day**, and **month**
- Study the impact of **weather conditions** on accident risk
- Identify road features linked with high accident rates (e.g., junctions, traffic signals)
- Visualize **accident hotspots** using a Folium heatmap

---

## 🛠️ Tools Used

- Python (Jupyter Notebook)
- Libraries:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `folium`, `folium.plugins`

---

## 📊 Key Insights

- Peak accidents occur during **rush hours (7–9 AM and 4–6 PM)**
- Most accidents happen on **weekdays**, especially **Friday**
- **Rain, snow, and fog** increase the chances of accidents
- **Junctions** and **traffic signals** are high-risk locations
- Hotspots are clustered in **urban areas** like LA, NYC, Houston, and Florida

---

## 🌍 Output Files

- `accident_analysis.ipynb` → Jupyter Notebook
- `accident_hotspots_map.html` → Interactive map of accident density
- `accident_report.pdf` → Report version of the notebook (for presentation or print)

---

## 🚀 How to Run

1. Install requirements:
   ```bash
   pip install pandas matplotlib seaborn folium
   ```

2. Open the notebook:
   ```bash
   jupyter notebook accident_analysis.ipynb
   ```

3. Run all cells and open:
   - The map: `accident_hotspots_map.html`
   - The report: `accident_report.pdf`

---

## 👩 Author

- **Netika Tiwari**
- Internship Project: **ProDigy Infotech**
