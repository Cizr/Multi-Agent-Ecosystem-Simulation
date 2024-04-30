# Multi-Agent Ecosystem Simulation

## Description
This repository contains a multi-agent ecosystem simulation developed using NetLogo, a modeling environment tailored for simulating natural and social phenomena. The simulation models the interactions between different agents in a simplified ecosystem, including cows, lions, a bull, and a dog.

## NetLogo Overview
NetLogo is a modeling environment ideal for studying complex systems evolving over time. It enables modelers to direct numerous independent “agents” simultaneously, allowing exploration of how individual behaviors relate to larger-scale emergent patterns. In NetLogo, agents can be turtles, observer, patches, or links, each with distinct capabilities and roles within the simulation.

- **Turtles**: Capable of movement within the simulation world, turtles can freely navigate the grid of patches.
- **Observer**: Provides instructions and guidance to other agents in the simulation without a physical location within the world.
- **Patches**: Represent the grid squares in the simulation world, serving as the environment over which turtles traverse. Patches can also create new turtles.
- **Links**: Connect pairs of turtles within the simulation, relying on the locations of the turtles they connect.

Procedures in NetLogo allow users to instruct agents using commands and reporters. Commands initiate actions for agents, while reporters provide instructions for computing values. Variables serve as containers for storing values within agents, categorized into global, turtle, patch, or link variables.

## Our Goal (Creation of a Multi-Agent Base System)
Our system is a multi-agent-based simulation environment built in NetLogo, simulating the dynamics of an ecosystem with grass patches, cows, lions, a bull, and a dog. The simulation aims to provide a platform for studying agent interactions and ecosystem dynamics.

## How to Use NetLogo
1. **Installation**: Download and install NetLogo from the [official website](https://ccl.northwestern.edu/netlogo/).
2. **Model Creation**: Define agents, procedures, and variables to create the desired simulation.
3. **Setup Procedures**: Initialize the simulation environment, agents, and variables using setup procedures.
4. **Simulation Execution**: Run the simulation to observe agent interactions and emergent behaviors.

## Simulation Features
- **Agent Movement**: Each agent moves randomly within the environment, with different behaviors for cows, lions, and the bull.
- **Predator-Prey Interactions**: Lions hunt and consume cows for food, while the bull and cows graze on grass patches.
- **Growth and Consumption of Grass**: Grass patches grow over time and are consumed by grazing animals.
- **Dog-Lion Interaction**: Dogs may engage in fights with lions to protect the ecosystem, with varying outcomes.
  
## Read More
You can read more about this simulation and its development process [here]([https://medium.com/multi-agent-ecosystem-simulation](https://medium.com/@benkaddourmed54/creating-a-multi-agent-base-system-with-netlogo-e0556eef8357)).

## Example Usage
- Study the dynamics of predator-prey interactions in an ecosystem.
- Explore the effects of different parameters, such as the number of lions or the growth rate of grass, on ecosystem stability.

## License
This project is licensed under the [MIT License].
