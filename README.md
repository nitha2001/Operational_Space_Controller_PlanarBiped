# Operational Space Control for a Planar Biped Robot
This repository contains the implementation of Operational Space Control (OSC) for a planar biped robot. The goal is to track the center of mass, torso angle, and swing foot position while maintaining balance.

## Project Overview
This project designs an OSC framework that includes:

- Task-Space Tracking: Center of mass, torso angle, and swing foot position.
- Contact Constraints: Zero acceleration on the stance foot.
- Friction Constraints: Prevent foot slipping by enforcing linear inequality constraints.

## Relevant Files:

- `osc.py`: Implements the OSC formulation, task-space objectives, and constraints.
- `osc_tracking_objective.py`: Defines objectives like center of mass and foot tracking.
  
## Key Concepts
- OSC: Controls the robot in task space (center of mass, foot position) rather than joint space.
- Quadratic Programming: The OSC is formulated as a constrained optimization problem (QP).

  ## Usage

- Implement the task tracking objectives in `osc_tracking_objective.py`.
- Modify constraints and robot parameters in `osc.py`.
- Run `osc_sim.py` to visualize the biped’s walking behavior.

  ## Results

  
  
