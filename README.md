# Why Some Indian Cities Breathe Worse Air Than Others

A data storytelling project exploring structural air pollution differences across Indian cities, with Delhi as a central case study.

This project turns messy air quality data into a clear narrative:  
a question → evidence → interpretation → conclusion.

---

## Research Question

Why does Delhi experience persistently worse air pollution than other major Indian cities — and does it recover differently after large emission shocks?

---

## Hypotheses

- **H1:** Delhi’s pollution problem is driven by retention, not just emissions.
- **H2:** Winter pollution spikes are regional, but Delhi fails to recover.
- **H3:** Temporary emission drops (COVID lockdown) reveal dispersion weaknesses.
- **H4:** Post-COVID recovery overshoots baseline faster in Delhi than in peer cities.

---

## Dataset Overview

This project combines multiple public air quality datasets:

- City-level AQI records (2015–2024)
- Pre-COVID baseline data (2015–2019)
- COVID lockdown period data (March–May 2020)
- Post-COVID recovery data (2020–2025)
- PM2.5 monitoring coverage across Indian states

Key fields:

- Date / Datetime
- City
- AQI
- PM2.5 and pollutant breakdown
- Geographic coordinates (for mapping)

All datasets were cleaned, validated, and aggregated into comparable monthly and yearly summaries.

---

## Analysis Workflow

1. **Data Cleaning**
   - Standardized timestamps
   - Removed invalid entries
   - Normalized AQI scales
   - Filtered out incomplete city records

2. **Baseline Construction**
   - Built pre-COVID city baselines (2015–2019)
   - Calculated relative recovery ratios

3. **Seasonal Analysis**
   - Winter spike detection
   - Month-by-month AQI patterns

4. **COVID Natural Experiment**
   - Compared lockdown vs baseline
   - Measured recovery trajectories

5. **Visualization**
   - Interactive city comparisons
   - Choropleth maps
   - Recovery wave plots
   - Hazard distribution charts

---

## Key Findings

- Delhi consistently ranks among the most structurally polluted cities.
- Winter pollution spikes repeat with high predictability.
- COVID lockdown proved pollution is reversible — temporarily.
- Recovery after lockdown was unequal.
- Delhi rebounds faster and accumulates pollution more aggressively.
- Geography + atmospheric retention amplify emissions impact.

Delhi’s air crisis is not only about how much pollution is produced —  
it is about how much is allowed to remain.

---

## Project Deliverables

- Reproducible notebooks for cleaning and aggregation
- Interactive Plotly visualizations
- Narrative HTML blog
- Structured research framing
- Evidence-backed conclusions

---

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

Open notebooks in `/analysis` and run in order.

Generated plots are saved to:

```
/plots
```

The final story is in:

```
index.html
```

---

## Tools Used

- Python
- Pandas
- Plotly
- Jupyter
- HTML/CSS
- GitHub Pages

---

## Next Experiments

If given more time:

- Add meteorological wind data
- Model dispersion vs geography
- Compare industrial vs traffic emissions
- Predict winter hazard windows
- Add hospital respiratory data

---

## References

- CPCB Air Quality Data
- OpenAQ
- Public AQI monitoring datasets
- Storytelling with Data principles
- Fundamentals of Data Visualization

---

## Author

Data storytelling project for academic submission.

