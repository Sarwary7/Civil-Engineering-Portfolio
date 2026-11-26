# HEC-HMS Project Reports

This folder contains the technical documentation prepared for the HEC-HMS Rainfall-Runoff Modeling project.

**Project Type:** Individual Academic Project  
**Course:** Engineering Hydrology  
**University:** Amirkabir University of Technology (AUT)  
**Date:** August 2025  
**Software:** HEC-HMS

## Available Documents

### 1. English Report Summary

A concise English-language summary of the original academic report, prepared for international readers.

The summary covers:

- Watershed model configuration.
- Rainfall-runoff modeling methods.
- Manual calibration of Junction 1 and Junction 3.
- Comparison of observed and simulated discharge.
- Model performance evaluation.
- Sensitivity analysis of seven hydrological parameters.
- Key findings and model limitations.

[View English Report Summary (PDF)](HEC-HMS-Report-Summary.pdf)

### 2. Full Persian Technical Report

The original academic report containing detailed documentation of the hydrological modeling process.

The report includes:

- Initial modeling assumptions and input data.
- Watershed configuration and parameter selection.
- Initial and Constant loss method.
- SCS Unit Hydrograph transformation method.
- Muskingum channel routing.
- Step-by-step manual calibration.
- Observed and simulated hydrographs.
- Sensitivity analysis.
- Detailed simulation tables and graphical outputs.

[View Full Persian Technical Report (PDF)](HEC-HMS-Full-Report-Persian.pdf)

## Final Model Performance

| Performance Indicator | Junction 1 | Junction 3 |
|---|---:|---:|
| Observed Peak Discharge (m³/s) | 228.7 | 263.1 |
| Simulated Peak Discharge (m³/s) | 235.9 | 271.7 |
| Relative Peak Discharge Error | 3.15% | 3.27% |
| Initial NSE | -0.838 | 0.831 |
| Final NSE | 0.994 | 0.888 |
| Observed Runoff Depth (mm) | 4.50 | 5.20 |
| Simulated Runoff Depth (mm) | 4.93 | 7.08 |
| Reported Percent Bias | 6.29% | 35.67% |

## Key Findings

- Manual calibration substantially improved model performance at Junction 1.
- The final simulation reproduced the observed peak timing at both monitored junctions.
- Impervious area percentage was the most influential parameter affecting peak discharge at Junction 1 within the tested range.
- SCS lag time showed a smaller inverse effect on peak discharge.
- Runoff volume remained overestimated at Junction 3, indicating scope for further calibration.

## Model Limitations

The documented calibration is based on a single rainfall event. Independent validation using additional rainfall-runoff events would be required to assess model performance under different hydrological conditions.

## Related Project Materials

- [Project Brief](../project-brief/)
- [Simulation Results and Design Outputs](../design-outputs/)
- [Project Images](../images/)
- [HEC-HMS Model Files](../software-files/)
