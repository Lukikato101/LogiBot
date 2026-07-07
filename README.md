# LogiBot

**Low-cost Autonomous Mobile Robot (AMR) for Warehouse Automation**

LogiBot is an autonomous mobile robot project focused on building an affordable and practical warehouse automation platform for small and medium-sized warehouses.

The goal of this project is to develop a reliable AMR system that can transport materials, navigate autonomously, and serve as a foundation for future warehouse automation solutions.

---

## Vision

Warehouse automation should not be limited to large enterprises.

LogiBot aims to make autonomous material transport more accessible by developing a cost-effective AMR platform that can be deployed in real-world warehouse environments.

---

## Project Goals

* Build a reliable autonomous mobile robot platform
* Develop a low-cost warehouse transportation solution
* Create a modular hardware and software architecture
* Support ROS 2 based development
* Enable fleet management and multi-robot operations
* Provide a foundation for future commercial deployment

---

## Current Development Status

### Phase 1 — Mobile Robot Platform

* [ ] Differential drive platform
* [ ] STM32 motor controller
* [ ] Encoder integration
* [ ] IMU integration
* [ ] Battery management

### Phase 2 — ROS 2 Integration

* [ ] ROS 2 communication
* [ ] Robot description (URDF)
* [ ] Teleoperation
* [ ] Odometry

### Phase 3 — Autonomous Navigation

* [ ] Localization
* [ ] Waypoint navigation
* [ ] AprilTag navigation
* [ ] Obstacle detection

### Phase 4 — Warehouse Features

* [ ] Material transport workflow
* [ ] Automatic docking
* [ ] Charging station
* [ ] Fleet management dashboard

### Phase 5 — Field Testing

* [ ] Real warehouse deployment
* [ ] Performance optimization
* [ ] Reliability testing

---

## System Architecture

```text
+------------------------+
|      Fleet Manager     |
+-----------+------------+
            |
            v
+------------------------+
|    ROS 2 Computer      |
| (Raspberry Pi / SBC)   |
+-----------+------------+
            |
            v
+------------------------+
|         STM32          |
|  Motor & Sensor Layer  |
+-----------+------------+
            |
            v
+------------------------+
| Motors / Encoders /    |
| IMU / Safety Sensors   |
+------------------------+
```

---

## Repository Structure

```text
LogiBot/

├── docs/
├── hardware/
├── firmware/
├── software/
├── simulation/
├── dashboard/
├── test/
└── README.md
```

### docs/

Project documentation, architecture, roadmap, and technical notes.

### hardware/

Mechanical design, CAD files, PCB designs, and manufacturing resources.

### firmware/

STM32 firmware for motor control, sensors, and communication.

### software/

ROS 2 packages, navigation stack, robot interfaces, and system integration.

### simulation/

Simulation environments and testing tools.

### dashboard/

Fleet monitoring and management interface.

---

## Technology Stack

### Hardware

* STM32
* Differential Drive Platform
* BLDC/DC Motors
* Encoders
* IMU
* Camera
* Battery Management System

### Software

* ROS 2
* Ubuntu
* C++
* Python
* Micro-ROS
* Gazebo

---

## Contribution Areas

There are many ways to contribute:

### Embedded Systems

* STM32 firmware
* Motor control
* Sensor integration
* Communication protocols

### Robotics Software

* ROS 2 packages
* Navigation
* Localization
* Path planning

### Mechanical Design

* Chassis design
* CAD modeling
* Manufacturing optimization

### Electronics

* PCB design
* Power systems
* Safety circuits

### Simulation

* Gazebo environments
* Testing scenarios
* Validation tools

### Documentation

* Tutorials
* Setup guides
* Technical documentation

---

## How to Contribute

1. Fork the repository
2. Create a feature branch
3. Implement your changes
4. Test your work
5. Submit a Pull Request

Please keep contributions focused, documented, and aligned with the project roadmap.

---

## Roadmap

### V0.1

Basic differential drive robot

### V0.2

ROS 2 integration

### V0.3

Autonomous waypoint navigation

### V0.4

Automatic docking

### V0.5

Fleet management

### V1.0

Warehouse-ready AMR platform

---

## Long-Term Objective

Build an affordable warehouse AMR platform that helps small and medium-sized businesses adopt automation without the high costs typically associated with industrial robotics.

---

## Join the Project

If you are interested in robotics, embedded systems, ROS 2, mechanical design, electronics, or warehouse automation, contributions are welcome.

Together we can build a practical and accessible AMR platform from the ground up.

---

**Project Name:** LogiBot

**Status:** Early Development

**License:** To be determined
