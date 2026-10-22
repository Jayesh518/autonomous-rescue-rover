# Personal AI + Robotics Rover

**Status: Planned**

A small, personally owned rover that integrates camera-based object detection and range sensing with ROS 2 navigation, tested at low speed in a controlled environment.

Part 3 of 3: combines [robust-computer-vision](https://github.com/jayesh518/robust-computer-vision) and [ros2-slam-navigation](https://github.com/jayesh518/ros2-slam-navigation).

## Research question (hypothesis, not a result)
Does combining camera-based detection with range sensing improve obstacle avoidance and target localization compared with camera-only perception?

## Ownership boundary
This is an independent, personally owned build. It uses no employer hardware, code, designs, data or documents.

## Planned scope
Staged hardware build, safety layer (speed limits, manual emergency stop), teleoperation, perception node with latency logging, range sensing, navigation integration, and repeatable camera-only vs camera+range trials.

## Structure
```
src/        ROS 2 packages and firmware
hardware/   verified bill of materials, wiring diagrams, safety checklist
docs/       report.md and demo/ (approved media only)
```

## Results
None yet.

## Safety
Low-speed tests only, controlled environment, wheels raised during first power-up. No automatic driving toward people.
