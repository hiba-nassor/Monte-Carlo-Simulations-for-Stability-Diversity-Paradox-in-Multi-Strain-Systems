# Monte Carlo Simulations for Stability-Diversity Paradox in Multi-Strain Systems

This repository contains the code developed during a research internship at the Denis Poisson Institute in Tours, France. The research focused on the theoretical study and numerical and statistical exploration of the "stability-diversity" paradox. The study investigates the relationship between species diversity and stability in ecological systems, using Monte Carlo simulations to explore various states in multi-strain systems.

## Repository Structure

This repository is organized into three main Jupyter Notebooks, each corresponding to different types of steady states in the system:

1. **Steady States**:
   - **File:** `steady_states.ipynb`
   - **Description:** This notebook simulates the average number of steady states in the system. It computes the probability of having steady states with \(k\) strains and their average number in a pool of \(N\) strains, considering \(\lambda_i^j\) as independent and identically distributed (iid) variables and introducing the impact of \(\mu\).

2. **Saturated Steady States**:
   - **File:** `saturated_steady_states.ipynb`
   - **Description:** This notebook simulates the average number of saturated states in the system. It computes the probability of having saturated states with \(k\) strains and their average number in a pool of \(N\) strains, considering \(\lambda_i^j\) as independent and identically distributed (iid) variables and introducing the impact of \(\mu\).

3. **Stable Steady States**:
   - **File:** `stable_steady_states.ipynb`
   - **Description:** This notebook simulates the average number of stable states in the system. It also calculates the probability of stable states with \(k\) strains and their average number in a pool of \(N\) strains, considering \(\lambda_i^j\) as independent and identically distributed (iid) variables and introducing the impact of \(\mu\).

## Research Context

This work is based on the article by Gjini E., Madec S. titled *"The ratio of single to co-colonization is key to complexity in interacting systems with multiple strains."* published in *Ecology and Evolution* in 2021. The study delves into how single and co-colonization ratios affect the complexity of interactions within multi-strain systems.

## How to Use the Code

To run the simulations, you need to have Python installed on your system, along with the necessary scientific libraries (e.g., NumPy, SciPy, Matplotlib). You can view and run the Jupyter Notebooks directly in the repository.

