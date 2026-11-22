# HEC-HMS Project: Rainfall-Runoff Modeling

**Type:** Individual Academic Project  
**Course:** Engineering Hydrology, Amirkabir University of Technology (AUT), August 2025  
**Software:** HEC-HMS

## Overview

Development of a rainfall-runoff model for a hypothetical watershed with a total area of approximately 1,029 km².

The model was built from a 15-minute rainfall hyetograph recorded on 1 April 2004 and observed discharge hydrographs at two outlets. The project covered watershed modeling, rainfall-runoff simulation, manual calibration, and parameter sensitivity analysis.

## Model Setup

| Element | Method / Description |
|---|---|
| Watershed | 4 sub-basins (461, 127, 310, and 131 km²), 3 junctions, and 2 reaches |
| Rainfall | Two specified hyetographs at 15-minute intervals |
| Loss method | Initial and constant rate, including percentage of impervious area |
| Transform method | SCS unit hydrograph (standard PRF 484) |
| Routing method | Muskingum (K and X for each reach) |
| Observed data | Hourly discharge at Junction 1 and Junction 3 |

## Model Calibration

Calibration was performed progressively, starting at the upstream outlet (Junction 1) and continuing downstream to Junction 3. At each stage, selected parameter groups were adjusted (impervious percentage, initial loss, constant loss rate, and Muskingum K), and the resulting peak discharge, runoff volume, and goodness of fit were compared with the observed hydrographs.

### Junction 1

| Calibration stage | Peak (m³/s) | Volume (mm) | Nash-Sutcliffe | Percent bias |
|---|---:|---:|---:|---:|
| Observed | 228.7 | 4.50 | n/a | n/a |
| Initial parameters | 530.4 | 7.78 | −0.838 | 67.7% |
| After three adjustment rounds | 294.3 | 5.02 | 0.917 | 8.1% |
| Final calibrated model | 235.9 | 4.93 | 0.994 | 6.3% |

### Junction 3

| Calibration stage | Peak (m³/s) | Volume (mm) | Nash-Sutcliffe | Percent bias |
|---|---:|---:|---:|---:|
| Observed | 263.1 | 5.20 | n/a | n/a |
| Initial parameters | 269.0 | 7.28 | 0.831 | 39.5% |
| Final calibrated model | 270.6 | 7.08 | 0.886 | 35.7% |

At Junction 3, the calibrated model reproduces the observed peak and its timing (07:00), but the total runoff volume remains overestimated (7.08 mm against 5.20 mm observed).

## Sensitivity Analysis

A sensitivity analysis was conducted on seven parameters:

1. Percentage of impervious area
2. Muskingum K
3. Muskingum X
4. Number of subreaches
5. SCS lag time
6. Initial loss
7. Constant loss rate

Their effects were evaluated on peak discharge, runoff volume, rising and falling limbs, time to peak, and base time.

The percentage of impervious area had the strongest influence on peak discharge: varying it by ±20% moved the Junction 1 peak between approximately 195 and 283 m³/s. SCS lag time had a small effect, and the other parameters did not change the Junction 1 peak noticeably within the tested range.

## My Contribution

Completed individually: watershed modeling, rainfall-runoff simulation, manual calibration, sensitivity analysis, and interpretation of results.

## Project Files

- [Project Brief](project-brief/)
- [Report Summary (English) and Full Report (Persian)](report/)
- [HEC-HMS Model Files](software-files/)
- [Simulation Results and Outputs](design-outputs/)
- [Model Images and Hydrographs](images/)
