# A5 – [Topic]

## Objective

The objective of this project is to conduct stress and stiffness analyses to determine appropriate dimensions for the structural features. Free body diagrams (FBDs) were created to visualize the forces and constraints acting on each feature, while known and unknown variables, assumptions, and algebraic models were identified for the stress calculations. Stiffness analysis was performed to establish the minimum required dimensions based on deflection constraints. The stress and stiffness results were then compared to ensure structural integrity and compliance with the given requirements. Detailed multiview sketches were created to illustrate the dimensions determined from the analyses, and key engineering lessons learned throughout the design process were documented.


## Analyze
### Requirements and values
![Requirements and values ](Pic1.png)
![Requirements and values ](Pic2.png)
### Feature A
![Feature A](Pic2.png)
![Feature A](Pic3.png)

Feature A was modeled as a circular beam subjected to a 1200 lbf load. Stress and stiffness analyses were performed using a factor of safety of 4 and a maximum allowable deflection of 0.005 in. Stress required a diameter of 1.006 in, while stiffness required 0.516 in. Since stress governed, the final diameter was selected as **1.006 in**.

### Feature B
![Feature B](Pic3.png)
![Feature B](Pic4.png)

Feature B connects Feature A to the upper bracket and was modeled as an axially loaded member. The applied load was 1200 lbf. Stress required a diameter of 0.133 in, while stiffness required 0.0165 in. Since stress governed the design, the final diameter was selected as **0.133 in**.

### Feature C
![Feature C](Pic4.png)
![Feature C](Pic5.png)

Feature C was modeled as a simply supported beam with a 600 lbf reaction force from Feature B. Stress and stiffness were analyzed using a factor of safety of 4 and a maximum allowable deflection of 0.005 in. Stress required a diameter of 0.133 in, while stiffness required 0.0652 in. The final diameter was selected as **0.133 in** because stress governed.

### Feature D
![Feature D](Pic5.png)

Feature D was modeled as an axially loaded T-section carrying a 600 lbf load. Stress required a thickness of 0.053 in, while stiffness required 0.00331 in. Since stress was the governing requirement, the final thickness was selected as **0.050 in**.


### Feature E
![Feature D](Pic6.png)

Feature E carries the load transferred from Feature D and was analyzed as an axially loaded T-section. Stress required a thickness of 0.053 in, while stiffness required 0.00331 in. Stress governed the design, resulting in a final thickness of **0.050 in**.

### Final Table
![Final Table](Pic7.png)

The final multiview drawings were created to communicate the completed bracket design and the dimensions determined from the stress and stiffness analyses. The drawings include the necessary views and dimensions for Features A–E, showing the final geometry selected for the design. These drawings provide a clear representation of the bracket that can be used to communicate the final design and manufacturing requirements.


## Decide
### Multi-view drawings
![Drawings](Pic8.png)

The final multi-view drawings were created to communicate the completed bracket design and the dimensions determined from the stress and stiffness analyses. The drawings include the necessary views and dimensions for Features A–E, showing the final geometry selected for the design. These drawings provide a clear representation of the bracket that can be used to communicate the final design and manufacturing requirements.

## Lessons Learned

### Governing Failure Mode

For all of the features analyzed, **stress governed the required dimensions** over stiffness. For Feature A, the stress analysis required a diameter of **1.006 in**, while the stiffness analysis required **0.516 in**. For Feature C, stress required **0.133 in**, while stiffness required **0.0652 in**. Features B, D, and E also had larger dimensions required by stress than by stiffness. This demonstrates that both strength and stiffness calculations are necessary because either requirement could potentially control the final design.

### Error Propagation

The forces calculated for one feature are used as the applied loads for the following features. Because of this, an incorrect reaction force early in the analysis would affect the calculations for the remaining features. For example, the **1200 lbf** load applied to Feature C produces two **600 lbf** reactions. These 600 lbf reactions are then used as the loads for the upper features. This showed the importance of checking each free body diagram and reaction force before continuing with the next feature.

### Assumption Sensitivity

Several assumptions were made throughout the analysis, including neglecting direct shear failure and shear deformation, assuming constant cross sections, assuming the material remains elastic, and assuming deflections are small. These assumptions simplify the calculations and allow the features to be modeled using basic beam and axial-loading equations. If shear effects or other deformation modes were included, the calculated stresses and deflections could change and potentially affect the required dimensions.

### Material and Safety Factor

The analysis used **A36 steel** with a yield strength of **36,000 psi** and an elastic modulus of **29,000,000 psi**. A **factor of safety of 4** was used to determine the allowable stress of **9,000 psi**. Using the safety factor helped ensure that the final dimensions provided an appropriate margin between the expected loading and the material's yield strength.

### Design Comparison

The stress and stiffness calculations were compared for each feature before selecting the final dimensions. The larger requirement was used as the governing dimension. The final dimensions were **1.006 in for Feature A, 0.133 in for Feature B, 0.133 in for Feature C, 0.050 in for Feature D, and 0.050 in for Feature E**. Comparing the two analyses helped ensure that the final design met both the strength and deflection requirements.

### Project Time

**Total time spent on the project: 7 hours.**

The majority of the time was spent creating the free body diagrams, performing the stress and stiffness calculations, comparing the required dimensions, and creati



