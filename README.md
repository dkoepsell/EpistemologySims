# Cognitive Agency & Epistemic Autonomy Simulation  

A browser-based agent simulation exploring the dynamics of **Cognitive Agency (CA)** and **Epistemic Autonomy (EA)** across populations of interacting agents.  
This simulation is designed as part of ongoing research in *The Geometry of the Good* project and builds upon the conceptual framework developed in **Preston’s thesis on belief dynamics, agency, and autonomy**.  

---

## Acknowledgments & Credit  

This project would not exist without the foundational insights of **Preston [Last Name]**, whose thesis provided both the **conceptual framing** and the **motivating research question**:  

- How do variations in *cognitive agency* and *epistemic autonomy* affect social knowledge, belief distribution, and systemic stability?  

Preston’s work directly inspired the design of the CA/EA sweeps, metrics, and analysis modules included in this repository.  

---

## Features  

- 🧑‍🤝‍🧑 **1000+ agents** with configurable traits (Cognitive Agency, Epistemic Autonomy, etc.)  
- 📊 **Batch-run mode** with automatic CSV export across parameter sweeps  
- 🔄 **Interactive GUI** for toggling features, running experiments, and visualizing outcomes in real-time  
- 📈 **Data logging** for downstream statistical analysis (fulfillment rate, trust density, contradiction debt, etc.)  
- 🌐 Runs entirely **in the browser** — no server setup required  

---

## Installation  

1. Clone the repository:  

   ```bash
   git clone https://github.com/YOUR_USERNAME/cognitive-agency-sim.git
   cd cognitive-agency-sim
├── index.html           # Main browser app
├── js/
│   ├── agents.js        # Agent definitions
│   ├── simulation.js    # Core simulation loop
│   ├── gui.js           # User interface controls
│   └── config.js        # Default simulation parameters
├── data/
│   └── output.csv       # Batch-run results
├── analysis/
│   └── analysis.ipynb   # Example Jupyter Notebook for CSV data
└── README.md

If you use this simulation in academic work, please cite:

Preston, [Full Name]. [Thesis Title]. [Institution], [Year].

Koepsell, David R. The Geometry of the Good (manuscript-in-progress).

@unpublished{preston_thesis,
  author = {Preston, [Full Name]},
  title = {Title of Thesis},
  institution = {Institution Name},
  year = {Year},
  note = {Thesis forming the conceptual basis of this simulation}
}
