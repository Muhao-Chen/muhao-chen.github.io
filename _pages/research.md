---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
toc: true
---

<div style="text-align: justify;" markdown="1">


## Research Goal
The existing design approaches mainly deal with what is sufficient rather than necessary, locked into the classical thinking of component technology. That is, design the structure first, followed by material studies and fluid analysis, and add control and signal processing later. The critical question that we ask is whether dramatic performance improvements are possible by combining different disciplines as a communal pool of resources such that engineers in different disciplines have more freedom and can talk to each other in the design space to solve a joint optimization problem. Our research aims to exploit the integration of disciplines for better performance with fewer resources required of various engineering systems.  


We would also like to develop and offer more and more software and tools to help engineers knit efficient structures that physics and their imagination allow and motivate students to study structure and control more fundamentally. All the source codes can be found on the [Software](https://muhao-chen.github.io/resources/) page. 

## Research Interests
 * Integrating Structure and Control Design for Modeling and Control of Complex Deployable Systems
 * Lightweight Automated System (i.e., by Tensegrity, Origami) for Space, Land, Air, and Ocean Applications
 * Robotics, Reinforcement Learning, System Identification, Model Reduction, Sensor & Actuator Selections
 * Data-Driven Control, Path Planning, Finite Bit Computing of High-Dimensional (FEM, FSI, Real-time Control) Systems

<!--
## Research Keywords
* Integrating Structure & Control Design    
* Robotics & Lightweight Automated System
* Tensegrity and Origami Systems
* Space Systems and Deployable Infrastructures
* Dynamics & Control Theory, Reinforcement Learning    
--> 

<!--
## Research Interests

-----
### Integrating Structure & Control Design    
* Objective: Using the least amount of resources (structure mass, damper, control energy, sensors & actuators, and computational efforts) to achieve the required performance (stiffness, control objective, accuracy bound, safety and redundancy, and robustness)   
* Critical problems: Nonlinear and linearized dynamics and control, resource allocation algorithms, theories of integrated disciplines  

### Robotics & Lightweight automated system (i.e., by tensegrity, origami)
* Design: Lightweight structure design, deployment planning, actuation, and sensing strategy 
* Control: Data-based & model-based nonlinear and linear control, covariance control, obstacle avoidance, and path planning
* Signal processing: optimal sensor & actuator selection algorithm for nonlinear and linear systems, optimal simulation model, finite precision simulation


### Tensegrity and Origami Systems
* Tensergity and Origami solutions to the five fundamental problems in engineering mechanics: compression, tension, torsion, cantilever, simply supported
* Statics: Form-finding algorithms, structure topology optimization, minimal mass design subject to local and global failures
* Dynamics: The dynamics of the pure bar-string network, clustered tensegrity, origami, and tensegrity with arbitrary objects (non-rigid and rigid bodies)
* Applications: Wings and hydrofoils, space habitats, lunar towers, cable domes, robotic dolphins, robotic grippers, etc.

### Dynamical and Control Theory
* Data-driven control, path planning, finite bit computing of high-dimensional (FEM/FSI) systems
* Multibody dynamics, rigid and non-rigid body, nonlinear and linearized dynamics with arbitrary shape objects, and modal analysis      
* Structure redundancy, uncertainty, and robustness, FSI dynamics 
* Fluid-structure dynamics, structure under extreme fluid loading conditions, biomimetic structure designs, soft actuation strategy, and control
* Applications: rescue shelters, fish and hydrofoils, etc.

### Space Systems
* Lightweight and deployable structure solutions for the deep space explorations    
* Applications: space habitat design, Moon & Mars towers, drilling rigs, antennas, etc.

-->

<!--A misconception is that "The best system is made from the best components." That is certainly not true. Often, we gain more in integrating two disciplines than in making exceptional improvements in one discipline. For example, aerodynamics engineers first designed the best shape in the airplane wing based on their knowledge of fluid dynamics. The control engineer came and broke the beautiful shape for control objectives. This is certainly not the right way. A systematic approach would be to modify the shape not by pushing against a reference equilibrium but by modifying the equilibrium. Of course, this would require much less control effort. -->

<!--{% include toc %}-->


<!--Industrial discussion: Patterson-UTI-->


<!-- <br />
<img align="center" width="800" src="{{ site.url }}/images/rffi/RFF_identification_procedure.png" alt="...">
<br />-->



## Research Demonstrations

All my research mainly focuses on three topics: 1) Integrating Structure and Control Design, 2) Deployable Automated Systems and Robotics, and 3) Lightweight Infrastructures. Here are a few examples. 

### Dynamic Reference Tracking and Obstacle Avoidance Control Based on Reinforcement Learning  
<!-- (with Dr. Robert E. Skelton) -->
(Muhao Chen and Robert E. Skelton)


<table>
<tr>
<td><figure><img src="{{ site.url }}/images/rffi/T2D1_circling.gif" width="100px" height="100px"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/T2D1_tracing_obstacle_avoidance.gif" width="100px" height="100px"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/prism_pointing.gif" width="100px" height="100px"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/prism_obstacle_avoidance.gif" width="50px" height="100px"/></figure></td>
</tr>
</table>

<!--
### Integrated Tensegrity and Origami Systems  
(with Drs. Shuo Ma and Robert E. Skelton)
-->

### Mass Efficient Double-Helix Tensegrity and Origami
<!-- (with Drs. Manoranjan Majji and Robert E. Skelton) -->
(Muhao Chen, Manoranjan Majji, and Robert E. Skelton)


<figure><img src="{{ site.url }}/images/rffi/DHT.png" width="800"/></figure>



### Model-Based and Data-Based Shape Control of Tensegrity Structures
<!-- (with Dr. Robert E. Skelton) -->
(Muhao Chen and Robert E. Skelton)



<table>
<tr>
<td><figure><img src="{{ site.url }}/images/rffi/morph_air.gif" width="100"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/tail.gif" width="100"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/CableDomeCtrl.gif" width="100"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/arm.gif" width="100"/></figure></td>
</tr>
</table>

### Automated Drilling Rig
<!-- (with Arturo Lopez Nava Jr., Alkassoum Toure, Salim Al Kharsa, Tom Nan, Ran Wang, Luis A Rodriguez, Drs. Mohamed S Khaled, Enrique Z Losoya, Eduardo Gildin, Robert E. Skelton, Sam Noynaert, and George Moridis) -->
(Mohamed S Khaled, Muhao Chen, Enrique Z Losoya, Arturo Lopez Nava Jr., Alkassoum Toure, Salim Al Kharsa, Tom Nan, Ran Wang, Luis A Rodriguez, Eduardo Gildin, Robert E. Skelton, Sam Noynaert, and George Moridis)


<figure><img src="{{ site.url }}/images/rffi/rig.png" width="800"/></figure>


<!--
### Locomotion of A Tensegrity Spherical Robot 
(with Dr. Robert E. Skelton)
-->



### Economic Sensor & Actuator Selection for Tensegrity Robots Based on the Information Architecture
<!-- (with Dr. Robert E. Skelton) -->
(Muhao Chen, Manoranjan Majji, Robert E. Skelton)

<figure><img src="{{ site.url }}/images/rffi/sas.png" width="800"/></figure>


### Finite-Word Length Optimal Simulation for High-Dimensional Dynamical Systems
<!-- (with Drs. Yuling Shen and Robert E. Skelton) -->
(Muhao Chen, Yuling Shen, and Robert E. Skelton)


<figure><img src="{{ site.url }}/images/rffi/model_error.png" width="800"/></figure>


### Robust $\mathcal{L}_{\infty}$ Performance for Structure Passive Control
<!-- (with Dr. Robert E. Skelton) -->
(Muhao Chen and Robert E. Skelton)

<figure><img src="{{ site.url }}/images/rffi/Passive_ctrl.png" width="800"/></figure>


### Model Reduction Analysis for Nonlinear Tensegrity Systems
(Muhao Chen and Robert E. Skelton)   

<figure><img src="{{ site.url }}/images/rffi/model_reduction.png" width="800"/></figure>

<!-- ### System Identification to Nonlinear Tensegrity Structures
(Muhao Chen and Robert E. Skelton)   
<figure><img src="{{ site.url }}/images/rffi/system_id.png" width="800"/></figure> -->



### Growable Space Habitat with 1G Artificial Gravity in Deep Space
<!-- (with Anthony Longman, Drs. Raman Goyal, Yuling Shen, Manoranjan Majji, Robert E. Skelton, Joel Sercel, Jane Shevtsov) -->
(Muhao Chen, Raman Goyal, Yuling Shen, Manoranjan Majji, Robert E. Skelton, Joel Sercel, Jane Shevtsov, and Anthony Longman)

<figure><img src="{{ site.url }}/images/rffi/habitat.png" width="800"/></figure>


### Deployable Tensegrity Roof with Covers
<!-- (with Drs. Shuo Ma and Robert E. Skelton) -->
(Shuo Ma, Muhao Chen, and Robert E. Skelton)
<figure><img src="{{ site.url }}/images/rffi/Tenseg_Roof.png" width="800"/></figure>


### Low-Cost, Lightweight, Deployable Shelter subject to Extreme Environments
<!-- (with Dr. Robert E. Skelton) -->
(Muhao Chen and Robert E. Skelton)

<table>
<tr>
<td><figure><img src="{{ site.url }}/images/rffi/shelter.png" width="100"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/shelter_windlinear_elastic_slack_1.gif" width="100"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/shelter_womemlinear_elastic_slack_1.gif" width="100"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/shelter.gif" width="50"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/shelter_windstreamlines1.gif" width="50"/></figure></td>
</tr>
</table>
shelter


### Minimal Mass Design for Clustered Tensegrity 
<!-- (with Xiaoling Bai, Dr. Robert E. Skelton) -->
(Muhao Chen, Xiaolong Bai, and Robert E. Skelton)


<figure><img src="{{ site.url }}/images/rffi/clu_min.png" width="800"/></figure>


### Electromagnetic Lunar Launcher
<!-- (with Drs. Xiaowen Su, Manoranjan Majji, Robert E. Skelton) -->
(Xiaowen Su, Muhao Chen, Manoranjan Majji, and Robert E. Skelton)


<figure><img src="{{ site.url }}/images/rffi/propulsion.png" width="800"/></figure>

### Energy-Efficient Cable-actuation Strategies of the V-Expander Tensegrity 
<!-- (with Drs. Aguinaldo Fraddosio, Andrea Micheletti, Gaetano Pavone, Mario Daniele Piccioni, and Robert E. Skelton) -->
(Muhao Chen, Aguinaldo Fraddosio, Andrea Micheletti, Gaetano Pavone, Mario Daniele Piccioni, and Robert E. Skelton)

<figure><img src="{{ site.url }}/images/rffi/V_Expander.png" width="800"/></figure>


### Tensegrity System Dynamics in Fluids
<!-- (with Drs. Shuo Ma, Zhangli Peng, Xingfei Yuan, Robert E. Skelton) -->
(Muhao Chen, Jun Chen, Manoranjan Majji, and Robert E. Skelton)

<table>
<tr>
<td><figure><img src="{{ site.url }}/images/rffi/prism1.gif" width="80"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/prism2.gif" width="80"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/prism3.gif" width="80"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/land1.gif" width="80"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/land2.gif" width="80"/></figure></td>
</tr>
</table>


### Rigid Body Tensegrity
<!-- (with Drs. Shuo Ma, Zhangli Peng, Xingfei Yuan, Robert E. Skelton) -->
(Shuo Ma, Muhao Chen, Zhangli Peng, Xingfei Yuan, and Robert E. Skelton)


<figure><img src="{{ site.url }}/images/rffi/BallSpine.png" width="800"/></figure>

### Double-Helix Tensegrity Spherical Planetary Lander
<!-- (with Dr. Robert E. Skelton) -->
(Muhao Chen and Robert E. Skelton)


<figure><img src="{{ site.url }}/images/rffi/lander.png" width="800"/></figure>

### Gyroscopic Tensegrity System Dynamics
<!-- (with Drs. Xiaowen Su, Manoranjan Majji, Robert E. Skelton) -->
(Raman Goyal, Muhao Chen, Manoranjan Majji, and Robert E. Skelton)      
<figure><img src="{{ site.url }}/images/rffi/gyro.png" width="800"/></figure>


### Deployable Lightweight Tensegrity Cable Net
<!-- (with Drs. Shuo Ma and Robert E. Skelton) -->
(Shuo Ma, Muhao Chen, and Robert E. Skelton)

<figure><img src="{{ site.url }}/images/rffi/cable_roof.png" width="800"/></figure>

### Deployable Clustered Cable Nets
<!-- (with Kai Lu, Xinzhu Zhou, Drs. Shuo Ma, and Robert E. Skelton) -->
(Shuo Ma, Muhao Chen, and Robert E. Skelton)

<figure><img src="{{ site.url }}/images/rffi/cable_net.png" width="800"/></figure>

<!--
<br />
<img align="center" width="400" src="{{ site.url }}/images/rffi/ball.png" alt="...">
<br />-->

<!--
<figure class="half">
    <img src="{{ site.url }}/images/rffi/ball.png" width="200"/><img src="{{ site.url }}/images/rffi/spine.png" width="200"/></figure>-->
    

### Deployable Cable Domes 
<!-- (with Drs. Shuo Ma, Xingfei Yuan, and Robert E. Skelton) -->
(Shuo Ma, Muhao Chen, Xingfei Yuan, and Robert E. Skelton)

<figure><img src="{{ site.url }}/images/rffi/dome.png" width="800"/></figure>

<!--We are always keen to apply our knowledge to practical applications. Hence we have created several demonstration videos to present our applied research.-->


</div>
