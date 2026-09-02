# A2 – Truss Stress Analysis

## Objective

The objective of this project is to design a lightweight planar truss that can support the required loading while maintaining structural integrity and the required factor of safety. The design process includes determining the internal forces in each truss member, sizing the members and connecting pins, estimating the weight, and verifying the design using CAD. The final design will be compared to the analytical calculations to evaluate the accuracy of the design.

### Design Requirements

- Applied load, P: 25 kN
- a = 0.4 m
- b = 0.3 m
- Point A: Pin support
- Point B: Roller support
- Truss material: A500 structural steel
- Truss safety factor: 3.5
- Pin material: Hardened tool steel
- Pin shear yield strength: 170 ksi
- Pin safety factor: 4
- Pin density: 0.278 lb/in³
- Number of pins: 5


## Analyze

### 1. Initial Truss Geometry

![Initial Truss Sketch](Screenshot%202026-09-02%20091846.png)

The initial sketch was created to establish the overall geometry of the truss and identify the required dimensions, loading locations, and support conditions. At this stage, the goal was to develop a simple and stable layout that could be analyzed using the method of joints. This sketch served as the starting point for evaluating the geometry and making changes before selecting the final truss design.


### 2. Final Truss Geometry and Overall Truss FBD with Reaction Forces Calculations

![Final Truss Geometry](Screenshot%202026-09-02%20092536.png)


The final truss geometry was selected based on structural stability, simplicity, and weight. The geometry meets the required dimensions and support conditions while providing a simple layout that is easy to manufacture and analyze. This final design was used for the remaining calculations, including member forces, cross-sectional sizing, pin sizing, and total weight.

- a = 0.4 m

- b = 0.3 m
  
- Applied loads = 25 KN
  
- Ax = 0 KN
  
- Ay = 25 KN
  
- By = 25 KN
  
### 1. Joint Analysis 

### Joint Free-Body Diagrams

#### Joint A
![Joint A](jointA.png)

#### Joint B
![Joint B](jointb.png)

#### Joint C
![Joint C](jointC.png)

#### Joint D
![Joint D](jointD.png)

#### Joint E
![Joint E](jointE.png)


The free-body diagrams for each joint were created to determine the internal forces acting on every truss member. Starting with the known support reactions, the method of joints was used by applying the equilibrium equations, \(\sum F_x=0\) and \(\sum F_y=0\), at each joint. The calculated member forces were then used to identify whether each member was in tension or compression and to determine the largest internal force in the truss.

Analyzing the joints individually also provided a way to verify that the truss remained in equilibrium throughout the analysis. The results from each joint were carried forward to the next joint until all member forces were determined. These forces were then used in the member sizing and stress calculations to select a cross-sectional area that satisfies the required factor of safety.

The joint analysis determined the force carried by each member and whether the member was subjected to tension or compression. The largest calculated member force was used as the critical loading condition for sizing the truss members. This result was then carried into the stress analysis to determine the minimum required cross-sectional area while maintaining the specified factor of safety.

### 4. Truss Member Sizing



