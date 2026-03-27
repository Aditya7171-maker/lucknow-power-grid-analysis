# ⚡ Lucknow Power Grid Network Analysis

A graph-theoretic analysis of the urban transmission network in Lucknow using real geospatial infrastructure data.

This project converts raw grid topology into a network model to evaluate **connectivity, redundancy, and structural resilience**.

---

## 🚀 What This Does

This project extracts and analyzes **real-world transmission network structure** — not synthetic data.

### Pipeline

```
OpenStreetMap → OSMnx → Graph Construction → Network Analysis → Visualization
```

---

## 📊 Key Findings

| Metric     | Value  | Insight                |
| ---------- | ------ | ---------------------- |
| Nodes      | ~8000+ | Large-scale urban grid |
| Edges      | ~8000+ | Sparse connectivity    |
| Avg Degree | ~2.0   | Tree-like structure    |
| Components | 17     | Fragmented network     |
| Cycles     | 40+    | Limited redundancy     |

### Interpretation

* Grid is **efficient but weakly redundant**
* Network shows **fragmentation risk**
* Structure resembles **radial + lightly meshed topology**
* Critical nodes likely exist with **high failure impact**

---

## 🧠 Why This Matters

Grid topology directly impacts:

* Fault tolerance
* Restoration time
* Power routing flexibility
* Infrastructure resilience

This project acts as a **foundation layer** for:

* Grid vulnerability analysis
* Contingency simulation
* Smart grid optimization
* Future VPP systems

---

## 🛠️ Tech Stack

* Python
* NetworkX
* OSMnx
* Pandas
* Matplotlib
* NumPy

---

## 🧩 Core Capabilities

### 1. Grid Extraction

* Pulls transmission infrastructure from OpenStreetMap
* Converts geospatial data into graph nodes and edges

### 2. Network Analysis

* Degree distribution
* Connected components
* Cycle detection
* Graph metrics

### 3. Visualization

* Graph topology plots
* Degree distribution charts
* Static geographic visualization

---

## ▶️ Run Locally

```
pip install -r requirements.txt
python app.py
```

---

## 📁 Project Structure

```
lucknow-power-grid-analysis/
│
├── app.py
├── requirements.txt
├── README.md
├── data/
│   ├── nodes.csv
│   └── edges.csv
├── assets/
│   ├── graph.png
│   ├── degree.png
│   └── map.png
```

---

## ⚠️ Limitations

This is a **topological model**, not a full electrical simulation.

Missing:

* Line impedance
* Power flow physics
* Voltage constraints
* Load & generation modeling

---
## 🎯 Positioning

This is NOT:

> A basic NetworkX project

This IS:

> A structural analysis of real-world power grid topology for resilience evaluation

---

## 🧠 Strategic Insight

Power grids are **networks under constraint**.

Understanding:

* topology
* connectivity
* failure points

is the foundation for:

* resilient grid design
* smart grid systems
* energy optimization platforms

---


### What this project is:

✔ Real data + graph modeling
✔ Strong engineering signal
✔ Above average portfolio quality

### What it is NOT (yet):

❌ Not a power system simulation
❌ Not optimization
❌ Not production-grade

---
