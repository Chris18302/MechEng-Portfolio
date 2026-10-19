# Stress Concentration Study: Plate With vs. Without a Hole

## Executive Summary

Modeled loaded plates in SOLIDWORKS Simulation to examine how a geometric discontinuity changes the local stress field. The exercise demonstrated FEA setup, meshing, boundary conditions, stress/displacement interpretation, and—most importantly—the limitations of comparing simulations when material and setup conditions are not held constant.

## Engineering Question

How does a central hole affect stress concentration and displacement in a loaded plate?

## Actions

- Created plate geometries in SOLIDWORKS.
- Assigned linear elastic material properties.
- Applied fixed constraints and static face loading.
- Generated solid meshes and reviewed mesh quality.
- Compared von Mises stress, displacement, and deformed shape.
- Identified why the original two-model comparison was not a controlled quantitative comparison.

## Available Results

For one completed no-hole study:

| Item | Result |
|---|---:|
| Material | Alumina |
| Load | 10 N |
| Nodes | 15,076 |
| Elements | 7,369 |
| Maximum von Mises stress | ≈ 6.02 × 10⁴ N/m² |
| Maximum resultant displacement | ≈ 2.665 × 10⁻⁵ mm |

The hole model used a different material, so the project supports a **qualitative stress-concentration conclusion**, not a defensible direct numerical comparison.

## Critical Trade-Off / Limitation

The most important lesson is experimental control: material, load, geometry scale, thickness, constraints, and mesh strategy must be consistent before attributing numerical differences to the hole itself.

## What I Would Do Differently

Re-run both models with identical inputs, perform local mesh refinement around the hole, check convergence, calculate a stress-concentration factor, and compare it with a theoretical or handbook value.

## Skills Demonstrated

SOLIDWORKS Simulation · FEA · Meshing · Boundary conditions · von Mises stress · Displacement · Engineering interpretation
