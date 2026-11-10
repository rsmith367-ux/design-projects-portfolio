# A9 – Pulleys

## Objective

The objective of this project was to design a pulley system capable of transferring power between two parallel shafts separated by a center distance of 4–6 inches. The design required two 3-inch-diameter pulleys connected by a polyurethane rubber belt, operating at a selected speed between 1,000 and 2,000 RPM.

To complete the design, I needed to determine the appropriate belt size and length, calculate the minimum required shaft diameter using hardened 1060 steel, and select suitable journal bearings based on their pressure, surface velocity, and PV rating. I also needed to design a supporting frame capable of holding the pulley system while maintaining a minimum factor of safety of 3.

Throughout this project, I applied engineering principles involving force analysis, torque, stress, material selection, and deflection to develop a pulley system that met the assignment requirements.

### Design Requirements and Initial Choices

I began the pulley system design by identifying the requirements provided in the assignment and selecting values that fell within the allowed design ranges. I chose a pulley diameter of 3 inches, a center distance of 5 inches, and an operating speed of 1,500 RPM. I also selected a stationary belt tension of 5 lbf and a minimum required safety factor of 3.

For the materials, I selected polyurethane rubber for the belt, hardened 1060 steel for the shafts, sintered metal as the initial journal bearing material selection, and 6061-T6 aluminum for the supporting frame. These choices established the starting parameters for the belt, shaft, bearing, and frame calculations.
## Analyze

![Known design Parameters and Choices](pic1.png)

## Analyze

### Belt Design

I started the design process by focusing on selecting the belt for the pulley system. First, I listed the known and unknown variables and created a free-body diagram (FBD) to identify the forces acting on the belt.

Next, I used the stationary belt tension and the belt friction relationship to calculate the tight-side and loose-side forces. From these calculations, I obtained a tight-side force of 9.59 lbf and a loose-side force of 0.414 lbf.

After determining the belt forces, I calculated the required belt cross-sectional area and diameter using the given polyurethane rubber yield strength of 471 psi and a safety factor of 3. The calculated belt diameter was 0.279 inches, with a cross-sectional area of 0.0611 in².

Finally, I calculated the theoretical belt length using the selected pulley diameter and center distance. The calculated open-belt length was approximately 19.425 inches. This provided an initial belt length to use when selecting a suitable belt from the McMaster-Carr catalog.

![Calculations ](pic2.png)

![Calculations ](pic3.png)

### Minimum Shaft Diameter

After completing the belt design, I moved on to determining the minimum required shaft diameter. I used the tight-side and loose-side belt forces calculated in the previous section to determine the torque applied to the pulley shaft.

I first identified the known values, including the belt forces and the yield strength of hardened 1060 steel. I then created a free-body diagram to represent the shaft's loading and direction of rotation.

Using the difference between the tight-side and loose-side belt forces and the pulley radius, I calculated the torque transmitted through the shaft. I then applied the torsional stress relationship to determine the minimum shaft diameter while accounting for the required safety factor.

The calculated minimum shaft diameter was approximately 0.173 inches. This value represents the theoretical minimum based on the loading and material properties used in my calculations.

![Calculations ](pic4.png)

### Journal Bearing Design

Once I determined the minimum shaft diameter, I began evaluating the journal bearing requirements. I used the shaft diameter, operating speed, and belt forces to calculate the bearing loading conditions.

I first determined the radial force acting on the pulley shaft by adding the tight-side and loose-side belt forces. This resulted in a radial force of 10 lbf. I then used the shaft diameter and an assumed bearing length of 3 inches to calculate the projected bearing area.

Using the radial force and projected area, I calculated an average bearing pressure of approximately 19.27 psi. Next, I calculated the shaft's surface velocity using the shaft diameter and operating speed of 1,500 RPM. The resulting surface velocity was approximately 67.94 ft/min.

Finally, I multiplied the bearing pressure by the surface velocity to obtain a PV value of approximately 1,309 psi·ft/min. This value can be used to evaluate suitable journal bearing materials. Based on my initial material investigation, I considered nylon, polycarbonate, and acetal as potential nonmetallic bearing options.

![Calculations ](pic5.png)

![Calculations ](pic6.png)

### Frame Design and Engineering Analysis

After completing the pulley, shaft, and bearing calculations, I moved on to designing a frame to support the pulley system. I selected 6061-T6 aluminum as the frame material because it provides sufficient strength for the loading conditions while keeping the structure relatively lightweight.

I used a design load of 10 lbf and a minimum safety factor requirement of 3 to evaluate the frame. I calculated the cross-sectional area of the frame and used the applied load to determine the resulting stress. I also considered the effect of the mounting holes by calculating the net cross-sectional area.

The calculated stress for the original cross-section was approximately 26.67 psi, resulting in a safety factor of approximately 1,500. After accounting for the mounting holes, the net stress increased to approximately 32 psi, giving a safety factor of approximately 1,250. Both calculated safety factors were greater than the required minimum of 3.

I also calculated the estimated frame deflection under the applied load. The resulting deflection was approximately 0.0000133 inches. Based on these simplified calculations, the proposed frame cross-section has sufficient strength and stiffness for the loading conditions considered.

![Frame](pic8.png)

![Calculations](pic9.png)

## Communicate

### Conclusion and Lessons Learned

Throughout this project, I learned how the different components of a pulley system depend on one another. The belt forces determined the torque transmitted to the shaft, while the shaft diameter and applied loading were used to evaluate the journal bearing requirements. I also learned how to use stress, safety factor, and deflection calculations to evaluate a supporting frame.

One important lesson I learned was how changes in belt tension affect the overall system. The difference between the tight-side and loose-side belt forces determines the torque transmitted through the pulley, while their combined loading contributes to the radial force acting on the shaft and bearings.

I also learned the importance of considering the mounting holes when evaluating a frame. Although the original cross-sectional area provided a certain stress value, removing material for mounting holes reduced the net area and increased the calculated stress.

Overall, this project helped me understand how to apply statics, mechanics of materials, and machine design principles to a complete mechanical system rather than analyzing each component independently.

**Time Spent:** I spent approximately 2.5 hours (2 hours and 30 minutes) completing the calculations and design analysis for this pulley system project.
