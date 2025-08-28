# Hi, I’m Clément Chevauchey

Power & electronics student focusing on **power systems analysis**, **measurement & instrumentation**, and **clean documentation**.  
I like turning messy engineering problems into reproducible, readable pipelines.

- 🔗 Academic Portfolio: **https://yoficlemy.github.io/academic-portfolio/**
- 📦 Portfolio repo: **https://github.com/YofiClemy/academic-portfolio**

---

## Some examples of project

- **MV Feeder Study (pandapower)** – baseline LF/SC (IEC 60909), OLTC probe, shunt cap sweep, targeted rebalancing, auto-ranking of scenarios.  
  _Next_: PV/BESS integration with **Volt-VAR & curtailment** sweeps to compare “network support via DER” vs “caps/taps”.  
  Repo path: `/power-studies-feeder`

- **Electronics & Measurements labs** – consistent report structure (`report.pdf`, `data/`, `figures/`, `code/`), uncertainty and error propagation.

- **Logic systems – Traffic Lights (Proteus)** – Moore FSM with clean timing divider, optional HDL/testbench notes.

---

## Selected projects

- **Power studies feeder**  
  _Outcome_: Ran LF/SC on the CIGRE MV feeder, enumerated actions (OLTC, shunt caps, rebalancing), snapshotted KPIs, auto-selected the lightest fix meeting planning limits (Vmin ≥ 0.95 pu, Vmax ≤ 1.05 pu, line/trafo ≤ 100%).  
  _Selected case_: `cap_1.0MVAr+rebalance_90pct` (1.0 MVAr at bus 11 + 10% load transfer on hottest LV feeder).  
  _Stack_: Python, **pandapower**, pandas, matplotlib, IEC 60909, lightweight scenario ranking.  
  ▶ Portfolio card + report on the site.

<h2 align="center">PlantWeb - CS50 Final Project</h2>
<p align="center">
  <a href="https://yoficlemy.github.io/Final-Project-CS50/" target="_blank" rel="noopener noreferrer">
    <img alt="Project Page"
         src="https://img.shields.io/badge/Page-Project-1f77b4?style=flat&labelColor=555">
  </a>
  <a href="https://final-project-cs50.onrender.com/" target="_blank" rel="noopener noreferrer">
    <img alt="Live Demo"
         src="https://img.shields.io/badge/Live-Demo-f97316?style=flat&labelColor=555">
  </a>
  <a href="https://github.com/YofiClemy/Final-Project-CS50/releases/latest" target="_blank" rel="noopener noreferrer">
    <img alt="Latest Release"
         src="https://img.shields.io/github/v/release/YofiClemy/Final-Project-CS50?display_name=tag&color=10b981&label=Release&style=flat&labelColor=555">
  </a>
</p>
Track your houseplants, store photos, and never miss a watering. Built with **Python**, **Flask** and **SQLite** for a CS50 final project.

- Add plants with either an uploaded image or a stock image from `static/stock/`
- Images are resized server-side to fast thumbnails; album images are **lazy-loaded** with fixed dimensions
- Due-date logic: next watering is computed from the last watering or the added date
- Auth (register/login) with hashed passwords and server-side sessions
- **CSRF protection** on all POST forms
- Optional **email** on user accounts (migrated automatically if missing)
- Clean Bootstrap UI with empty state and due-status badges

- **Repo:** https://github.com/YofiClemy/Final-Project-CS50  
- **Live demo:** https://final-project-cs50.onrender.com/  
- **Project page:** https://yoficlemy.github.io/Final-Project-CS50/


<h2 align="center">Electronics II (7 labs)</h2>
  Rectifiers, clippers, BJT single/cascade, op-amp labs validated against specs.  
  _Stack_: LTspice/Proteus, biasing & small-signal, gain/bandwidth, measurement planning.

<h2 align="center">Electrical Measurements (7 labs)</h2>
  Instrument class, R/Z, single/three-phase power (3A/3V, wattmeter/Aron), Type A/B uncertainty.  
  _Stack_: metrology, phasors/PF, Python analysis.

<h2 align="center">Logic systems — Traffic Lights (Proteus)</h2>
  Moore FSM + timing divider, debounced, deterministic phase timing. Optional HDL/testbench.

<h2 align="center">Thermo cycle studies</h2>
  Rankine (superheat vs no superheat; ideal vs real), and Otto/Diesel/Dual (η_th vs compression ratio).

---

## How I structure projects

Every project is **repeatable** and **browseable**:

```
project/
├─ report.pdf        # final report in english
├─ /es               # final report in spanish
├─ data/             # CSVs, raw/processed data
├─ figures/          # plots/diagrams used in the report
├─ code/             # scripts/notebooks
└─ README.md         # short context + how-to-run
```


---

## Toolbox

- **Power systems**: pandapower (LF, IEC 60909 SC), scenario design, Volt-VAR & curtailment concepts  
- **Electronics/Measurements**: LTspice/Proteus, DMM/oscilloscope workflows, Type A/B uncertainty  
- **Data & viz**: Python, pandas, matplotlib  
- **Docs & site**: Markdown, LaTeX snippets, Jekyll/Liquid

---

## Quick links

- 🌐 Portfolio site: https://yoficlemy.github.io/academic-portfolio/
- 📁 Portfolio repo:  https://github.com/YofiClemy/academic-portfolio
- 📌 Featured: power-studies-feeder (MV feeder LF/SC + remedial actions, plots & CSVs)

> I keep things simple: small, readable scripts; CSV in /data; plots in /figures; a short README;
