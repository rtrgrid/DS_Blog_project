# Why Some Indian Cities Breathe Worse Air Than Others

🔗 **Live interactive story:**  
https://rtrgrid.github.io/DS_Blog_project/

A data storytelling research project investigating structural air pollution inequality across Indian cities, with Delhi as a central systems case study.

---

## Research Abstract

This project investigates why certain Indian cities — particularly Delhi — experience persistently higher air pollution exposure despite comparable urban growth trajectories. Using multi-year AQI datasets (2015–2025), the study treats pollution as a dynamic system shaped by emissions, geography, and atmospheric retention rather than isolated spikes.

A natural experiment created by the COVID lockdown reveals that pollution is rapidly reversible when emissions fall, but recovery trajectories differ sharply across cities. Delhi rebounds faster and overshoots baseline pollution more aggressively than peer cities, suggesting structural dispersion weaknesses. Seasonal analysis shows winter pollution compresses regionally, but Delhi uniquely fails to recover after peak events.

The findings support a retention-driven model of urban air inequality: pollution severity depends not only on production, but on how efficiently cities disperse accumulated pollutants. The project demonstrates how data storytelling can translate environmental systems into evidence-backed public narratives.

---

## Research Question

**Why does Delhi experience structurally worse air pollution than other major Indian cities, and how does its recovery differ after large emission shocks?**

---

## Hypotheses

- Delhi’s pollution is driven by atmospheric retention, not only emissions  
- Winter spikes are regional, but Delhi fails to normalize afterward  
- Lockdown emission cuts expose dispersion limits  
- Post-COVID recovery overshoots baseline faster in Delhi  

---

## Project Architecture

Raw AQI datasets (CPCB + OpenAQ)
│
▼
Data Cleaning & Validation (Pandas)
│
▼
Baseline Construction (2015–2019)
│
▼
Seasonal + COVID Natural Experiment Analysis
│
▼
Aggregation & Metrics
│
▼
Plotly Visualization Engine
│
▼
Narrative Data Story (HTML + CSS)
│
▼
Interactive Public Report (GitHub Pages)


This pipeline separates data engineering, analytical modeling, and narrative visualization into reproducible stages.

---

## Methodology

- Multi-source AQI dataset harmonization  
- Pre/post intervention baseline modeling  
- Seasonal wave decomposition  
- Relative recovery index construction  
- Hazard exposure measurement  
- Interactive visualization synthesis  

All transformations are reproducible via notebooks in `/analysis`.

---

## Key Findings

- Pollution inequality is structural, not episodic  
- Delhi accumulates pollutants faster than peer cities  
- Winter compression is regional, persistence is local  
- COVID proved pollution reversibility  
- Recovery patterns reveal atmospheric limits  
- Geography amplifies emissions impact  

**Delhi’s crisis is not only about production — it is about retention.**

---

## Deliverables

- Reproducible analytical notebooks  
- Clean aggregated datasets  
- Interactive Plotly visualizations  
- Narrative data story website  
- Research-style documentation  
- Evidence-backed conclusions  

---

## Run Locally

```bash
pip install -r requirements.txt
jupyter notebook
Plots → /plots
Story → index.html

Or view live:

👉 https://rtrgrid.github.io/DS_Blog_project/

Tools & Stack
Python

Pandas

Plotly

Jupyter

HTML/CSS

GitHub Pages

Data storytelling methodology

Portfolio Summary (Resume Version)
Data storytelling project analyzing structural air pollution inequality across Indian cities using multi-year AQI datasets. Built a reproducible analytical pipeline, modeled seasonal pollution behavior, and visualized post-COVID recovery dynamics. Produced an interactive narrative report translating environmental systems into policy-relevant insights.

Future Work
Integrate meteorological wind field modeling

Dispersion simulation by geography

Emissions source attribution

Predictive winter hazard modeling

Link AQI to health outcomes

References
CPCB · OpenAQ · Public AQI datasets
Storytelling with Data · Fundamentals of Data Visualization

