# Wind Tunnel Prototype & CFD Simulation

This repository contains the CAD models, CFD simulation data, and technical documentation for a desktop-scale wind tunnel prototype. The system is designed to generate a controlled, laminar airflow for aerodynamic testing, utilizing a standard vacuum cleaner as the primary flow inducer.

## Project Overview
The physical structure features a converging nozzle to accelerate the flow and minimize pressure losses, followed by lamination valves (honeycomb structures) to suppress turbulence before the airflow reaches the testing chamber. 

## Repository Structure
- **`/Technical Report`**: Contains the PDF documentation detailing the fluid dynamics principles (Continuity Equation, Bernoulli's Principle, blockage effect) and the structural design phase.
- **`/Wind Tunnel Parts`**: Contains all the SolidWorks part files (`.SLDPRT`), including the Nozzle, Testing Chamber, Lamination Valve, Vacuum Sealer, and the car mock-up model.
- **`WindTunnel.SLDASM`**: The main SolidWorks assembly file.
- **`CFDsimulation.mp4`**: A video export of the SolidWorks FloXpress CFD simulation showing velocity profiles and streamlines around the tested model.

## Technical Stack
- **3D Modeling & CFD**: SolidWorks
- **Documentation**: LaTeX 

## Author
**Alessio Nuzzolese**  
Mechanical Engineering Student  
Politecnico di Bari