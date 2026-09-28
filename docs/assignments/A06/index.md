# A6 – [Topic]

## Objective

The objective of this assignment was to continue the design of the bracket from the previous assignment by creating a fully parametric CAD model and a detailed engineering drawing. The final model needed to incorporate the dimensions determined from the previous strength and stiffness analysis while also accounting for the updated T-beam specifications and sliding-fit requirements.

The main goals of this assignment were to:

Create a complete parametric solid model of the bracket.
Use the dimensions determined from the previous engineering analysis.
Define important dimensions as CAD parameters.
Connect an engineering calculation to at least one CAD parameter.
Account for the updated T-beam dimensions and sliding-fit requirements.
Create a fully dimensioned multi-view engineering drawing.
Use third-angle projection.
Apply appropriate linear tolerances.
Include a tolerance block and title block.
Document the design process, mistakes, changes, and time spent.
Provide a downloadable CAD file for the completed design.
Design Requirements

The bracket was designed to attach to a rigid T-beam and hold a polyester strap. The updated T-beam specifications used for the interface were:

(a = 0.498) in
(b = 0.9992) in
(c = 1.499) in

The material selected for the bracket was A36 steel.

The material properties used in the previous analysis were:

Yield strength: (S_y = 36,000) psi
Elastic modulus: (E = 29,000,000) psi
Factor of safety: 4
Allowable stress: 9,000 psi
Maximum allowable deflection: 0.005 in

![bracket Concept Design from A5](pic6.png)


## Analyze
The starting point for this assignment was the strength and stiffness analysis completed in the previous assignment. The calculated dimensions were compared to determine which requirement governed each feature.

The previous analysis showed that the stress requirement governed the final dimensions for Features A through E.

### Final Feature Dimensions
Feature	Stress Requirement	Stiffness Requirement	Final Dimension
A	1.006 in	0.516 in	1.006 in
B	0.133 in	0.0165 in	0.133 in
C	0.133 in	0.0652 in	0.133 in
D	0.053 in	0.0031 in	0.050 in
E	0.053 in	0.0033 in	0.050 in

These values were used as the primary design dimensions for the parametric CAD model.

### Parametric Modeling

![CAD Parametric Table ](pic2.png)


Instead of treating each dimension as an independent value, the important dimensions were set up as parameters in CAD. This allows the model to respond to changes in the design requirements without requiring every feature to be manually remodeled. The parametric table contains the important dimensions used to control the bracket geometry. The parameters include the feature dimensions as well as other important dimensions used to define the bracket and its interface.

### Engineering Equation Used to Drive the Model

One of the dimensions was connected to the engineering analysis rather than simply entering the final calculated value manually.

For Feature A, the strength analysis used the bending-stress relationship:

[
\sigma = \frac{M}{Z}
]

The allowable stress was determined using the factor of safety:

[
\sigma_{allow}=\frac{S_y}{SF}
]

Using the A36 steel yield strength of 36,000 psi and a factor of safety of 4:

[
\sigma_{allow}=\frac{36,000}{4}
]

[
\sigma_{allow}=9,000\text{ psi}
]

The resulting strength calculation determined that Feature A required a final dimension of:

[
\boxed{1.006\text{ in}}
]

This dimension was incorporated into the CAD parameter system so that the model could update when the parameter was changed.

![Feature A dimensions](pic3.png)

### T-Beam Interface

The updated T-beam specifications were also considered when modeling the bracket. The bracket interface needed to provide the required sliding fit over the rigid T-beam.

The updated T-beam dimensions were:

(a = 0.498) in with a tolerance of (+0.000/-0.001) in
(b = 0.9992) in with a tolerance of (+0.000/-0.0005) in
(c = 1.499) in with a tolerance of (+0.000/-0.001) in

These dimensions were used to determine the corresponding bracket interface geometry and gaps.

![Feature A dimensions](pic3.png)


## Decide


## Communicate

