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

To add the references section to your README, you can format it as follows:

## References

### Journal Papers
1. Chul Hee Jo, Jin Young Yimb, Kang Hee Leeb, and Yu Ho Rhob. *Performance of Horizontal Axis Tidal Current Turbine*. Renewable Energy, 2011.
2. D. M. Grogan, S.B. Leen, C.R. Kennedy, and C.M. Ó Brádaigh. *Design of Composite Tidal Turbine Blades*. Renewable Energy, 2013.
3. Alex E. Ockfen and Konstantin I. Matveev. *Aerodynamic Characteristics of NACA 4412 Airfoil Section with Flap in Extreme Ground Effect*. International Journal of Naval Architecture and Ocean Engineering, 2009.
4. Andreas Uihlein and Davide Magagna. *Wave and Tidal Current Energy – A Review of The Current State of Research Beyond Technology*. Renewable and Sustainable Energy Reviews, 2015.
5. Luthra, Sunil Kumar, Sanjay, Garg Dixit, and Haleem Abid. *Barriers to Renewable/Sustainable Energy Technologies Adoption: Indian Perspective*. Renewable and Sustainable Energy Reviews, 2014.
6. Kemp, P.H., and Simons R.R. *The Interaction Between Waves and A Turbulent Current: Waves Propagating with The Current*. Fluid Mechanics, 1982.
7. Sanil Kumar V., Dora G. Udhaba, Philip C., Pednekar P., and Singh Jai. *Nearshore Currents along the Karnataka Coast, West Coast of India*. The International Journal of Ocean and Climate Systems, 2012.
8. Chul Hee Jo and Su Jin Hwang. *Review on Tidal Energy Technology on Research Subjects*. Chinese Ocean Engineering Society and Springer, 2019.
9. Funke, S.W., Farrell, P.E., and Piggott, M.D. *Tidal Turbine Array Optimisation Using the Adjoint Approach*. Renewable Energy, 2014.
10. Sanjay V., Jain Rajesh, and Patel N. *Investigations on Pump Running in Turbine Mode: A Review of The State-Of-The-Art*. Institute of Technology, Nirma University, 2013.
11. Couch S. J. and Bryden I. G. *Tidal Current Energy Extraction: Hydrodynamic Resource Characteristics*. Proc. Imeche Vol. 220 Part M: J. Engineering for The Maritime Environment, 2006.
12. Bae, Y.H., Kim, K.O., and Choi, B.H. *Lake Sihwa Tidal Power Plant Project*. Ocean Engineering, 2010.
13. Ko, D.H., Chung, J., Lee, K.S., Park, J.S., and Yi, J.H. *Current Policy and Technology for Tidal Current Energy in Korea*. Energies, 2019.
14. Brito E Melo A and Villate JL. *Annual report 2013. Implementing Agreement on Ocean Energy Systems*. 2013.
15. Bryden I. G. and Scott J. C. *How Much Energy Can Be Extracted from Moving Water with A Free Surface: A Question of Importance in The Field of Tidal Current Energy?* Journal of Renewable Energy, 2007.
16. Batten, W.M.J., Bahaj A.S., Molland A.F., and Chaplin, J.R. *Experimentally Validated Numerical Method for The Hydrodynamic Design of Horizontal Axis Tidal Turbines*. Ocean Engineering, 2007.

### Books
1. D. M. Somers. *The S814 and S815 Airfoil*. National Renewable Energy Laboratory, 2004.
2. Peter J. Tavner. *Wave and Tidal Generation Devices*. British Library Cataloguing in Publication Data, 2017.

### Conference Proceedings
1. Vikas M., Subba Rao, and Jaya Kumar Seelam. *Tidal Energy: A Review*. Proceedings of International Conference on Hydraulics, Water Resources and Coastal Engineering, 2016.
2. Garbuglia E, Rosa A D, Berti D. *Exploitation of Marine Current Energy*. Offshore Technology Conference, 1993.
3. Encarnacion, J.I., Johnstone, C. *Preliminary Design of a Horizontal Axis Tidal Turbine for Low-Speed Tidal Flow*. In Proceedings of the 4th Asian Wave and Tidal Energy Conference, 2018.
4. Walsum W. *Offshore Engineering for Tidal Power*. Proceedings of The Ninth International Offshore and Polar Engineering Conference, 1999.
5. Paish O. and Fraenkel P. *Tidal Stream Energy Zero-Head Hydropower*. International Conference on Hydropower into The Next Century, 1995.
6. Shiono M. *Experiments on The Characteristics of Darrieus Turbine for Tidal Power Generation*. Proceedings of The Ninth International Offshore and Polar Engineering Conference, 1999.
7. Jo CH, Lee CH, Rho YH, and Yim J.Y. *Floating Tidal Current Power Application in Cooling Water Channel*. The Korean Association of Ocean Science and Technology Societies Conference, 2008.
