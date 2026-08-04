# Robotic Dog Design

## Project Description
This project presents the preliminary mechanical design of a quadruped robotic dog. The design focuses on the mechanical structure, leg mechanism, degrees of freedom (DOF), actuator selection, torque calculation, stability analysis, and gait planning.

## Objectives
- Design a four-legged robotic dog.
- Define the Degrees of Freedom (DOF) for each leg.
- Select suitable servo motors for every joint.
- Perform torque calculations for the main joints.
- Analyze robot stability using the Center of Mass (CoM).
- Propose a stable walking gait.
- Identify possible mechanical issues and suggest solutions.

## Design Specifications
- Robot Type: Quadruped Robot
- Number of Legs: 4
- Degrees of Freedom: 16 DOF (4 DOF per leg)
- Frame Material: Aluminum Alloy
- Actuators: High-Torque Digital Servo Motors
- Control Board: STM32 (Concept)
- Power Supply: 14.8V Li-Po Battery

## Mechanical Design
The robot consists of:
- Main body (Aluminum frame)
- Four identical legs
- Hip Joint (Yaw)
- Thigh Joint (Pitch)
- Knee Joint (Pitch)
- Ankle Joint (Pitch)

## Stability Analysis
The robot is designed so that the Center of Mass (CoM) remains inside the support polygon during standing and walking to improve stability.

## Torque Analysis
Torque calculations were performed for the hip, thigh, knee, and ankle joints. Appropriate safety factors were considered when selecting the actuators.

## Walking Gait
The robot uses a Trot Gait, which provides a good balance between stability, speed, and energy efficiency.

## Expected Mechanical Challenges
- High loads on the joints
- Motor overheating
- Foot slippage
- Weight distribution
- Mechanical wear
