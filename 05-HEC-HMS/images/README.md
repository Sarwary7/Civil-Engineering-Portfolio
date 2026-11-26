# HEC-HMS Project Images

This folder contains selected visual materials from the HEC-HMS Rainfall-Runoff Modeling academic project, illustrating the basin model configuration, calibration process, simulation results, model performance, and parameter sensitivity analysis.

## 1. Basin Model Layout

The HEC-HMS basin model consists of four subbasins, three junctions, and two routing reaches.

![Basin Model Layout](01-Basin-Model.png)

## 2. Junction 1 – Before Calibration

Comparison of observed and simulated discharge hydrographs before model calibration.

![Before Calibration](02-Junction-1-Before-Calibration.png)

## 3. Junction 1 – After Calibration

Comparison of observed and simulated discharge hydrographs following model calibration, showing improved agreement.

![After Calibration](03-Junction-1-After-Calibration.png)

## 4. Junction 3 – Final Hydrograph

Final simulated and observed discharge hydrographs at Junction 3, illustrating the downstream model response.

![Final Hydrograph](04-Junction-3-Final-Hydrograph.png)

## 5. Junction 1 – Calibration Statistics

Selected model performance results:

- Simulated peak discharge: 235.9 m³/s
- Observed peak discharge: 228.7 m³/s
- Nash–Sutcliffe Efficiency (NSE): 0.994
- Percent Bias (PBIAS): 6.29%

![Junction 1 Statistics](05-Junction-1-Calibration-Statistics.png)

## 6. Junction 3 – Calibration Statistics

Selected model performance results:

- Simulated peak discharge: 271.7 m³/s
- Observed peak discharge: 263.1 m³/s
- Nash–Sutcliffe Efficiency (NSE): 0.888
- Percent Bias (PBIAS): 35.67%

The model reproduced the observed peak discharge reasonably well, although the volume bias remained relatively high.

![Junction 3 Statistics](06-Junction-3-Calibration-Statistics.png.png)

## 7. Sensitivity Analysis

Sensitivity analysis of peak discharge at Junction 1 for parameter variations ranging from −20% to +20%.

- Impervious area showed the greatest sensitivity.
- Increasing lag time reduced peak discharge.
- K, X, subreaches, initial loss, and constant loss rate showed no discernible change in peak discharge within the tested range.

The curves for parameters with identical results overlap in the graph.

![Sensitivity Analysis](sensitivity-analysis-junction-1.png)

---

These images document the hydrological modeling, calibration, performance evaluation, and sensitivity analysis conducted during the academic project.
