---
layout: archive
title: "Software"
permalink: /resources/
author_profile: true
toc: true
toc_max_header: 1
---

<div style="text-align: justify;" markdown="1">

The boundaries between structure design, materials, and control are becoming increasingly blurred, and structures with more functionalities are of more significant need. However, the existing commercial packages have a lot of limitations. For example, they require much effort and experience to do the geometric modeling of the bar-string network in popular CAE software such as SolidWorks, Catia, Creo, Ansys, etc. They do not have the most updated research, i.e., Adams, Ansys, and Abaqus cannot handle the statics and dynamics studies of the clustered cable problems. Moreover, one can hardly integrate structure and control design without looking into the math and codes between the different disciplines. Yet, the bottom layer codes are not provided by the commercial software. Plus, we have to look into the insight of each member and let our ideas drive the research path instead of accommodating the tools. Thus, we are working as hard as possible to get all the software available to help engineers and students. The demonstration examples shown here mainly use the tensegrity paradigm, but the theories developed here can also be implemented in other engineering structures and robotics.

<td><figure><img src="{{ site.url }}/images/rffi/plane_rocket_sub.png" width="200"/></figure></td>

We appreciate your interest in our research. We are open and willing to answer any question and appreciate your help improving the software. This Source Code Form is subject to the terms of the Mozilla Public License, v. 2.0. If a copy of the MPL was not distributed with this file, You could obtain one at [http://mozilla.org/MPL/2.0/](http://mozilla.org/MPL/2.0/).


### Modeling of Tensegrity Structures Software ([MOTES](https://github.com/Muhao-Chen/Modeling_of_Tensegrity_Structures_MOTES))

[MOTES](https://github.com/Muhao-Chen/Modeling_of_Tensegrity_Structures_MOTES) provides two categories for analyzing tensegrity structure. Firstly, static analysis provides the minimum mass of the tensegrity structure by optimizing tensile forces in the strings and compressive forces in the bars without external forces (self-equilibrium state) and the presence of given external forces. Secondly, the dynamic analysis uses a second-order matrix differential equation to simulate the dynamics of any complexity of the tensegrity structures. This dynamic model assumes the bars are rigid and strings exhibit linear elastic behavior. Some demos are shown below. 

<figure><img src="{{ site.url }}/images/rffi/motes.png" width="200"/></figure>


<!--<table>
<tr>
<td><figure><img src="{{ site.url }}/images/rffi/habitat_membrane.png" width="200"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/Telescope.png" width="200"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/plate.jpg" width="200"/></figure></td>
</tr>
</table>-->

### Tensegrity Finite Element Method Software ([TsgFEM](https://github.com/Muhao-Chen/Tensegrity_Finite_Element_Method_TsgFEM))

[TsgFEM](https://github.com/Muhao-Chen/Tensegrity_Finite_Element_Method_TsgFEM) allows one to do the subsequent studies, but not limited to the listed items. For statics, 1). Conducting structure equilibrium configuration, prestress design, and stiffness studies. 2). Performing prestress and mechanism modes analysis. 3). Checking stiffness, stability, and robustness regarding the structure prestress, materials, and geometric information. 4). Conducting studies on form-finding of tensegrity systems. 5). Simulating the forced motion of structures. 6). Studying the feasibility of pseudo-static deployment trajectories. For dynamics: 1). Rigid body dynamics with acceptable errors by setting relatively high bar stiffness. 2). FEM dynamics simulation with elastic or plastic deformations in various boundary conditions, such as fixing any nodes in any direction or applying static or dynamic external forces (i.e., gravitational force, some specified forces, or random seismic vibrations). 3). Modal analysis, including natural frequency and corresponding modes. 4). An interface towards structural control by a compact state-space form of a linear model. Some demos are shown below. 

<table>
<tr>
<td><figure><img src="{{ site.url }}/images/rffi/cable_dome.gif" width="100px" height="100px"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/net.gif" width="100px" height="100px"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/Jansen.gif" width="100px" height="100px"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/ball.gif" width="50px" height="100px"/></figure></td>
</tr>
</table>

### Origami and Tensegrity Equilibrium and Form-finding Analysis ([OriTsgEFA](https://github.com/Muhao-Chen/Origami_and_Tensegrity_Equilibrium_and_Form-finding_Analysis_OriTsgEFA))

[OriTsgEFA](https://github.com/Muhao-Chen/Origami_and_Tensegrity_Equilibrium_and_Form-finding_Analysis_OriTsgEFA) offers a comprehensive framework for modeling and analyzing both origami and tensegrity paradigms as a unified system. The software's capabilities extend to various types of static analyses, including (1). Load analysis, accommodating both elastic and plastic deformations in bars and strings. (2). Analysis of both infinitesimal and large-scale deformations. (3). Versatility in handling diverse boundary conditions, such as fixed points or nodes subjected to various types of static loads in any given direction—gravitational forces, specified forces, or moments. (4). Stiffness analysis featuring eigenvalue computations and mode shapes. By providing nuanced insights into structural integrity, material properties, and overall performance, this software enhances our capacity to design and deploy large-scale, multifaceted structures. Some demos are shown below. 

<table>
<tr>
<td><figure><img src="{{ site.url }}/images/rffi/01_origami_finger.gif" width="100px" height="100px"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/02_A_Mirua.gif" width="100px" height="100px"/></figure></td>
<!-- <td><figure><img src="{{ site.url }}/images/rffi/03_origami_kresling.gif" width="100px" height="100px"/></figure></td> -->
<td><figure><img src="{{ site.url }}/images/rffi/04_shelter.gif" width="50px" height="100px"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/05_Kresling_with_string.gif" width="50px" height="100px"/></figure></td>
</tr>
</table>

### Tensegrity Foil Design & Analysis Software (TsgFoil)

TsgFoil is software for foil-related studies, such as airfoils, airplane wings, hydrofoils, fish, manta rays, etc. One can: 1). Design tensegrity morphing airfoil and wings based on the [NACA airfoil database](http://airfoiltools.com/search/index?m%5Bgrp%5D=naca4d&m%5Bsort%5D=1). 2). Study structure statics, i.e., prestress, materials, stability, etc. 3). Perform structure and fluid dynamics. 4) Do nonlinear, linear, model-based, and data-based morphing control. 5). Economic sensor and actuator selection. Some of the demos are shown below. 

<table>
<tr>
<td><figure><img src="{{ site.url }}/images/rffi/tensegfoil2.png" width="50px" height="50px"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/foil_ctrl_fluid.gif" width="100px" height="100px"/></figure></td>
</tr>
</table>

One can also add mass-efficient cover structures to the lightweight wing design.  

<figure><img src="{{ site.url }}/images/rffi/Dbar_airfoil.png" width="200"/></figure>



<!--
<table>
<tr>
<td>
<figure><img src="{{ site.url }}/images/rffi/foil_complex.png" width="100"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/morph_air.gif" width="200"/></figure>
<figure><img src="{{ site.url }}/images/rffi/morph_fluid.gif" width="200"/></figure>
</td>
</tr>
</table>-->

<!--
<table>
<tr>
<td>
<figure><img src="{{ site.url }}/images/rffi/foil_complex.png" width="100"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/morph_air.gif" width="400"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/morph_fluid.gif" width="400"/></figure>
</td>
</tr>
</table>
-->

### Tensegrity with Arbitrary Shape of Rigid Bodies Software (TsgRgd)

TsgRgd allows one to 1). Conduct structure equilibrium configuration, prestress design, and stiffness studies. 2). Perform prestress and mechanism modes analysis. 3). Check stiffness, stability, and robustness regarding the structure prestress, materials, and geometric information. 4). Conduct studies on form-finding of rigid body tensegrity systems. 5). Simulate the forced motion of structures. 6) Study the feasibility of pseudo-static deployment trajectories. It is also shown that the rigid body tensegrity system yields the pure string-bar one without rigid bodies. Some demos are shown below.

<figure><img src="{{ site.url }}/images/rffi/tsgrbd.png" width="200"/></figure>

### Tensegrity System Fluid-Structure Interaction Software (TsgFSI)

TsgFSI is a general software for FSI studies. It allows one to 1). Conduct a study of nonlinear tensegrity dynamics in fluids. 2). Ideal, in-incompressible, nonviscous flow on the structure surface. 3). Dynamics of structure with skin in fluids. Some demos are shown below.

<!--<figure><img src="{{ site.url }}/images/rffi/tsgrbd.png" width="200"/></figure>-->

### Clustered Tensegrity Structure Statics, Dynamics, and Control Software (CtsSDC)

Clustered Tensegrity Structure (CTS) can significantly reduce the number of actuators and sensors, offering scalable actuation energy and simplifying the assembly process, especially for soft robots and large-span deployable structures. CtsSDC allows one to conduct statics, dynamics, control, and clustering strategies for any clustered tensegrity structures. Some demos are shown below.

<figure><img src="{{ site.url }}/images/rffi/ctssdc.png" width="200"/></figure>

### Structure Passive Control and Robustness Design subject to Extreme Environments Toolbox (PsvRbst)

PsvRbst allows one to conduct structure passive control and robustness study of any engineering structures subject to extreme environmental events, such as strong winds, heavy rains/snows, large ocean currents, violent earthquakes, giant tsunamis, and significant impact loads. That is, the disturbance signal can be in any form. PsvRbst can help engineers do structure passive control for disturbance rejection and construction material selection by designing the structure's mass, stiffness, and damper in an integrated approach. Some demos are shown below.


### Control Toolbox for Structures and Robotics (CtrlBox)

CtrlBox has the following options for active control of deployable structures and robotics. 1). Nonlinear model-based control for nonlinear dynamics. 2). Linear model-based covariance control. 3). Q-Markov Data-based Control. 4). Model-based and data-based LQG controller. 5). Central pattern generator (CPG) controller. 6). Optimal sensor and actuator selection algorithms for nonlinear and linear models. 7) Information architecture (design pool of control energy, budget, and performance). Some demos are shown below.

<table>
<tr>
<td><figure><img src="{{ site.url }}/images/rffi/curve_front.gif" width="100"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/curve_side.gif" width="100"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/slope_front.gif" width="100"/></figure></td>
<td><figure><img src="{{ site.url }}/images/rffi/slope_side.gif" width="100"/></figure></td>
</tr>
</table>

<!--<figure><img src="{{ site.url }}/images/rffi/tsgrbd.png" width="200"/></figure>-->


### Tensegrity Structure Toolboxes (TsgBox)

TsgBox can help one model and run HPRC (High-Performance Research Computing), get statics, dynamics, and control reports, and generate animations of tensegrity structures concisely. We also provide interfaces and solutions to other CAE software such as [ABAQUS](https://www.3ds.com/products-services/simulia/products/abaqus/), [Adams](https://www.mscsoftware.com/product/adams), [ANSYS](https://www.ansys.com/), [FreeCAD](https://www.freecadweb.org/), [RFEM](https://www.dlubal.com/en-US/products/rfem-fea-software/what-is-rfem), [MuJoCo](https://mujoco.org/), [SolidWorks](https://www.solidworks.com/), [ZW3D](https://www.zwsoft.com/product/zw3d), etc. As for the hardware realization, we include a set of class-k joint designs and 3D printing techniques for various hard & soft filaments and photosensitive resin materials, for example, from [Flashforge](https://www.flashforge.com/product-detail/flashforge-hunter-dlp-3d-printer-dental-impression-jewelry-printing). Some demos are shown below. 

<td><figure><img src="{{ site.url }}/images/rffi/tsgbox.png" width="200"/></figure></td>

</div>