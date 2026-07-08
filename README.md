# 🐕 Mechanical Design of a Simple Robotic Dog Using Tinkercad

## Overview

This project presents the mechanical design of a simple robotic dog created using **Tinkercad**. The objective was to design a lightweight quadruped robot that demonstrates the basic principles of mechanical robot design, including body structure, leg mechanisms, joints, motor selection, stability, and torque estimation.

This project focuses on the **mechanical design only** and does not include electronics or programming.

---

## Project Objectives

- Design a simple robotic dog chassis.
- Build four identical legs.
- Define the joints and Degrees of Freedom (DOF).
- Select suitable servo motors.
- Estimate the required torque for one joint.
- Analyze stability and center of gravity.
- Propose a simple walking gait.
- Identify possible mechanical challenges.

---

## Software Used

- Autodesk Tinkercad

---

## Robot Specifications

| Feature | Description |
|---------|-------------|
| Robot Type | Robotic Dog (Quadruped) |
| Number of Legs | 4 |
| Joints per Leg | 2 |
| Total Joints | 8 |
| Degrees of Freedom | 8 DOF |
| Motor Type | SG90 Servo Motor |

---

## Mechanical Design

The robot consists of:

- Rectangular body (chassis)
- Four identical legs
- Hip joints
- Upper legs
- Knee joints
- Lower legs

The design was created using simple geometric shapes available in Tinkercad, resulting in a lightweight and symmetrical mechanical structure.

### Complete Robot Design

![Complete Robot](Images/Complete_Design.png)

### Robot Leg Design

![Robot Leg](Images/Robot_Leg.png)

---

## Motor Selection

The selected actuator is the **SG90 Servo Motor** because it is:

- Lightweight
- Compact
- Easy to control
- Suitable for educational robotics projects

A total of **8 servo motors** are required (one motor for each joint).

---

## Initial Torque Estimation

The required joint torque was estimated using:

**τ = F × r**

Where:

- Robot mass = **1 kg**
- Weight = **9.81 N**
- Force per leg = **9.81 / 4 = 2.45 N**
- Distance from joint = **0.05 m**

**Torque = 2.45 × 0.05 = 0.1225 N·m**

**Estimated Required Torque ≈ 0.13 N·m**

This value indicates that an **SG90 servo motor** is suitable for the preliminary mechanical design.

---

## Stability

The robot was designed with:

- Symmetrical body structure
- Equal spacing between the legs
- Centered center of gravity
- Lightweight chassis

These features improve balance during movement.

---

## Proposed Walking Method

The robot uses the **Crawl Gait**.

Walking sequence:

1. Front Left
2. Rear Right
3. Front Right
4. Rear Left

This gait provides high stability because three legs remain on the ground while one leg moves.

---

## Expected Mechanical Challenges

- Joint friction
- Limited servo torque
- Body vibration
- Foot slipping
- Joint misalignment
- Uneven weight distribution

---

## Skills and Experience Gained

This project was my first experience creating a 3D mechanical model using **Tinkercad**.

During this project, I learned how to:

- Design a robotic dog using CAD software.
- Create joints and leg mechanisms.
- Understand Degrees of Freedom (DOF).
- Select suitable servo motors.
- Estimate joint torque.
- Analyze stability and center of gravity.

This project improved my CAD modeling skills and provided valuable hands-on experience in mechanical robotics design.

---

## Project Files

This repository contains:

- **Report.pdf** – Complete project report.
- **Tinkercad Design** – Exported 3D model of the robotic dog.
- **Images/** – Images of the complete robot and leg design.
- **README.md** – Project documentation.

---

## Repository Structure

```text
Robotic-Dog/
│
├── README.md
├── Report.pdf
├── Tinkercad_Design.stl
└── Images/
    ├── Complete_Design.png
    └── Robot_Leg.png
```

---

## Conclusion

This project demonstrates the mechanical design of a simple robotic dog using Tinkercad. It provided practical experience in 3D modeling and introduced the fundamental concepts of quadruped robot mechanics, serving as a strong foundation for future robotics development.
