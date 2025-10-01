# 🌋 Earthquake Trends & Alerts: Seismic Data Analysis  

## 📌 Overview  
This project analyzes global earthquake data, focusing on **magnitude, depth, intensity (CDI, MMI), significance scores, and alert levels**.  
The goal is to explore seismic activity patterns, identify high-risk events, and visualize trends that can support disaster awareness and preparedness.  

---

## 📊 Dataset  
- **Features included**:  
  - `magnitude`: Strength of the earthquake  
  - `depth`: Depth in km  
  - `cdi`: Community Internet Intensity (perceived impact)  
  - `mmi`: Modified Mercalli Intensity (structural impact)  
  - `sig`: Significance score of the event  
  - `alert`: Alert level (green, yellow, orange, red)  

- **Source**: *Dataset to be uploaded into the repo*  

---

## 🔍 Objectives  
- Explore statistical distributions of earthquake magnitude and depth.  
- Compare **intensity indicators (CDI, MMI)** across different magnitudes.  
- Investigate correlation between **depth and alert level**.  
- Visualize global patterns of earthquake severity.  
- Provide insights into **high-risk earthquake conditions**.  

---

## 📈 Key Insights & Visualizations  
✅ Distribution of earthquake magnitudes & depths  
✅ Heatmaps showing correlation between magnitude, intensity, and alert levels  
✅ Bar plots of frequency of each **alert category**  
✅ Highlight of top significant earthquakes (`sig` feature)  
✅ Risk trend analysis based on depth vs magnitude  

---

## 🛠️ Tech Stack  
- **Python**  
- **Pandas** (data wrangling)  
- **Seaborn & Matplotlib** (visualizations)  
- **Scikit-learn** (optional: clustering / predictive modeling)  

---

## 🚀 How to Run  
```bash
# Clone repository
git clone https://github.com/lightonkalumba/earthquake-trends-alerts.git

# Navigate into project folder
cd earthquake-trends-alerts

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
