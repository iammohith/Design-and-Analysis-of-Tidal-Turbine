# Design and Analysis of Tidal Turbine

## Abstract

In the present world, there is massive energy demand. Most of this energy is supplied by coal, crude oil, and fossil fuels, leading to harmful environmental impacts such as high carbon emissions and global warming. To address this, renewable energy sources like wind, solar, geothermal, hydroelectric, and tidal energy are being explored. However, only a few tidal power plants exist globally.

This project focuses on harnessing **tidal energy**, where water currents convert into rotational energy through turbine blades, generating electricity. Using **Blade Element Momentum Theory (BEMT)**, we designed a turbine placed at a depth of 120 meters below sea level. 

Computational Fluid Dynamics (CFD) simulations are used to analyze various factors like fluid velocity, pressure, turbulent kinetic energy, eddy viscosity, velocity vector, thrust force, and torque. These analyses help in understanding the efficiency of the designed turbine for power extraction.

Additionally, **Static Structural Analysis** checks the stresses and forces on the blade due to pressure at higher depths, and **Modal Analysis** is performed to ensure the turbine avoids resonance by evaluating frequencies, vibrations, and noise levels. 

## Contents

1. **Certificate**
2. **Declaration**
3. **Abstract**
4. **Acknowledgement**
5. **List of Figures**
6. **List of Tables**
7. **Chapter 1: Introduction**
   - 1.1 Ocean Energy
      - 1.1.1 Global Potential
   - 1.2 Forms of Ocean Energy
   - 1.3 Tide
     - 1.3.1 Characteristics
     - 1.3.2 Definitions
   - 1.4 Methods to Extract Tidal Energy
     - 1.4.1 Tidal Barrages
     - 1.4.2 Tidal Stream Energy
8. **Chapter 2: Literature Review**
   - 2.1 Literature Survey
   - 2.2 Motivation for Present Work
9. **Chapter 3: Objectives and Methodology**
   - 3.1 Objectives
   - 3.2 Methodology
     - 3.2.1 Betz Limit Theory
     - 3.2.2 Blade Element Momentum Theory
     - 3.2.3 Static Structural Analysis
     - 3.2.4 Cantilever Beam
     - 3.2.5 Finite Element Analysis
     - 3.2.6 Modal Analysis
     - 3.2.7 Computational Fluid Dynamics
     - 3.2.8 Finite Volume Method
     - 3.2.9 Shear Stress Transport
10. **Chapter 4: Numerical Analysis**
    - 4.1 Blade Element Momentum Analysis
    - 4.2 Static Structural Analysis
    - 4.3 Modal Analysis
    - 4.4 Flow Analysis
11. **Chapter 5: Results and Discussion**
    - 5.1 Static Structural Analysis Results
    - 5.2 Modal Analysis Results
    - 5.3 Flow Analysis Results
12. **Chapter 6: Conclusion**
13. **References**

## Conclusion

The study presented results from the shape modeling of a tidal current power turbine based on turbine design theory and 3-D flow analysis using CFD. A horizontal axis tidal current power turbine was designed with a diameter of 2 m, utilizing a NACA 4412 airfoil and considering tip loss. 

Using SOLIDWORKS for modeling and ANSYS CFX V11 SP1 for analysis, a performance curve and torque curve were generated. At a design flow of 1.0 m/s, the maximum output coefficient was approximately 0.51 at a tip speed ratio (TSR) of 5, yielding a maximum torque of 1499.45 N-m. 

The flow phenomena around the turbine were studied, revealing that as TSR increases, negative pressure on the suction side also increases, leading to decreased output beyond the optimal TSR. The model displayed negligible deformation in the Static Structural Analysis, indicating that the stresses remained below the tensile yield strength. The frequency analysis confirmed no resonance issues within the operational range. Overall, the CFX analysis highlighted maximum torque and thrust force at the optimal TSR of 5.

## References
