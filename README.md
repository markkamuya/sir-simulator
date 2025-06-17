# Particle-Based SIR Model Simulation

## Overview 
This simulation models the spread of an infection among a population of particles (representing people) within a building environment with elevators, floors, and lobbies. The particles move, interact, get infected, recover, and develop immunity, with the immunity eventually waning over time. The simulation is visualized using `matplotlib`, and the SIR (Susceptible, Infected, Recovered) data is plotted over time.

## Features 
- **Dynamic Particle Movement:** Simulates particle movement through a building, including interactions with elevators, lobbies, and staircases.
- **Infection Spread:** Particles can spread infection to others within a defined radius. Infection spread is probabilistic, based on a defined infection rate.
- **Immunity and Recovery:** Particles can recover from infection, developing immunity that decays over time.
- **Visualization:** Movement and status (susceptible, infected, recovered) of each particle is visualized on a 2D plot. The simulation tracks the number of susceptible, infected, and recovered particles over time.
- **Unit Testing:** The model includes unit tests for particle movement, infection, and recovery, achieving a 75% success rate.

## Installation
To run this simulation, ensure you have Python 3.x installed. Install the required dependencies using `pip`:

```bash
pip install numpy matplotlib
