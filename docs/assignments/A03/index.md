# A3 – [Topic]

## Objective

The purpose of this assignment is to design an aluminum bar subjected to direct axial tension using parametric modeling and finite element analysis (FEA). The design must satisfy a maximum axial deflection of 0.009 inches while using a load between 300 and 500 lbf. A circular cross section was selected for the bar, and the required length was determined using the direct tension elongation equation. The resulting geometry was then created parametrically in CAD so that changes to the design parameters would automatically update the bar's dimensions. Finally, FEA was used to verify the axial deflection and stress of the design and to compare the FEA results with the analytical calculations.

## Analyze

## Initial Design Parameters

![Bar Design](work1.png)

The first step was to determine the design parameters that would be used for the bar. A load of 400 lbf was selected because it falls within the required range of 300 to 500 lbf. A Young's modulus of \(10\times10^6\) psi was selected, which is within the specified aluminum range of \(8.5\times10^6\) to \(11.5\times10^6\) psi. The maximum allowable axial deflection was set to 0.009 inches. A circular cross section with a diameter of 0.25 inches was selected for the bar.

For the Cross-Sectional Area, a circular cross section was selected based on the geometry shown in the assignment. The bar diameter was selected as 0.25 inches. The cross-sectional area was calculated using the area equation for a circle. The resulting area was then used in the direct tension elongation equation to determine the required length of the bar.

The direct tension elongation equation was used to determine the required length of the bar. The maximum allowable axial deflection was known to be 0.009 inches. Since the applied force, cross-sectional area, Young's modulus, and maximum allowable deflection were known, the equation was rearranged to solve for the length.The analytical calculation resulted in a required bar length of approximately 11.05 inches. This length was then used as the basis for the parametric CAD model.

![Bar Design](work2.png)

The nominal stress in the bar was also calculated to provide a theoretical value to compare with the FEA results. The calculated nominal stress of approximately 8.15 ksi is below the specified aluminum yield strength of 40 ksi. The theoretical safety factor was then calculated. This indicates that the initial analytical design is below the specified yield strength.

## Parametric CAD Analysis

![CAD](barWrightdiameter.png)

The calculated design parameters were then incorporated into the CAD model using parametric equations. The force, Young's modulus, maximum allowable deflection, diameter, cross-sectional area, and length were defined as parameters. The cross-sectional area was calculated from the diameter, while the length was calculated using the axial deflection equation. Linking these values together allows the model to automatically update when a design parameter is changed. The final analytical geometry was a circular bar with a diameter of 0.25 inches and a calculated length of approximately 11.05 inches.

## FEA Setup

![Mesh](mesh.png)

The completed CAD model was then prepared for finite element analysis. The left end of the bar was fixed to represent the support shown in the assignment, while a 400 lbf tensile load was applied to the opposite end in the axial direction. The aluminum material was assigned using the selected Young's modulus of \(10\times10^6\) psi. A mesh was then generated over the model before running the simulation.

## Decide





## Communicate

