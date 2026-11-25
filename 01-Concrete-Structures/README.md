
# Reinforced Concrete Structures Project

**Structural Analysis and Design of a 12-Level Reinforced Concrete Residential Building**

![3D ETABS Structural Model](images/etabs-3d-model.png)

*Figure 1. Three-dimensional ETABS structural model of the reinforced concrete residential building.*

---

| Project Information | Details |
|---|---|
| Project Type | Team Academic Project (3 Students) |
| Course | Reinforced Concrete Structures |
| Institution | Amirkabir University of Technology (AUT) – Tehran Polytechnic |
| Academic Year | 2024–2025 |
| Location | Tehran, Iran |
| Software | ETABS, SAFE |
| Retained Model Versions | ETABS 22.7.0, SAFE 22.7.0 |
| Design Codes | Iranian National Building Code Parts 6 and 9; Iranian Standard No. 2800 |

### Quick Access

- [Academic Project Brief (PDF)](project-brief/Concrete-Project-Brief.pdf)
- [Original Technical Report](report/)
- [ETABS and SAFE Models](software-files/)
- [Project Images and Visualizations](images/)

---

## 1. Project Overview

This academic project involved the structural analysis and design of a 12-level reinforced concrete residential building in Tehran, Iran.

The building consists of one basement parking level, one ground-floor parking level, and ten residential floors, with a total floor area of approximately 4,452 m².

The selected lateral load-resisting system consists of intermediate moment-resisting frames combined with intermediate reinforced concrete shear walls. Alternative structural configurations were evaluated with respect to lateral stiffness and inter-storey drift control.

The project integrates manual engineering calculations, computational structural modeling, seismic analysis, reinforced concrete design, foundation analysis, and structural material quantity estimation.

---

## 2. Building Specifications and Design Criteria

### Building Specifications

| Parameter | Specification |
|---|---|
| Building Occupancy | Residential |
| Number of Levels | 12 |
| Basement Parking Levels | 1 |
| Ground-Floor Parking Levels | 1 |
| Residential Floors | 10 |
| Typical Floor Area | 371 m² |
| Total Floor Area | 4,452 m² |
| Structural Material | Reinforced Concrete |
| Lateral Load-Resisting System | Intermediate Moment Frames and Intermediate Shear Walls |
| Floor System | Two-Way Waffle Slab |
| Foundation System | Mat Foundation |
| Soil Classification | Type I |
| Allowable Soil Bearing Capacity | 370 kPa |
| Required Fire Resistance | 90 minutes |

### Material Properties

| Material Property | Value |
|---|---:|
| Concrete Compressive Strength (f'c) | 37 MPa |
| Reinforcement Yield Strength (fy) | 400 MPa |
| Concrete Elastic Modulus | 32,694.8 MPa |
| Steel Elastic Modulus | 200,000 MPa |

### Design Codes and Standards

- Iranian National Building Code, Part 6 – Loads on Buildings.
- Iranian National Building Code, Part 9 – Design and Construction of Reinforced Concrete Buildings.
- Iranian Standard No. 2800 – Seismic Design of Buildings.

[View Academic Project Brief (PDF)](project-brief/Concrete-Project-Brief.pdf)

---

## 3. Engineering Methodology

The project was developed through an integrated structural engineering workflow combining analytical calculations, numerical modeling, and code-based design.

### Structural System Selection and Preliminary Design

- Review of architectural plans and project requirements.
- Evaluation of alternative structural systems.
- Preliminary sizing of beams and columns.
- Selection and arrangement of shear walls.
- Consideration of lateral stiffness and storey drift.
- Evaluation of fire-resistance requirements.
- Selection of a two-way waffle slab floor system.

### Structural Loading

- Structural and non-structural dead loads.
- Residential, parking, and roof live loads.
- Snow loads and snow accumulation.
- Wind loads.
- Elevator loads.
- Seismic load calculations.
- Effective seismic weight determination.
- Development of structural load combinations.

### Engineering Workflow

1. Architectural review and structural system selection.
2. Preliminary member sizing.
3. Manual load calculations.
4. Three-dimensional structural modeling.
5. Structural and seismic analysis.
6. Reinforced concrete member and slab design.
7. Foundation analysis and design.
8. Durability and serviceability assessments.
9. Structural material quantity estimation.
10. Technical documentation and interpretation of results.

[View Detailed Engineering Report](report/)

---

## 4. ETABS Structural Modeling and Seismic Analysis

A three-dimensional computational model was developed in ETABS to evaluate the structural response of the building under gravity and seismic loading.

### Modeling Procedure

- Definition of structural geometry and storey levels.
- Assignment of material and section properties.
- Modeling of beams, columns, slabs, and shear walls.
- Assignment of cracked-section stiffness modifiers.
- Shear wall meshing.
- Definition of diaphragm behavior.
- Assignment of gravity and seismic loads.
- Definition of mass sources and load combinations.
- Extraction of structural response and internal member forces.

### Three-Dimensional Beam and Column Model

![ETABS Beam and Column Model](images/etabs-beam-column-model.png)

*Figure 2. Three-dimensional ETABS model illustrating the reinforced concrete beam and column framing system.*

### Typical Structural Floor Plan

![Typical Structural Floor Plan](images/structural-floor-plan.png)

*Figure 3. Structural floor plan showing beam section assignments, column locations, shear wall positions, slab openings, and structural grid dimensions.*

### Structural and Seismic Assessments

- Modal analysis and natural period evaluation.
- Modal mass participation assessment.
- Structural displacement evaluation.
- Inter-storey drift assessment.
- Torsional irregularity assessment.
- Overturning stability assessment.
- Interpretation of structural internal forces.

Manual engineering calculations were integrated with computational analysis to evaluate structural behavior and support design decisions.

[Access ETABS and SAFE Software Files](software-files/)

---

## 5. Reinforced Concrete Member and Waffle Slab Design

The design of reinforced concrete members combined analytical engineering calculations with internal forces and design outputs obtained from ETABS.

### Beam Design

- Flexural strength calculations.
- Shear and torsional design.
- Longitudinal reinforcement determination.
- Transverse reinforcement and stirrup calculations.
- Reinforcement arrangement and member classification.

### Column Design

- Axial load and bending moment interaction.
- Longitudinal reinforcement calculations.
- Shear resistance assessment.
- Transverse reinforcement calculations.
- Column section and reinforcement classification.

### Two-Way Waffle Slab Design

- Definition of slab geometry and section properties.
- Finite element meshing.
- Definition of design strips.
- Evaluation of bending moments and internal forces.
- Determination of reinforcement requirements.

### Durability and Serviceability

- Concrete cover requirements.
- Reinforcement detailing considerations.
- Crack control requirements.
- Structural deformation considerations.
- Durability and serviceability provisions.
- Fire-resistance considerations.

[View Detailed Member and Slab Design Calculations](report/)

---

## 6. Mat Foundation Analysis and Design in SAFE

The foundation system was selected based on preliminary bearing area calculations using column reactions obtained from the ETABS structural model.

The estimated total area required for isolated footings was approximately 300.51 m², representing about 81% of the building footprint. Based on this preliminary assessment, a mat foundation was selected for the academic design.

### Foundation Selection

| Parameter | Reported Value |
|---|---:|
| Building Footprint | 371 m² |
| Estimated Required Isolated Footing Area | 300.51 m² |
| Required Footing Area / Building Footprint | Approximately 81% |
| Selected Foundation System | Mat Foundation |
| Preliminary Foundation Thickness | 1,500 mm |

### Three-Dimensional Foundation Model

![SAFE Mat Foundation Model](images/safe-foundation-model.png)

*Figure 4. Three-dimensional SAFE model illustrating the mat foundation geometry, foundation thickness, and reinforced concrete shear wall locations.*

### SAFE Modeling and Design

- Application of structural reactions.
- Definition of foundation geometry.
- Definition of soil subgrade properties.
- Finite element meshing.
- Definition of foundation design strips.
- Soil bearing pressure assessment.
- Punching shear assessment.
- One-way shear assessment.
- Flexural design and reinforcement calculations.
- Interpretation of foundation analysis results.

[Access Foundation Software Files](software-files/)

---

## 7. Key Engineering Results

The following values summarize selected results reported in the original academic project documentation.

### Modal Analysis Results

| Parameter | Reported Result |
|---|---:|
| Fundamental Period – X Direction | 1.950 s |
| Fundamental Period – Y Direction | 1.785 s |
| Number of Vibration Modes | 24 |
| Cumulative Modal Mass Participation – X | 98.70% |
| Cumulative Modal Mass Participation – Y | 97.25% |

The reported cumulative modal mass participation exceeded 90% in both principal horizontal directions.

The original technical report also documents seismic loading, inter-storey drift, torsional irregularity, and overturning stability assessments.

### Engineering Interpretation

Modal analysis was used to evaluate the dynamic characteristics of the building and the contribution of vibration modes to its seismic response.

Preliminary bearing area calculations supported the selection of a mat foundation, while structural analysis outputs informed reinforced concrete member design and reinforcement requirements.

### Documentation and Model Verification Note

The numerical values presented above are taken from the original academic report. A subsequent review of the retained ETABS model revealed differences in modal periods and mass participation results.

These differences have not yet been reconciled. Accordingly, the reported numerical results and retained computational models should not be interpreted as a fully reconciled or independently validated dataset.

[View Original Analysis Results and Calculations](report/)

---

## 8. Structural Material Quantity Estimation

Structural material quantities were estimated following the design of the main reinforced concrete components.

### Reported Aggregate Material Quantities

| Material | Reported Quantity |
|---|---:|
| Total Concrete Volume | 1,512.81 m³ |
| Total Reinforcement | 239.33 t |
| Total Floor Area | 4,452 m² |

### Material Consumption Indicators

| Indicator | Calculated Value |
|---|---:|
| Concrete Volume per Floor Area | 0.340 m³/m² |
| Reinforcement per Floor Area | 53.76 kg/m² |
| Reinforcement per Concrete Volume | 158.20 kg/m³ |

The material consumption indicators were calculated using the reported aggregate material quantities and total floor area.

These estimates demonstrate the relationship between structural design decisions and material requirements.

Detailed component-level quantity calculations are available in the original technical report.

[View Material Quantity Calculations](report/)

---

## 9. Project Contribution and Academic Learning Outcomes

### Collaborative Contribution

This project was completed collaboratively by a team of three civil engineering students at Amirkabir University of Technology.

All team members participated jointly in the major stages of the project, including structural system selection, load calculations, computational modeling, structural analysis, reinforced concrete member design, foundation design, material quantity estimation, and technical reporting.

My contribution extended across all major project stages through collaborative engineering calculations, computational modeling, design discussions, interpretation of numerical results, and technical documentation.

The project results and original technical report represent the collective work of the three team members.

### Academic Learning Outcomes

Through this project, I developed experience in:

- Structural behavior of multi-storey reinforced concrete buildings.
- Evaluation and selection of structural systems.
- Application of structural and seismic design regulations.
- Integration of manual calculations and computational analysis.
- Interpretation of modal and seismic response results.
- Reinforced concrete member and foundation design.
- Finite element modeling and engineering simulation.
- Structural material quantity estimation.
- Technical reporting and collaborative engineering problem-solving.

The project strengthened my academic foundation in structural engineering and computational analysis, providing relevant preparation for graduate-level studies in Civil Engineering.

---

## 10. Project Documentation and Resources

The retained project materials are organized into the following directories:

| Resource | Description | Access |
|---|---|---|
| Academic Project Brief | Academic requirements and design objectives | [View PDF](project-brief/Concrete-Project-Brief.pdf) |
| Project Brief Directory | Academic requirements and supporting documents | [Open Directory](project-brief/) |
| Original Technical Report | Comprehensive 156-page engineering report in Persian | [View Report](report/) |
| ETABS Structural Model | Retained numerical model of the reinforced concrete building | [View Software Files](software-files/) |
| SAFE Foundation Model | Numerical model of the mat foundation | [View Software Files](software-files/) |
| Overall Structural Model | Three-dimensional ETABS building visualization | [View Image](images/etabs-3d-model.png) |
| Beam and Column Model | Three-dimensional reinforced concrete framing system | [View Image](images/etabs-beam-column-model.png) |
| Structural Floor Plan | Structural layout and member section assignments | [View Image](images/structural-floor-plan.png) |
| Mat Foundation Model | Three-dimensional foundation visualization in SAFE | [View Image](images/safe-foundation-model.png) |
| Project Visualizations | Selected structural and foundation model images | [Open Directory](images/) |

### Repository Structure

```text
01-Concrete-Structures/
│
├── README.md
│
├── images/
│   ├── README.md
│   ├── etabs-3d-model.png
│   ├── etabs-beam-column-model.png
│   ├── structural-floor-plan.png
│   └── safe-foundation-model.png
│
├── project-brief/
│   ├── README.md
│   └── Concrete-Project-Brief.pdf
│
├── report/
│
└── software-files/
```

The original academic report is written in Persian. This English README summarizes the project methodology, technical scope, and selected engineering results for international academic review.

The selected ETABS and SAFE visualizations complement the technical documentation by illustrating the overall structural geometry, reinforced concrete framing system, structural floor layout, and mat foundation configuration.

---

## Academic Disclaimer

This project was completed as part of undergraduate Civil Engineering coursework at Amirkabir University of Technology.

The models, calculations, and reported results are presented for academic documentation and graduate application purposes. They do not constitute independently verified or certified construction-ready engineering designs.

---

[Return to Main Civil Engineering Portfolio](../README.md)
