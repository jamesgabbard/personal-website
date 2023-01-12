---
layout: default
title: Projects
---
TODO:
 - Descriptions for Murphy, SM Thesis, more for 16.930
 - Pictures for 18.337, 18.085, MURPHY
 - Resovle the AIAA SciTech republishing issue - link to paper?
 - Mention core Murphy developer and link to release
 
#### High-Order 3D Immersed Interface Simulations in MURPHY
*MIT PhD Thesis (ongoing)*
[[scitech23]](/assets/AIAA_SciTech_2023_Submission.pdf)

#### Immersed Interface methods for 2D flow simulations
*MIT SM Thesis*
[[article]](https://vanreeslab.mit.edu/wp-content/papercite-data/pdf/gabbard-2022.pdf)
[[poster]](/assets/MERE_Final.pdf)

<img align="left" width="200" src="{{ site.url }}{{ site.baseurl }}/assets/IIM2D_Icon.jpg">
<br clear="left"/>

#### 3D-Var and 4D-Var Assimilation for Dynamic Soft Elastic Structures
*MIT 16.940: Numerical Methods for Stochastic Modeling and Inference*
[[pdf]](/assets/16940_Final_Project.pdf) [[slides]](/assets/16940_Final_Slides.pdf)

<img align="left" width="200" src="{{ site.url }}{{ site.baseurl }}/assets/16940_Elasticity.jpg">
Used variational data assimilation to infer the state of an elastic structure based on noisy observations and a model of the underlying physics.
<br clear="left"/>

#### Performance of Automatic Adjoint Computation for Elastic Structures
*MIT 18.337: Parallel Computing and Scientific Machine Learning*
[[pdf]](/assets/18337_Final_Project.pdf) [[code]](https://github.com/jamesgabbard/DiscreteElasticRods.jl)

Implemented and heavily optimized the Discrete Elastic Rods (DER) model in Julia, then assessed the performance of existing forward and reverse mode automatic differentiation packages for calculating gradients and Hessians of the DER elastic energy function.

#### A Hybridized Discontinuous Galerkin Method for Linear Elastodynamics
*MIT 16.930: Advanced Numerical Methods for PDEs*.
[[slides]](/assets/16930_Final_Project.pdf)

<img align="left" width="200" src="{{ site.url }}{{ site.baseurl }}/assets/16930_MatrixStructure.jpg">
Formulated and implemented an HDG discretization of 2D linear elasticity for both static and dynamic problems. Verified the resulting code on canoncial problems in elasticity: bending of beams and elastic waves in homogeneous and inhomogeneous media.
<br clear="left"/>

#### From scratch implementation of Deep-Q Reinforcement Learning
*MIT 18.085: Computational Science and Engineering I*
[[pdf]](/assets/18085_Project_final.pdf) [[slides]](/assets/18085_Final_Slides.pdf)

Implemented a feedforward neural network, backpropagation, the ADAM optimizer, and a Deep-Q reinforcement learning framework to control a cart-pole system. 



