# Hotel Guest Flow Simulation

## Overview
This project implements an **event-driven simulation** of hotel guest flow, modeling the full customer journey from **check-in** through in-hotel activities (e.g., pool, bar, breakfast) to **final checkout**.

The simulation is based on **probabilistic modeling and statistical analysis**, enabling realistic representation of service times and guest behavior.

> Developed as part of a course on **simulation, probabilistic modeling, and event-driven programming**, this project combines statistical inference with discrete-event system design. January 2024.

---

## Key Features
- Event-driven simulation of guest flow  
- Modeling of multiple hotel services:
  - Check-in  
  - Pool  
  - Bar  
  - Breakfast  
  - Check-out  
- Statistical analysis of real data  
- Custom sampling algorithms for activity durations  
- Visualization of distributions and results  

---

## Statistical Modeling

### Service Time Analysis
- Check-in and check-out times are modeled using the **Exponential Distribution**
- Parameters are estimated using **Maximum Likelihood Estimation (MLE)**

### Validation
- Goodness-of-fit tested using the **Kolmogorov–Smirnov (KS) test**
- Results support the assumption of exponential service times at a 10% significance level

---

## Sampling & Simulation

The simulation includes custom sampling methods for different activities:

- **Exponential sampling** for arrivals and service times  
- **Custom distributions** for activities (e.g., pool time)  
- Inverse transform sampling for non-standard distributions  

---

## Simulation Logic

The system simulates:
- Guest arrivals  
- Queueing and service processes  
- Movement between hotel facilities  
- Resource usage and timing  

---

## Outputs
- Distribution visualizations  
- Q-Q plots and statistical diagnostics  
- Simulation behavior insights  
- Service time analysis  

---

## How to Run

1. Download the notebook file [(`hotel-guest-flow-simulation.ipynb`)](\hotel-guest-flow-simulation.ipynb)
2. Open it using:
   - Google Colab  
   - Jupyter Notebook  
   - VS Code
   - Code editor of your choice

3. Upload the required Excel [datasets](\Check_INOUT_Samples_Minutes) when prompted  
4. Run the cells sequentially  

---

## Packages & Libraries
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- SciPy  

---

## Contributors
- [Leah Rosen](https://github.com/leahrosen21)
- [Lilach Yosef](https://github.com/LilachYosef)
- [Ofri Ratinsky](https://github.com/OfriRatinsky)
