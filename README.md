# Gravitational-Acceleration
Determining gravitational acceleration from free-fall and Kater's pendulum.

Chapter 31 Project C: Gravity

If I was to write a more exciting title: How accurately can you measure gravitational acceleration

31.1 General background

In physics, precise knowledge of fundamental constants is important. The acceleration due to gravity, g, is not a fundamental constant, but it is often used.

Tasks:

Explore any practical uses of g: in what contexts is it actually important to know g accurately?
Review the connection between g and G, the gravitational constant;
Review the expressions for velocity and acceleration when measured in a non-inertial (typically ‘rotating’) reference frame;
Establish how g depends on altitude and latitude.

31.3 Measuring g through experiments with falling bodies

Starting from Newton’s second law of dynamics, arrive at the differential equation governing free fall of bodies and its solution; include the viscous drag due to air in the differential equation and explore its role. Viscous drag can be modelled as proportional to the velocity of the moving body in the fluid, or to the square of the velocity, depending on the velocity regime: study this problem and establish the law relevant to this experiment.

Look at the practical realization of the experiment and suggest a range of useful measurements to carry out in order to extract g (experimental parameters and conditions to vary); predict possible causes of systematic uncertainties and quantities that may produce largest random uncertainties; estimate number of repetitions needed to arrive at acceptable random uncertainties. Establish the data fitting procedures to extract g and its uncertainty from the experimental data sets.

31.4 Measuring g through experiments with a compound (or physical) pendulum

Theoretical/computational background

Derive and solve the differential equation for a simple pendulum in the small angle approximation. Now consider the exact solution for the simple pendulum problem, ie for arbitrary – rather than small – angles and investigate ways of evaluating the period of oscillation numerically (this requires exploring how to evaluate elliptic integrals). Include air viscous drag as well and explore how to numerically solve the problem (show the solution as a trajectory in phase space). Modify the differential equations, solutions and results to describe the compound pendulum (a rigid body). Discuss the validity of the results for the compound pendulum, going back to modify any equations if necessary.

Practical work

Precise measurement of g with a pendulum is tricky because the effective length can be difficult to determine accurately. To overcome this problem, it is possible to use a reversible compound pendulum with two fixed knife edge pivot points of precisely known separation. The period of the pendulum about either knife edge can be varied by sliding a mass along the length of the pendulum. When the period about each pivot point is the same, then the effective length, Leff, which is related to g by

$T = 2\pi\sqrt{\frac{L_{eff}}{g}}$,
 
can be shown to be equal to the separation between the two knife edges (Leff = 993.9 ± 0.1 mm). Note that the expression is valid in the small angle approximation.

Study and search the literature on the reversible compound pendulum and formally reproduce the explanation that justifies the use of the distance between knife edges in the expression for the period of oscillation given above.

Once you have the two sets of experimental data showing the periods of oscillation as a function of mass position for oscillations about the two pivot points, deduce g from the period at which the two sets of data intersect. Determine the best way of extracting the value of the period from the experimental data.

Study the effect of the angle of swing on the period for a fixed pendulum configuration to ensure the data are within the range of validity of the equation given above or, if necessary, correct the expression in light of your preliminary theoretical/computational work.
