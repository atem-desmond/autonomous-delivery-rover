# Autonomous Delivery Rover — Requirements

**Project Status:** Preliminary

**Last Updated:** 12 September 2026

---

## 1. Purpose

This document defines the preliminary functional and performance requirements for the Autonomous Delivery Rover.

The requirements will be refined as the project progresses and additional information becomes available through research, calculations, prototyping, and testing.

---

## 2. Operating Environment

The rover is intended for indoor operation in a controlled environment.

### Initial assumptions

* Relatively flat floor surface
* No outdoor operation
* Limited obstacles compared with an uncontrolled environment
* Robot operates at low speed
* Robot does not need to operate on stairs or steep slopes

These assumptions may be revised as the design develops.

---

## 3. Functional Requirements

### R-001 — Mobility

The rover shall be capable of forward and reverse motion.

### R-002 — Steering

The rover shall be capable of turning left and right without direct physical intervention.

### R-003 — Obstacle Detection

The rover shall detect obstacles within a defined detection range.

**Initial target:** ≥ 50 cm

### R-004 — Obstacle Avoidance

The rover shall be capable of avoiding detected obstacles without direct human control.

### R-005 — Autonomous Operation

The rover shall be capable of performing its navigation task without continuous manual control.

### R-006 — Payload

The rover shall be capable of carrying a small payload.

**Initial target:** ≥ 500 g

### R-007 — Delivery

The rover shall include a mechanism capable of releasing or delivering the payload at the destination.

### R-008 — Battery Operation

The rover shall operate from a portable battery supply.

---

## 4. Performance Requirements

The following values are preliminary targets and will be refined after hardware selection.

| Requirement              | Initial Target | Final Target |
| ------------------------ | -------------: | -----------: |
| Payload capacity         |        ≥ 500 g |          TBD |
| Maximum speed            |      ≥ 0.5 m/s |          TBD |
| Operating time           |       ≥ 20 min |          TBD |
| Obstacle detection range |        ≥ 50 cm |          TBD |
| Navigation accuracy      |        ≤ 10 cm |          TBD |
| Autonomous operation     |       Required |     Required |

---

## 5. Mechanical Requirements

The rover shall:

* Fit within a compact indoor form factor.
* Support the required payload.
* Provide secure mounting for motors and wheels.
* Provide mounting locations for sensors and electronics.
* Provide access to the battery and major electronic components.
* Be designed using CAD.
* Allow future mechanical modifications where practical.

---

## 6. Electrical Requirements

The electrical system shall:

* Provide appropriate power to the microcontroller.
* Provide appropriate power to the motors.
* Provide appropriate power to sensors and other peripherals.
* Include appropriate voltage regulation where required.
* Support motor control.
* Support wheel encoder inputs.
* Provide appropriate connections for sensors.
* Be designed with electrical safety and reliability in mind.

A custom PCB is a long-term project goal.

---

## 7. Software Requirements

The software system shall:

* Control motor operation.
* Read and process sensor data.
* Detect obstacles.
* Implement obstacle avoidance.
* Support autonomous navigation.
* Provide a method of testing individual hardware components independently.

The initial embedded software will be developed using C/C++.

Python and/or ROS 2 may be introduced later if they provide a meaningful benefit to the system.

---

## 8. Testing Requirements

Major system requirements shall be validated through measurable experiments where practical.

Testing may include:

* Motor speed testing
* Straight-line accuracy
* Distance measurement
* Encoder accuracy
* Obstacle detection accuracy
* Obstacle avoidance success rate
* Navigation accuracy
* Battery operating time
* Payload testing
* Delivery mechanism reliability

Test procedures and results will be documented in the project repository.

---

## 9. Constraints

The project will be developed under the following constraints:

* Student project budget
* Indoor operation
* Limited workspace
* Limited development time alongside university coursework
* Components should be reasonably accessible
* The system should remain sufficiently simple to develop incrementally

---

## 10. Stretch Requirements

The following are optional and will only be pursued after the core requirements have been satisfied:

* PID motor control
* Improved localization
* Mapping
* Path planning
* Computer vision
* Wireless control
* ROS 2 integration
* More advanced autonomous navigation

---

## 11. Requirement Status

Requirements will be tracked throughout the project.

Possible statuses include:

* 🔴 Not started
* 🟡 In progress
* 🟢 Complete
* ⚪ Deferred

Requirements may be modified when new information is obtained through testing or design analysis.

---

## 12. Revision History

| Version | Date           | Change                           |
| ------- | -------------- | -------------------------------- |
| 0.1     | 12 September 2026 | Initial preliminary requirements |
