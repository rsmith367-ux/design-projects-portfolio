# A7 – [Topic]

## Objective

The objective of this assignment is to use finite element analysis (FEA) to improve the bracket design developed in Assignments #5 and #6. The goal is to create a bracket that balances strength, stiffness, and low mass while maintaining an appropriate factor of safety. Static stress simulations will be performed to evaluate maximum stress, maximum displacement, and safety factor. Mesh convergence will be checked by refining the mesh until the results differ by no more than 7%, or until three convergence attempts have been completed. At least three design iterations will be evaluated to determine how changes in geometry affect the bracket's structural performance.

### Design Requirements

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

### Initial Bracket 

![Bracket FEA Model](picture1png%20-%20Copy%20%282%29.png)

I started with my A5 bracket CAD model and used it as the initial FEA design. The original model included an upper mounting feature, a narrow drop-down arm, and a lower cylindrical support. The original bracket's calculated mass in SOLIDWORKS was 0.56 lb.

## Initial FEA Setup

I used a static study in SOLIDWORKS Simulation to evaluate my original A6 bracket design. First, I assigned A36 steel as the material and applied fixed geometry to the mounting faces where the bracket connects to the T-beam. This represents the bracket being restrained at its mounting connection.

![Initial FEA Setup](<picture2png - Copy (2).png>)

I then applied the 1,400 lbf downward force to the loading face on the lower cylindrical support to represent the force acting on the bracket. I kept the support and loading conditions consistent so I could compare the original design with my later design iterations.

![Initial FEA Setup](<picture3png - Copy (2).png>)

I generated an initial mesh and ran the static simulation to evaluate the maximum von Mises stress, maximum resultant displacement, and minimum factor of safety. I used these results as the baseline for evaluating how changes to the bracket geometry affected its structural performance and mass.


### Workflow and Mesh Validation

I started by running a static FEA study on my original A6 bracket design. I refined the mesh over three successive runs while keeping the geometry, material, fixtures, and applied load the same. This allowed me to check how mesh refinement affected the simulation results.

To check mesh convergence, I calculated the percent change between consecutive runs using:

$$
\text{Percent Change} =
\frac{|\text{New Result} - \text{Previous Result}|}
{|\text{Previous Result}|}
\times 100\%
$$

I compared the maximum von Mises stress, maximum resultant displacement, and minimum factor of safety for each mesh. The goal was to achieve a percent change of no more than 7% between consecutive runs, or complete three convergence attempts as required by the assignment. If the stress results did not converge within the three attempts, I recorded the results from the finest mesh.

After evaluating the original bracket, I used the simulation results to guide changes to the geometry. I repeated the analysis for three design iterations to compare how each design affected stress, displacement, factor of safety, and mass.

## Analyze


## Decide


## Communicate

