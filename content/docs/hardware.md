---
title: "Hardware and Robotics"
weight: 140
---

# Hardware and Robotics in Julia

> Software libraries to control hardwarr and robots

**Organzations**

- [Julia robotics](https://github.com/JuliaRobotics)
- [Julia embedded](https://github.com/Julia-Embedded)
- [Julia berry](https://github.com/JuliaBerry)

## APIs and bindings

- [Instruments.jl](https://github.com/BBN-Q/Instruments.jl) : A package for controlling laboratory instruments through Julia over TCPIP/GPIB/USB/Serial, wrapped around the NI-VISA library (which needs to be separately installed) similar to PyVISA and has some starts towards making it easier to write custom instrument drivers.
- [NIDAQ.jl](https://github.com/JaneliaSciComp/NIDAQ.jl) : This package provides an interface to NIDAQmx - National Instruments' driver for their data acquisition boards.

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Alazar.jl](https://github.com/ajkeller34/Alazar.jl) : [AlazarTech](http://www.alazartech.com/) API wrapper for Julia.
- 🏚️ [DIDebug.jl](https://github.com/Keno/DIDebug.jl) : Debug the destination index in an x86 computer architecture using the standardized DWARF-ELF debugging data format.
- 🏚️ [FTD2XX.jl](https://github.com/cstook/FTD2XX.jl) : Wrapper for FTDI [FTD2XX](http://www.ftdichip.com/Drivers/D2XX.htm) library.
- 🏚️ [MichrochipRTDM.jl](https://github.com/cstook/MicrochipRTDM.jl) : A bunch of functions usefull for working with MicrochipTM's RTDM interface.
- 🏚️ [RdRand.jl](https://github.com/SamChill/RdRand.jl) : Generate random numbers using Intel's RDRAND instruction.
- 🏚️ [Vectorize.jl](https://github.com/rprechelt/Vectorize.jl) : Cross-platform vectorization of Julia code using Accelerate, VML, Yeppp! and LLVM.
- 🏚️ [VISA.jl](https://github.com/ajkeller34/VISA.jl) : [VISA](https://www.ni.com/visa/) wrapper for Julia.
- 🏚️ [ZenFab.jl](https://github.com/FactoryOS/ZenFab.jl) : Software for using digital manufacturing devices.

</details>

## Computer-assisted design / manufacture (CAD/CAM)

- [Devices.jl](https://github.com/PainterQubits/Devices.jl) : For simplified generation of device CAD files for superconducting device design.
- [LTspice.jl](https://github.com/cstook/LTspice.jl) : It provides a julia interface to [LTspice](http://www.linear.com/designtools/software/#LTspice).

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Gcode.jl](https://github.com/sjkelly/Gcode.jl) : A wrapper for writing [Gcode](http://en.wikipedia.org/wiki/Gcode) from Julia easily.

</details>

## Embedded Systems

[Embedded Systems](https://en.wikipedia.org/wiki/Category:Embedded_systems)

- [JuliaBerry.jl](https://github.com/JuliaBerry/JuliaBerry.jl) : An omnibus package with a high level API for controlling peripherals on the Raspberry Pi computer.
- [PiGPIO.jl](https://github.com/JuliaBerry/PiGPIO.jl) : Manage external hardware using GPIO pins on the Raspberry Pi.
- [PiCraft.jl](https://github.com/JuliaBerry/PiCraft.jl) : Manipulate Minecraft on the Raspberry Pi from Julia.

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Arduino.jl](https://github.com/ihnorton/Arduino.jl) : Basic [Arduino](http://www.arduino.cc/) interface for Julia.
- 🏚️ [TinyG.jl](https://github.com/sjkelly/TinyG.jl) : This package provides support for CNC controllers running the [TinyG firmware](https://github.com/synthetos/TinyG/wiki), principally developed by Synthetos.

</details>

## Robots

- [Caesar.jl](https://github.com/JuliaRobotics/Caesar.jl) : Robot toolkit: Towards non-parametric and parametric navigation solutions.
- [MotionCaptureJointCalibration.jl](https://github.com/JuliaRobotics/MotionCaptureJointCalibration.jl) : Kinematic calibration for robots using motion capture data.
- [RigidBodyDynamics.jl](https://github.com/JuliaRobotics/RigidBodyDynamics.jl) : Julia implementation of various rigid body dynamics and kinematics algorithms.
- [RobotOS.jl](https://github.com/Julia-Embedded/RobotOS.jl) : Julia interface to [ROS](http://wiki.ros.org/) (Robot Operating System).
- [ROS.jl](https://github.com/gstavrinos/ROS.jl) : A Julia wrapper of the ROS C++ client.
- [RigidBodySim.jl](https://github.com/JuliaRobotics/RigidBodySim.jl) : Simulation and visualization of articulated rigid body systems in Julia.
- [StrandbeestRobot.jl](https://github.com/rdeits/StrandbeestRobot.jl) : Simulation of a 12-legged parallel walking mechanism in Julia, inspired by Theo Jansen's Strandbeest.

---

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [FPTControl.jl](https://github.com/krisztiankosi/FPTControl.jl) : Fixed Point Transformation Based Control.
- 🏚️ [Robotics.jl](https://github.com/cdsousa/Robotics.jl) : Toolbox for (serial manipulator) robotics, focusing robot dynamics.

</details>

## TouchScreen

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Taste.jl](https://github.com/jiahao/Taste.jl) : A simple package for computerized human-computer olfaction and gustation interactivity that supports integrated Instant Olfaction Technology Screens.

</details>
