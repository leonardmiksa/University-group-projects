# University-group-projects

### Automated Greenhouse Climate Control (TIA Portal)

This project involved modeling, simulating, and visualizing an automated climate control system for a smart greenhouse using Siemens TIA Portal.  
It was developed as part of the course *Automatizacija postrojenja i procesa (Plant and Process Automation)*.

**Project collaborators:** Marina Branilović, Jazz Richard Greblo, Leonard Mikša

Key features:
- PID control of greenhouse temperature
- Control of air humidity, soil moisture, and light intensity
- Simulation of external disturbance (outside temperature) modeled by a sinusoidal generator
- Ladder Logic programming of controllers and actuators (HVAC, humidifiers, irrigation, LED lighting)
- Human-Machine Interface (HMI) design for monitoring, manual setpoint input, and alarm states
- Animation of crop ripening, harvesting, and spoilage based on environmental conditions

Tools used:
- Siemens TIA Portal
- Simatic S7-1200
- Simatic KTP700 Basic Panel

The final system was fully simulated in TIA Portal with a functional HMI and dynamic process visualization.

Notes:  
> While the system worked perfectly during laboratory simulations on a Siemens S7-1200 PLC, the implementation as designed would be heavily impractical for real-world deployment due to the control logic
> All the flaws for real-world implementation are extensively described in the project report (University-group-projects/report_greenhouse_control.pdf)
> **The project remains an academic exercise in modeling, control, and automation logic development**


---


