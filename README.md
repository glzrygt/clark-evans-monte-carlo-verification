# Clark-Evans Test Verification via Monte Carlo Simulation

This project is a spatial analysis study focused on verifying the theoretical foundations of the **Clark-Evans Test** using Python-based simulations.

## Project Overview
The study simulates **Complete Spatial Randomness (CSR)** in a unit square window to observe how the average nearest neighbor distance ($d_{min}$) behaves under different point densities ($N=10, 50, 100, 500$). 

### Key Features
* **Monte Carlo Simulation:** 1000 iterations for each density level to ensure statistical reliability.
* **Theoretical Verification:** Comparison of observed means and variances against Clark-Evans (1954) formulas.
* **Convergence Analysis:** Visualization of how spatial distributions converge to a Normal (Gaussian) distribution as $N$ increases (Central Limit Theorem).

## Tech Stack
* **Language:** Python
* **Libraries:** `pointpats`, `scipy.spatial (KDTree)`, `numpy`, `pandas`, `matplotlib`

## Results & Analysis
The simulation successfully validates the Clark-Evans model. As point density increases:
1. The **Observed Mean** aligns almost perfectly with the **Expected Mean**.
2. The **Variance** decreases significantly, reaching high precision ($10^{-7}$) at $N=500$.
3. Histograms show a clear convergence to the theoretical normal curve.

License & Rights
© 2026 Gülüzar Yiğit. All rights reserved. 
This project is prepared for GMT 454 Spatial Analysis course and serves as a professional portfolio piece. Direct copying or commercial use is not permitted.
