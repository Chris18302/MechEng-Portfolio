# Stress Concentration Study: Plate With vs. Without a Hole

## Objective
Compare the stress and displacement response of a solid plate with a plate containing a central hole under static loading. The project demonstrates how a geometric discontinuity changes the local stress field.

## Engineering Question
How does adding a hole to a loaded plate affect stress concentration and displacement compared with a geometrically similar plate without the hole?

## Method
1. Created two plate geometries in SOLIDWORKS.
2. Assigned linear elastic material properties.
3. Applied fixed boundary conditions and static face loads.
4. Generated high-quality solid meshes.
5. Reviewed von Mises stress, resultant displacement, and deformed shape.
6. Compared the two configurations and documented the effect of the hole.

## Available Results
One completed SOLIDWORKS Simulation study for the no-hole plate used Alumina, a 10 N load, and a high-quality mesh with 15,076 nodes / 7,369 elements. The reported maximum von Mises stress was approximately **6.02e4 N/m²** and the maximum resultant displacement was approximately **2.665e-5 mm**.

A second study modeled the plate with a central hole using alloy steel and a static load. The key portfolio takeaway is the **stress-concentration behavior around the geometric discontinuity**, not a direct material-to-material comparison.

## What I Learned
- Boundary conditions and material selection strongly affect absolute FEA results.
- Mesh quality matters most around geometry changes such as holes, fillets, and notches.
- A valid comparison should keep geometry scale, material, loading, and constraints consistent.
- Stress concentration is a localized effect and should be interpreted with mesh convergence in mind.

## Next Improvement
Re-run both models with identical material, load, constraints, thickness, and a local mesh refinement around the hole. Then calculate a numerical stress-concentration factor and compare it with a handbook/theoretical value.

## Skills Demonstrated
SOLIDWORKS Simulation · FEA · von Mises stress · displacement · meshing · boundary conditions · engineering interpretation
