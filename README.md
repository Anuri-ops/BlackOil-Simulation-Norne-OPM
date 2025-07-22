# Black-Oil Reservoir Simulation – NORNE Field (Norway)

## Introduction
This project uses the open NORNE dataset (from Equinor/NTNU) to simulate oil and gas production in a full-field, offshore Norwegian reservoir. The simulation was conducted using **OPM Flow**, and post-processing was performed in **ResInsight** for 3D grid views and production trend analysis.

## 🧪 Simulation Highlights
- 352 timesteps covering production years from 1996 to 2007  
- Production visualized using `SMSPEC` time-series plots (e.g., Oil Production Total)  
- Reservoir properties (SOIL, permeability, pressure) explored in 3D grid views  
- Well activity tracked through ResInsight's well log summaries

## 🖥️ Tools Used
- OPM Flow (simulator)
- ResInsight (visualization)
- WSL2 (Ubuntu 20.04)
- Windows 10

## 📂 Files Used
- `NORNE_ATW2013.DATA` — Eclipse input file
- `NORNE_ATW2013.UNRST` — Dynamic results
- `NORNE_ATW2013.EGRID` — Static grid
- `NORNE_ATW2013.SMSPEC` — Summary output
