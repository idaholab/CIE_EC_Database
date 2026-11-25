Next round of engineered controls cataloging efforts scheduled for Q2 in FY27.

# CIE Engineered Controls

A research repository from the **Cyber-Informed Engineering (CIE)** program at Idaho National Laboratory. This repository contains the Engineered Controls Database — a catalog of engineered controls mapped to cyber-physical resilience roles across all 18 DHS Critical Infrastructure sectors — along with a browser-based dashboard for exploring it.

---

## What Is Cyber-Informed Engineering?

Sponsored by Department of Energy's Office of Cybersecurity, Energy Security, and Emergency Response (CESER), CIE eliminates cyber impacts through the unbreakable laws of engineering and physics, ensuring energy dominance by embedding security into infrastructure design and helping asset owners and vendors create secure-by-design systems and reduce costly disruptions from cyber attacks.

Traditional cybersecurity alone cannot prevent catastrophic consequences in increasingly digital engineered systems. CIE closes this gap by integrating engineered controls at the physical and algorithmic levels--ensuring safety, reliability, and performance even under attack.

More information: [inl.gov/cie](https://inl.gov/cie)

---

## Repository Structure

```cmd
/
├── GUI/        Browser-based dashboard for exploring the controls database
└── Data/       Engineered Controls Database and supporting data files
```

### GUI

The `GUI/` directory contains a standalone HTML dashboard — **CIE Engineered Controls Explorer** — that runs entirely in the browser with no installation required. Load your data files and explore controls by sector hierarchy, filter by resilience role or control type, search across all entries, and view analytics. See `GUI/README.md` for usage instructions.

### Data

The `Data/` directory contains the Engineered Controls Database files used to power the hierarchy browser in addition to presentation materials for CIE Engineered Controls. See `Data/README.md` for file format documentation.

---

## Authors

**Benjamin Lampe**
Idaho National Laboratory — Cyber-Informed Engineering Program
<benjamin.lampe@inl.gov>
