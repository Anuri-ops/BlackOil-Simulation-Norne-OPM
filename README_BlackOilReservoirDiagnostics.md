# 🛢️ Black Oil Reservoir Diagnostics – NORNE Field (Norway)

This project showcases a black-oil reservoir simulation using the publicly available **NORNE dataset** and the **OPM Flow + ResInsight** toolchain. The focus is on simulating real-field production, analyzing well behavior, and visualizing key reservoir performance metrics.

## 🎯 Objectives

- Perform black-oil simulation with the NORNE dataset using OPM Flow
- Visualize key performance indicators: production, pressure, water breakthrough
- Compare well performance to identify insights on sweep efficiency and recovery
- Explore diagnostic metrics such as water cut, GOR, and field-wide trends

## 🧰 Tools & Libraries

- [OPM Flow](https://opm-project.org/) – Reservoir simulator
- [ResInsight](https://resinsight.org/) – Post-processing and 3D visualization
- WSL (Ubuntu on Windows)
- Python (planned for extended analysis)

## 📦 Dataset

- **Source**: [OPM Data Repository – NORNE ATW2013](https://opm-project.org/?page_id=559)
- **Files used**:
  - `NORNE_ATW2013.DATA`
  - `EGRID`, `SMSPEC`, `UNRST` (for visualization in ResInsight)
- **Disclaimer**: All data is publicly provided by the OPM project and Equinor for research and academic purposes.

---

## 🔍 Key Visualizations

### ▶️ 1. Field Total Production

![Total Oil Production](visuals/total_oil_production.png)

**Interpretation**: Field oil production peaked around timestep XXX, followed by a steady decline. Injection support can be correlated with pressure stabilization over time.

---

### ▶️ 2. Grid Structure

![Grid Structure](visuals/grid_structure.png)

**Interpretation**: Active cells are distributed in fault-bounded compartments. The vertical layering captures key zones for oil saturation and fluid flow.

---

### ▶️ 3. Well Comparison: E-4AH vs B-4BH

![Well Summary Comparison](visuals/well_summary_comparison.png)

**Interpretation**:  
- **E-4AH**: Stable BHP and late water breakthrough indicate a productive zone.  
- **B-4BH**: Earlier WWCT increase, steeper decline in oil rate. Suggests faster sweep or coning issues.

---

### ▶️ 4. GOR & Water Cut Evolution

![Water Cut GOR](visuals/wc_gor.png)

**Interpretation**: GOR trends upward for B-4BH post breakthrough, while water cut sharply rises. This indicates gas coning or late-stage water dominance.

---

### ▶️ 5. Injection Diagnostics

![Field Water Injection Total](visuals/fwit.png)

**Interpretation**: Injection volumes correlate with production plateaus and reservoir pressure control during the mid-phase of production.

---

## 🧠 Key Learnings

- Diagnostics from well summaries provide early warning signs of water/gas breakthrough.
- Visual analytics using ResInsight enables well-to-field scale performance review.
- Understanding the reservoir compartmentalization helps in explaining differences between well performance.

---

## 👤 Author

**Anuri Nwadinma Chiamaka Nwagbara**  
MSc Geological Engineering | BSc & PGD Chemical Engineering  
Location: Norway  
GitHub: [@anurinwagbara](https://github.com/anurinwagbara)

---

## 📜 License

This repository is for educational and non-commercial use only. NORNE dataset © Equinor & OPM Project.  
