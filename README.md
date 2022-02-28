# Nonlinear String Simulation
### Introduction

Nonlinear spring simulation for soft tissues. The tissue data is from 'Modeling and Prediction of Soft Tissue Directional Stiffness using In-Vitro Force-Displacement Data'.



### Function & Data

I have extracted the force-displacement coefficients from the above article, and draw the curves. See code file for more details.



The functions of two categories are follow:


$$
F_I (x) = Σa_i e^{b_i x} \\
F_{II} (x) = Σa_i e^{-({(b_i -x)/c_i})^2} 
$$
  