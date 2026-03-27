##⚡ Lucknow Power Grid Network Analysis

A graph-theoretic analysis of the urban transmission network in Lucknow using real geospatial infrastructure data.

This project converts raw grid topology into a network model to evaluate connectivity, redundancy, and structural resilience.

🚀 What This Does

This project extracts and analyzes real-world transmission network structure.

Pipeline:

OpenStreetMap → OSMnx → Graph Construction → Network Analysis → Visualization
##📊 Key Findings
Metric	Value	Insight
Nodes	~8000+	Large-scale urban grid
Edges	~8000+	Sparse connectivity
Avg Degree	~2.0	Tree-like structure
Components	17	Fragmented network
Cycles	40+	Limited redundancy
Interpretation
Grid is efficient but weakly redundant
Network shows partial fragmentation
Structure resembles radial + lightly meshed topology
High risk of failure propagation from critical nodes
🧠 Why This Matters

##Grid topology directly affects:

Fault tolerance
Restoration time
Power routing flexibility
Infrastructure resilience

##This project serves as a base for:

Vulnerability analysis
Contingency simulation
Grid optimization
Future VPP systems
🛠️ Tech Stack
Python
NetworkX
OSMnx
Pandas
Matplotlib
NumPy
##🧩 Core Capabilities
1. Grid Extraction
Pulls transmission infrastructure from OpenStreetMap
Converts geospatial data into graph nodes and edges
2. Network Analysis
Degree distribution
Connected components
Cycle detection
Graph metrics
3. Visualization
Graph topology plots
Degree distribution charts
Static geographic visualization
▶️ Run Locally
pip install -r requirements.txt
python app.py
##⚠️ Limitations

This is a topological model, not a physical power system simulation.

##Missing:

Line impedance
Power flow modeling
Voltage constraints
Load and generation dynamics
