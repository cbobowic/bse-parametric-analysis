# Magnetorquer Parametric Analysis
This is a parametric analysis done in MATLAB to determine the optimal length and radius of magnetorquer coils.

The Attitude Determination and Control Systems subgroup of Brown Space Engineering was tasked with developing a low-power and low-mass attitude control system with ~10&deg; accuracy for the 3U cubesat PVDx. The group must consider a multitude of constraints, including:

- Mass limitations: PVDx has a maximum mass for launch, which must be shared between all subgroups. ADCS was given a 1.5kg mass budget.
- Power constraints: PVDx is operating with very minimal power. Magnetorquers can only run intermittently, and adhere to voltage and timing constraints.
- Spatial constraints: The system must fit within the satellite, be positioned near the edges, and avoid high voltage wires. 
- Price limitations: Since PVDx is intended to increase accessibility to space, components of the attitude system must be purchased or built at a minimal cost.

Magnetorquers are solenoids that generate a magnetic dipole to position the satellite in a specific direction. Magnetorquers that are longer with larger radii produce greater dipoles, so there are many tradeoffs to consider when selecting a length and radius. This parametric analysis was used to determine possible combinations that yield the desired dipole. 

As of Spring 2023, the team is still working hard for a tentative 2025-2026 launch date! 
