# Black-Oil Reservoir Simulation – NORNE Field (Norway)

##  Project Overview
This project uses the publicly available NORNE dataset to simulate historical oil and gas production in a real offshore Norwegian reservoir. The simulation was conducted using **OPM Flow**, and post-processing was performed in **ResInsight** using static grid and summary data to analyze production trends and grid behavior.

##  Simulation Details
- 352 timesteps covering historical production from 1996 to 2007  
- Summary results include oil production total (SMSPEC)  
- 3D grid structure visualized using EGRID  
- Simulation executed with OPM Flow on WSL (Ubuntu on Windows)

##  Tools Used
- OPM Flow (simulator)
- ResInsight (visualization)
- WSL2 (Ubuntu 20.04)
- Windows 10

##  Files Used
- `NORNE_ATW2013.DATA` — Eclipse input file (not included)
- `NORNE_ATW2013.EGRID` — Static grid structure
- `NORNE_ATW2013.SMSPEC` — Summary output (production trends)

## Visualizations

### Oil Production Total Plot
![Oil Production](screenshots/production_plot.png)

### Grid Structure (SOIL)
![Grid View](screenshots/grid_view_soil.png)

### Well Summary View
![Well Summary](screenshots/well_summary.png)

##  Notes
This project does not include `.UNRST` dynamic files; only EGRID and SMSPEC were visualized. The NORNE dataset is available for academic use from Equinor and NTNU:  
[https://www.ntnu.edu/ie/norne](https://www.ntnu.edu/ie/norne)


