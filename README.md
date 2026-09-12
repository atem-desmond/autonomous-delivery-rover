# Autonomous Delivery Rover

A personal mechatronics project focused on designing and building an autonomous indoor mobile robot capable of transporting a small payload between predefined locations while detecting and avoiding obstacles.

> **Project Status:** 🟡 Planning / Initial Design

## Project Overview

The goal of this project is to design, build, and test a small autonomous mobile robot from the ground up.

The project will begin with a simple prototype using off-the-shelf components such as a microcontroller, motor driver, DC motors, and sensors. As the design develops, the system will be progressively improved through mechanical, electrical, and software iterations.

A major long-term goal is to replace the initial prototyping electronics with a **custom PCB designed in KiCad**.

## Objectives

The project aims to:

* Design and build a functional mobile robotic platform
* Develop embedded software for motor and sensor control
* Implement obstacle detection and avoidance
* Implement feedback-based motor control using wheel encoders
* Develop autonomous navigation between predefined locations
* Design mechanical components using CAD
* Design a custom PCB for the final electronic system
* Experiment with higher-level robotics software if appropriate
* Document the complete engineering design and testing process

## System

The planned system will consist of several major subsystems:

```text
                    Autonomous Rover
                          │
        ┌─────────────────┼─────────────────┐
        │                 │                 │
        ▼                 ▼                 ▼
   Computation        Actuation          Sensing
        │                 │                 │
   Microcontroller     DC Motors      Distance Sensors
        │             Motor Driver        Encoders
        │                 │                 │
        └─────────────────┼─────────────────┘
                          │
                       Power
```

The exact architecture and components will be determined during the design phase.

## Planned Development

### Phase 1 — Prototype

* Select and test components
* Build the initial chassis
* Control the motors
* Read sensor data
* Establish reliable power and wiring

### Phase 2 — Autonomous Behaviour

* Implement obstacle detection
* Implement obstacle avoidance
* Add wheel encoder feedback
* Investigate closed-loop motor control

### Phase 3 — Mechanical and Electrical Refinement

* Improve the CAD design
* Design a custom PCB in KiCad
* Integrate the custom electronics
* Improve reliability and maintainability

### Phase 4 — Autonomous Navigation

* Develop waypoint-based navigation
* Investigate localization and path planning
* Evaluate whether ROS 2 is appropriate for the final system

### Phase 5 — Testing and Validation

* Define quantitative performance tests
* Collect experimental data
* Evaluate the robot against the project requirements
* Document limitations and future improvements

## Technologies

Planned technologies include:

* **C/C++** — embedded programming
* **Python** — potential higher-level robotics software and data analysis
* **Arduino / Microcontroller** — initial embedded platform
* **SolidWorks** — mechanical CAD
* **KiCad** — schematic and PCB design
* **Git / GitHub** — version control and documentation

Additional technologies may be introduced as the project develops.

## Documentation

Detailed project documentation will be maintained in the `docs/` directory.

* [Project Proposal](docs/01-project-proposal.md)

Additional documentation will be added as the project progresses.

## Project Status

This project is currently in the **planning and requirements phase**.

No hardware has been built yet. The initial objective is to establish the system requirements and determine an appropriate hardware architecture before beginning construction.

## Future Work

Potential future improvements include:

* Improved localization
* Mapping
* More advanced path planning
* Computer vision
* Wireless communication
* Higher-level robotics software
* ROS 2 integration
* Improved custom electronics

These features are considered stretch goals and will only be pursued if they contribute meaningfully to the project's objectives.

## Author

**[Desmond Atehnchong Atem]**

Mechatronics Engineering Student
Queen's University

