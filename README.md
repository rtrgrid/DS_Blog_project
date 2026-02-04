# Why Some Indian Cities Breathe Worse Air Than Others

🔗 **Live interactive story:**  
https://rtrgrid.github.io/DS_Blog_project/

A data storytelling project investigating structural air pollution inequality across Indian cities, with Delhi as a central systems case study.

---

## Overview

This project explores why Delhi experiences persistently worse air pollution than other major Indian cities. Instead of treating pollution as isolated spikes, the analysis models it as a dynamic system shaped by emissions, geography, and atmospheric retention.

Using multi-year AQI datasets (2015–2025), the study combines seasonal analysis, baseline modeling, and the COVID lockdown natural experiment to understand how cities accumulate and disperse pollution differently.

The central finding: pollution severity is not only about how much is produced — it is about how much is allowed to remain.

---

## Research Question

Why does Delhi experience structurally worse air pollution than peer cities, and how does its recovery differ after major emission shocks?

---

## Key Findings

- Pollution inequality across cities is structural, not episodic  
- Winter pollution spikes are regional, but Delhi fails to recover  
- COVID lockdown proved pollution is rapidly reversible  
- Recovery trajectories differ sharply across cities  
- Delhi rebounds faster and accumulates pollution more aggressively  
- Geography amplifies atmospheric retention

Delhi’s crisis is driven by persistence, not just production.

---

## Methodology

The analysis pipeline includes:

- Multi-source AQI dataset harmonization  
- Pre-COVID baseline modeling (2015–2019)  
- Seasonal wave decomposition  
- Relative recovery index construction  
- Hazard exposure measurement  
- Interactive Plotly visualizations  

All transformations are reproducible via notebooks in `/analysis`.

---

## Project Architecture

Data flows from raw monitoring datasets through cleaning, modeling, and visualization into a narrative research story.

Raw AQI data → Cleaning → Baseline modeling → Seasonal analysis → Metrics → Plotly visualization → Public report

---

## Deliverables

- Reproducible analytical notebooks  
- Clean aggregated datasets  
- Interactive visualizations  
- Narrative HTML research story  
- Evidence-backed conclusions  

---

## Run Locally

```bash
pip install -r requirements.txt
jupyter notebook


Plots are saved in /plots
Final story: index.html

Or view online:

👉 https://rtrgrid.github.io/DS_Blog_project/

Tools & Stack

Python • Pandas • Plotly • Jupyter
HTML/CSS • GitHub Pages
Data storytelling methodology

Portfolio Summary

Data storytelling project analyzing structural air pollution inequality across Indian cities using multi-year AQI datasets. Built a reproducible analytical pipeline, modeled seasonal pollution behavior, and visualized post-COVID recovery dynamics. Produced an interactive narrative translating environmental systems into policy-relevant insights.

Future Work

Meteorological wind modeling

Dispersion simulation

Emissions attribution

Winter hazard prediction

Health outcome linkage

References

CPCB • OpenAQ • Public AQI datasets
Storytelling with Data • Fundamentals of Data Visualization