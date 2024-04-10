---
layout: default
title: Projects
---
## Projects
#### High-Order 3D Immersed Interface Simulations in MURPHY
*MIT PhD Thesis (ongoing)*
[[scitech23]]({{ site.baseurl }}/assets/Gabbard_AIAA_SciTech_2023.pdf){:target="_blank"}

<img align="left" width="200" src="{{ site.url }}{{ site.baseurl }}/assets/MurphyIcon.jpg">
My ongoing thesis project, developing high-order numerical methods that don't require mesh generation. Currently the numerics include third order methods for advection and up to sixth order methods for diffusion, all implemented in [MURPHY (a C++ framework for adaptive multiresolution grids)](https://www.murphy-code.dev/). 
<br clear="left"/>

#### Lattice Green's Functions for High Order Finite Difference Stencils
*MIT Research Project*
[[ExpandLGF.jl]](https://github.com/vanreeslab/ExpandLGF.jl){:target="_blank"}
[[article]](https://vanreeslab.mit.edu/wp-content/papercite-data/pdf/gabbard-2024.pdf){:target="_blank"}

<img align="left" width="200" src="{{ site.url }}{{ site.baseurl }}/assets/LGFicon.png">
A personal project in the field of numerical analysis, numerically evaluating a set of difficult integrals that define the fundamental solutions to discretized elliptic PDEs. The Julia code linked above uses a combination of symbolic computation and numerical quadrature to evaluate these fundamental solutions orders of magnitude faster than existing methods.
<br clear="left"/>


#### Immersed Interface methods for 2D flow simulations
*MIT SM Thesis*
[[article]](https://vanreeslab.mit.edu/wp-content/papercite-data/pdf/gabbard-2022.pdf){:target="_blank"} 
[[poster]]({{ site.baseurl }}/assets/MERE_Final.pdf){:target="_blank"}

<img align="left" width="200" src="{{ site.url }}{{ site.baseurl }}/assets/IIM2D_Icon.jpg">
Developed a vorticity-based flow solver in C++ for 2D flows with moving immersed bodies. The discretization addresses challenges that arise in the vorticity formulation when there are multiple bodies or outflow, and the implementation allows for thread-based parallelism.
<br clear="left"/>

#### 3D-Var and 4D-Var Assimilation for Dynamic Soft Elastic Structures
*MIT 16.940: Numerical Methods for Stochastic Modeling and Inference*
[[pdf]]({{ site.baseurl }}/assets/16940_Final_Project.pdf){:target="_blank"} 
[[slides]]({{ site.baseurl }}/assets/16940_Final_Slides.pdf){:target="_blank"}

<img align="left" width="200" src="{{ site.url }}{{ site.baseurl }}/assets/16940_Elasticity.jpg">
Used variational data assimilation to infer the state of an elastic structure based on noisy observations and a model of the underlying physics. The assimilation algorithm is based on the 4D-Var fromulation often used in weather forecasting, and the elastic model is based on Discrete Elastic Rods.
<br clear="left"/>

#### A Hybridized Discontinuous Galerkin Method for Linear Elastodynamics
*MIT 16.930: Advanced Numerical Methods for PDEs*.
[[slides]]({{ site.baseurl }}/assets/16930_Final_Project.pdf){:target="_blank"}

<img align="left" width="200" src="{{ site.url }}{{ site.baseurl }}/assets/16930_MatrixStructure.jpg">
Formulated and implemented an HDG discretization of 2D linear elasticity for both static and dynamic problems. Verified the resulting code on canoncial problems in elasticity: bending of beams and elastic waves in homogeneous and inhomogeneous media.
<br clear="left"/>

#### Performance of Automatic Adjoint Computation for Elastic Structures
*MIT 18.337: Parallel Computing and Scientific Machine Learning*
[[pdf]]({{ site.baseurl }}/assets/18337_Final_Project.pdf){:target="_blank"} 
[[code]](https://github.com/jamesgabbard/DiscreteElasticRods.jl){:target="_blank"}

Implemented and heavily optimized the Discrete Elastic Rods (DER) model in Julia, then assessed the performance of existing forward and reverse mode automatic differentiation packages for calculating gradients and Hessians of the DER elastic energy function.

#### From scratch implementation of Deep-Q Reinforcement Learning
*MIT 18.085: Computational Science and Engineering I*
[[pdf]]({{ site.baseurl }}/assets/18085_Project_final.pdf){:target="_blank"} 
[[slides]]({{ site.baseurl }}/assets/18085_Final_Slides.pdf)

Implemented a feedforward neural network, backpropagation, the ADAM optimizer, and a Deep-Q reinforcement learning framework to control a cart-pole system. 



