# ⚡ Lucknow Power Grid Network Analysis

This project models the transmission network of Lucknow using graph theory and real-world OpenStreetMap data.

## 🚀 Features
- Extracts real grid data using OSMnx
- Converts transmission lines into graph topology
- Performs network analysis using NetworkX
- Visualizes:
  - Degree distribution
  - Cycle distribution
  - Graph structure
  - Geographic grid map (Folium)

## 📊 Key Results
- Nodes: ~8000+
- Edges: ~8000+
- Connected Components: 17
- Average Degree: ~2.0
- Cycles detected: 40+

## 🧠 Tech Stack
- Python
- NetworkX
- OSMnx
- Streamlit
- Folium

## ▶️ Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
