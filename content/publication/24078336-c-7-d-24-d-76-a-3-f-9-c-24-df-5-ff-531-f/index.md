---
title: "CFD modelling and measurements of the atmospheric boundary layer for micrositing of small wind turbines"
date: 2012-04-01
publishDate: 2020-04-13T05:58:24.047620Z
authors: ["Jochem Vermeir", "Mark Runacres", "Tim De Troyer"]
publication_types: ["6"]
abstract: "1 Introduction A major challenge in numerical siting studies over complex terrain is getting the atmospheric boundary layer right [1]. This boundary layer can be con- structed in two ways: setting a logarithmic wind profile at the inlet boundary, or applying a wall function to the ground to resolve the wind profile above. These two boundary conditions are complementary and can be used together. The difficulty is that these two boundary conditions satisfy different equa- tions. The inlet profile is set by 2 parameters, the friction velocity U? and the roughness length z0. The wall function is also determined by 2 parameters, the roughness height Ks and the roughness constant Cs. They are related by the roughness length z0: as a rule of thumb, Ks = 20z0. The functions described above will be used to demonstrate how the two boundary conditions can be tuned for simultaneous use. This type of rough- ness implementation is currently available in the CFD code OpenFoam 2.0.x. The solver that we use for this paper is SimpleFoam. It is a steady-state solver for incompressible turbulent flow, using a semi implicit method for pressure- linked equations. The solver allows to couple the Navier-Stokes equations with an iterative procedure. The selected Reynolds Averaged Stress (RAS) turbulence model is the k-? model. This paper first deals with the imple- mentation of the atmospheric boundary layer on a flat terrain. The results are then applied to a siting study on an existing terrain. The study is finally validated with on-site measurements. 2 Simulation of the boundary layer The two ways of setting the boundary layer are first studied separately and then applied together, on a flat terrain. Using the wall function only, a uni- form inlet velocity will be turned into a logarithmic wind profile over the surface. The value for the (constant) flow velocity at the inlet is carefully chosen. It is exactly the mean wind velocity of the expected wind profile, so the flow remains constant over the surface. Results show that the error between the simulated profile and the expected profile is less than 5 %. Vari- ation of the roughness constant has a major influence on the error specially for lower heights. A constant value of 0.327 is chosen for Cs, which gives the best result. A second test consists of applying a logarithmic wind profile at the inlet and a slip boundary condition on the surface. The profile at the outlet of the case has exactly the expected profile. Combining both boundary conditions, it should be possible to set up a logarithmic wind profile that remains con- stant when moving over the surface (with wall function applied). If so, both boundary conditions are consistent and representative of the atmospheric boundary layer. A result for this simulation is shown in figure 1, where the wind profile at the outlet is compared with the expected profile (i.e. the profile at the inlet). 3 Siting study in complex terrain After studying both boundary conditions, we have applied them to a siting study on an existing terrain. In this case the complexity of the terrain is due to buildings. Terrain topography such as hills can be treated in the same way. We have measured the terrain with a total station and introduced it in the CFD code as a 3D surface. The first step in this study is to estimate the roughness length of the terrain. Tables with roughness lengths for each type of vegetation, height of and spatial area between buildings are present in the literature [2]. In the next step we have determined the parameters for implementing the boundary layer at the inlet of the case. These are determined by measuring the wind speed at 2 different heights (13 and 15 m) on the same location on the terrain by the use of 2 cup anemometers. The location of the mast should be chosen with care. If a certain wind direction is simulated, the mast should obviously be placed in front of the terrain and the flow should be nearly undisturbed. The measurement period is set to 1 to 2 days. We have chosen this period because an adequate estimate of the parameters has to be made. Therefore a sufficient amount of data should be gathered. Due to the variability of the wind speed and direction at these low heights, a few hours did not suffice to make a good estimate. The parameters can be calculated from these measurements by using the boundary layer equation. These parameters are then set to the inlet, in this way the correct boundary layer is implemented. In figure 2 the results of a simulation for the (dominant) South-West wind direction are shown. The variable that is plotted in the left part of the figure is the wind speed at a height of 15 m. A few interesting zones where the wind is accelerated (from 4 m/s at the inlet to 4,6 m/s) by the characteristics of the terrain can be seen. On the right hand-side of the figure the stream lines are plotted on a height of 15 m to show the turbulent regions above the terrain. 4 Validation The goal of these siting studies is to determine the best location to install a small-scale wind turbine. An important step in the study is the validation of the CFD simulations. The validation of these models is done by comparing the results of the simulations with field measurements. These consist of mea- suring the undisturbed wind velocity on 2 heights (to implement the correct boundary layers at the inlet as described above) and measuring the wind velocity on the terrain. We have chosen the location on the terrain using the results of the simulation. The mast is placed in a zone where the wind speed was accelerated and the turbulence was low. The measurements are then compared with the simulations. The error between the values of the wind speed is nearly 20%. This error may seem large for siting studies in com- plex terrain [3], but when comparing field measurements with wind tunnel experiments in an urban environment this error seems reasonable [4]. Also it should be kept in mind that the validation is done at a height of 15 m where effects such as turbulence and fluctuation of the wind direction on a small time scale will influence the error between the numerical and experimental set-up. This error will certainly have an effect on the estimation of the en- ergy production of a potential wind turbine. However we can conclude from the measurement that the wind does really accelerates in the zone where the mast is installed as was indicated by the simulations. References [1] Blocken B, Stathopoulos T, Carmeliet J. 2007. CFD simulation of the atmospheric boundary layer: wall function problems., Atmospheric Envi- ronment 41(2): 238-252. Elsevier. [2] Wieringa J, 1992. Updating the Davenport roughness classification., Jour- nal of Wind Engineering and Industrial Aerodynamics 41-44, 357-368. Elsevier. [3] Wallbank T, 2008. WindSim validation study, Windsim, Tønsberg, http://tinyurl.com/7xbcdar (November 25, 2011)"
featured: false
publication: "*Proceedings of the EWEA Annual Event, 2012, Copenhagen*"
tags: ["Wind energy", "Siting study", "Complex terrain", "Atmospheric boundary layer", "Roughness", "Computational fluid dynamics", "Validation", "Field measurements"]
---
