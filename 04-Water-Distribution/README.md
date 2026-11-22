# Water Distribution Network Design: West Saadat Abad, Tehran

**Type:** Team Academic Project (3 students)  
**Course:** Water and Wastewater Engineering, Amirkabir University of Technology (AUT), 2024–2025  
**Software:** EPANET, Autodesk Civil 3D, AutoCAD, Microsoft Excel, Python  
**Design Reference:** Iranian Publication No. 117-3 (Urban Water Supply Design Criteria)

## Project Overview

Design and hydraulic analysis of an urban water distribution network for the western Saadat Abad district of Tehran, Iran.

The study area covers approximately 1.9 km² and had an estimated population of 23,157 in 2021. The project involved terrain modeling, network layout, population and water-demand estimation, hydraulic design, pump selection, storage calculations, and extended-period simulation using EPANET.

## Design Basis

| Parameter | Design Value |
|---|---|
| Study area | West Saadat Abad, Tehran (approx. 1.9 km²) |
| Initial population | 23,157 (2021) |
| Design period | 25 years |
| Population forecasting method | Curvilinear method |
| Annual population growth rate | 1.24% |
| Domestic water consumption | 110 L/person/day |
| Water loss allowance | 15% |
| Maximum daily demand factor (C1) | 1.4 |
| Maximum hourly demand factor (C2) | 1.5 |
| Pipe material | PVC |
| Main loop diameter | 700 mm |
| Simulation period | 24 hours |
| Simulation time step | 1 hour |

## Hydraulic Design Criteria

**Pressure**
- Target pressure: approximately 30 m at most nodes.
- Minimum service pressure at ground-floor level: 14 m, plus 4 m for each additional floor.
- Maximum pressure: approximately 50–70 m.
- Pressure zoning and pressure-breaker valves (PBVs) were considered to manage elevation-related pressure differences.

**Flow Velocity**
- Minimum: 0.3 m/s.
- Maximum under normal operation: 2.0 m/s.
- Maximum under fire flow: 2.5 m/s.

**Pipe Diameter**
- Minimum diameter: 60 mm.
- Minimum diameter for pipes equipped with fire hydrants: 110 mm.

**Fire Protection**
- Hydrant spacing: 100 m in important areas, 200 m in residential areas, and up to 300 m in lower-value areas, subject to the specified pipe-diameter requirements.

## Scope of Work

- **Terrain Modeling:** Extraction of elevation data from AutoCAD drawings and development of a ground surface model in Civil 3D.
- **Network Layout:** Placement of junctions at street intersections and routing of pipes along the street network, using looped arrangements where feasible.
- **Data Extraction:** Transfer of junction coordinates and pipe geometry from Civil 3D and AutoCAD into Excel for model preparation.
- **Service-Area Allocation:** Delineation of junction service areas using perpendicular bisectors and Voronoi polygons generated with Python.
- **Land-Use Analysis:** Classification of residential, educational, hospital, green-space, commercial, and other land uses for water-demand allocation.
- **Population Forecasting and Demand Estimation:** Calculation of domestic, institutional, green-space, and water-loss demands and their allocation to individual junctions.
- **Storage Design:** Development of hourly demand patterns and calculation of balancing storage requirements.
- **Hydraulic Modeling:** Development of the EPANET network model, including junctions, pipes, reservoirs, pumps, and valves.
- **Pump Selection:** Selection based on peak flow and required head, using technical data from the Pumpiran catalogue.
- **Extended-Period Simulation:** Evaluation of pressure, hydraulic head, pipe flow, velocity, and friction losses over a 24-hour simulation period.
- **Water Quality Analysis:** Modeling of residual chlorine concentration and its bulk and wall decay throughout the network.

## Selected Design Results

| Parameter | Result |
|---|---:|
| Number of junctions | 241 |
| Average daily demand | 12,973.4 m³/day |
| Maximum daily demand | 19,460.16 m³/day |
| Pump design flow | 810.84 m³/h |
| Required pump head | 25.5 m |
| Junction elevation range | 1,521.71–1,630.50 m |
| Total elevation difference | 108.79 m |
| Main loop pipe diameter | 700 mm |

## Water Quality Analysis

Residual chlorine was modeled in EPANET to examine chlorine decay throughout the distribution network.

- Continuous chlorine dosing at the tank: 1.0 mg/L.
- Bulk reaction coefficient: −0.85.
- Wall reaction coefficient: −0.015.

## Design Limitation

Despite several pipe-diameter adjustments, the maximum allowable flow velocity could not be achieved at some locations in the network. This limitation was identified during the hydraulic analysis.

## Team Contribution

This project was completed collaboratively by a team of three students. The major project activities were carried out jointly through discussion and shared work, including terrain modeling, network drafting, data extraction, service-area allocation, population forecasting, demand calculations, EPANET modeling, pump and storage design, hydraulic simulation, water quality analysis, and report preparation.

## Project Files

- [Project Brief](project-brief/)
- [Full Group Report (Persian)](report/)
- [EPANET Model and Software Files](software-files/)
- [Design Outputs](design-outputs/)
- [Model Images](images/)
