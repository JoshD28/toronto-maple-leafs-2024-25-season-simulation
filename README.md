# NHL Season Outcome Simulation

This repository contains a **Poisson-based win probability model**
and **Monte Carlo simulation** to estimate season-level outcomes for an NHL team
(Toronto Maple Leafs, 2024–25 season).

It simulated season outcomes to actual results to evaluate model behavior
and uncertainty.

##Goals
1. **Estimate game-level win probabilities** using a Poisson model based on goals for and against.
2. **Simulate full NHL seasons** using Monte Carlo methods.
3. **Analyze the distributions of total wins and points** across simulated seasons.
4. **Compare expected and simulated outcomes** to actual season results.

## Data
- **Source:** NHL game-level data (team goals for and goals against)
- **Unit of analysis:** Individual games
- **Key variables:**  
  - Goals For (GF)  
  - Goals Against (GA)  
  - Win indicator (derived)  
  - Model-based win probability (`p_win`)

## Methods
- **Model:** Poisson-based estimation of win probability
- **Simulation:** Monte Carlo simulation of full-season outcomes
- **Outputs analyzed:**  
  - Distribution of total wins  
  - Distribution of total points  
- **Visualization:**  
  - Histograms of simulated outcomes with overlays for expected and actual values

## Outputs
- Simulated distributions of season wins and points
- Expected season outcomes from the probabilistic model
- Visual comparison of simulated results against actual season performance

## How to Run
1. Clone or download this repository.
2. Ensure the dataset is located in the `data/` directory.
3. Open and run:
   - `Toronto_Maple_Leafs_2024_25_Poisson_Simulation.ipynb`

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn

## Notes
This model displays **season-level uncertainty**, not individual game prediction accuracy.
Simulated results represent probabilistic expectations rather than deterministic forecasts.
