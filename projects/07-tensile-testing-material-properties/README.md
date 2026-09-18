# Tensile Testing & Material Properties

## Project Overview

This project analyzes tensile-test data to determine key mechanical properties of a metallic specimen and connect the measured stress-strain response to material behavior and engineering design decisions.

The analysis focuses on elastic behavior, yielding, ultimate strength, ductility, necking, and fracture.

## Engineering Objectives

- Construct and interpret an engineering stress-strain curve
- Determine Young's modulus from the elastic region
- Estimate the 0.2% offset yield strength
- Determine ultimate tensile strength
- Calculate percent elongation and reduction of area
- Compare engineering stress and true stress near fracture
- Interpret material behavior throughout the tensile test

## Key Results

| Property | Approximate Result |
|---|---:|
| Young's Modulus, E | 3.94 × 10^7 psi |
| 0.2% Offset Yield Strength | 68 ksi |
| Ultimate Tensile Strength | 82.6 ksi |
| Elongation over 2 in gauge length | 23.8% |
| Elongation over 8 in gauge length | 8.2% |
| Reduction of Area | 54.9% |
| True Stress at Fracture | 183 ksi |

> Results are based on the original academic tensile-test analysis and are presented as approximate experimental values.

## Methodology

### Engineering Stress

Engineering stress was calculated from the applied load and original specimen area:

```text
σ = P / A₀
```

### Engineering Strain

Engineering strain was calculated from the change in gauge length:

```text
ε = ΔL / L₀
```

### Young's Modulus

Young's modulus was estimated from the slope of the approximately linear elastic region:

```text
E = Δσ / Δε
```

The experimental result was approximately **3.94 × 10^7 psi**.

### Yield Strength

The 0.2% offset method was used to estimate the onset of permanent plastic deformation. The resulting yield strength was approximately **68 ksi**.

### Ultimate Tensile Strength

The maximum engineering stress recorded during the test was approximately **82.6 ksi**.

### Ductility

Ductility was evaluated using elongation and reduction of area:

- Elongation over 2 in gauge length: **23.8%**
- Elongation over 8 in gauge length: **8.2%**
- Reduction of area: **54.9%**

### True Stress at Fracture

Because engineering stress uses the original specimen area, it becomes less representative after necking. Using the reduced fracture area produced an estimated true fracture stress of approximately **183 ksi**.

## Material Behavior

The tensile test demonstrates the progression from elastic deformation through yielding, plastic deformation, strain hardening, ultimate tensile strength, necking, and fracture.

The results show why material selection depends on more than maximum strength. Stiffness, yield behavior, ductility, and fracture characteristics are also important in mechanical design.

## Skills Demonstrated

- Mechanical materials testing
- Stress-strain analysis
- Young's modulus calculation
- 0.2% offset yield-strength determination
- Ultimate tensile strength evaluation
- Engineering vs. true stress
- Ductility calculations
- Experimental data interpretation
- Technical reporting

## Connection to My FEA Project

This project complements my [SOLIDWORKS FEA Stress Concentration Study](../01-solidworks-stress-concentration/README.md).

The tensile test examines experimentally measured material behavior, while the FEA project examines how geometry affects stress and displacement numerically. Together, they demonstrate both experimental and computational approaches to mechanical engineering analysis.

## Future Improvements

Planned additions include:

- Original tensile-test data in CSV format
- Engineering stress-strain plot
- 0.2% offset yield-strength plot
- Specimen dimensions before and after testing
- Fracture photographs
- Comparison with published material properties
- Experimental error and uncertainty discussion

---

**Project Type:** Academic Mechanical Engineering Laboratory  
**Topics:** Materials Testing · Stress-Strain · Mechanical Properties · Experimental Analysis
