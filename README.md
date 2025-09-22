# Turbulent-Duct-Flow-Multi-Reynolds-CFD
This project performs comprehensive CFD analysis of turbulent flow within a rectangular duct using various Reynolds numbers. The study aims to investigate flow characteristics, validate turbulence models, and analyze the effects of Reynolds number variation on flow behavior using Computational Fluid Dynamics methodologies.

<img width="1031" height="851" alt="image" src="https://github.com/user-attachments/assets/13ca7357-5fc1-4039-abf2-6ad1a623bf62" />



# Geometry Configuration

Geometry Type: 3D Rectangular Duct

Channel Configuration: Straight rectangular cross-section

Dimensions:

Length: L (streamwise direction)

Width: W (span-wise direction)

Height: H (wall-normal direction)


Aspect Ratio: W/H (to be specified based on study requirements)

Coordinate System: x (streamwise), y (wall-normal), z (span-wise)

# Analysis Methodology
Reynolds Number Investigation

The study encompasses multiple Reynolds numbers to capture different flow regimes:

Low Re: Transitional flow characteristics

Medium Re: Fully developed turbulent flow

High Re: High Reynolds number effects

Re Definition: Based on hydraulic diameter and bulk velocity

# Flow Physics Analysis Components
1. Velocity Profile Analysis

Centerline Velocity Distribution: Streamwise velocity development

Cross-sectional Velocity Profiles: Detailed velocity mapping

Secondary Flow Patterns: Corner vortex formation and behavior

2. Turbulent Flow Characteristics

Turbulent Kinetic Energy (TKE): Spatial distribution and magnitude

Reynolds Stresses: All six components of Reynolds stress tensor

Energy Dissipation Rate: Turbulent energy cascade analysis

Turbulent Viscosity: Effective viscosity distributions

3. Wall Effects & Boundary Layer Analysis

Near-Wall Behavior: Viscous sublayer, buffer zone, log-law region

Wall Shear Stress: Surface friction distribution

Boundary Layer Development: Growth along duct length

Corner Effects: Secondary flow in rectangular cross-section

4. Pressure Analysis

Pressure Drop: Friction factor calculations

Static Pressure Distribution: Axial and cross-sectional variations

Pressure Recovery: Downstream flow development

Loss Coefficients: Engineering correlation development
# Results and Conclusion

<img width="886" height="472" alt="image" src="https://github.com/user-attachments/assets/f44374cd-64ba-40d8-82e4-c821c7cee5dc" />

Near the wall, viscous stresses dominate over Reynolds stresses because the random velocity fluctuations are reduced in this region. This area is referred to as the inner layer. Moving away from the wall, the amplitude of turbulent fluctuations increases and Reynolds stresses become dominant; this region is called the outer layer. Between these two regions, there is an overlap layer, where both stresses are of comparable magnitude. Understanding these layers and the fluid behavior in each region is one of the most important aspects of flow analysis.


<img width="886" height="472" alt="image" src="https://github.com/user-attachments/assets/bab811ea-6709-4651-83ca-4123f3a848f8" />

Near the wall, viscous effects dominate. At the wall itself, the shear stress reaches its maximum value, denoted as 𝜏wall . As expected, the Reynolds stress at this point is zero (no-slip condition). Moving away from the wall, turbulent effects and momentum increase, while the influence of wall viscosity decreases. Consequently, Reynolds stresses gradually become dominant, and the viscous stress approaches zero. At the center of the channel, all shear stresses, both Reynolds and viscous, are zero, leaving only the normal stress. Overall, the channel center corresponds to the location of minimum total shear stress.
