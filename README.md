# Santosh Bala  
Embedded Systems | Robotics | Autonomous Navigation  

Hey There!
Most of my nights are spent figuring out why a rover is crawling at 0.2 m/s due to the STM32 timer ARR being wrong or making sure it doesn’t confidently drive into a wall and break an expensive Intel RealSense camera in the process.  

I like working at the intersection of hardware and software with bugs being beyond just logical but physical, expensive and occasionally on fire. (Me vs over volted capacitors is a never ending saga)

<p align="center">
  <img src="https://github.com/user-attachments/assets/994618b2-3ff9-462e-943c-9fc4d104af6c" width="30%" />
</p>

---

## Mars Rover Work

Working in a highly interdisciplinary team with multiple domains to build a fully autonomous Mars rover.

<p align="center">
<img width="320" height="180" alt="image" src="https://github.com/user-attachments/assets/1a4e3517-174f-4661-9f0a-f53858da0b52" />
</p>

Here's what I've built so far:
### Embedded Systems & Traversal Control
- Designed and implemented a **STM32 + CAN** based control architecture  
- Replaced a fragmented multi-MCU, multi-protocol system with a unified, scalable design  
- Built interrupt driven firmware handling PWM, encoders, timers, and GPIO  
- Implemented **closed-loop velocity control**, ramping, and slew rate limiting for stability  
- Added heartbeat based supervision and fault detection across nodes  

### Autonomous Navigation Stack
- Architected and deployed a **ROS2 Nav2 stack**  
  - Smac Hybrid-A* (global planner)  
  - MPPI (local controller)  
- Developed a custom **C++ costmap plugin** for dynamic keep out zones  
- Integrated **Intel RealSense depth camera** and tuned for outdoor terrain  
- Built a watchdog monitored **multi camera GStreamer pipeline** with hot plug support  

*Note: Code is part of a private team repository*

---

## Featured Projects

Here are some of my personal projects that I worked on for fun:

### [Custom ST-Link Compatible Debugger & Flasher](https://github.com/IM-TechieScientist/custom-stlink)
- Designed a **STM32F103-based debugging tool** using KiCAD  
- Supports SWD flashing and debugging via Black Magic Probe  
- Validated full debugging workflows on real hardware  

### [TSPMO](https://github.com/IM-TechieScientist/tspmo)
- Python CLI tool for fixing command line errors using a local LLM (Qwen Coder via Ollama). This tool captures wrong shell commands, sends them to a local LLM and suggests a fix.
- Inspired by the thefuck CLI tool.

### [Meowsic](https://github.com/IM-TechieScientist/meowsic)
- A Free, Open Source and Feature Rich Music Streaming App built in Python.


---

## Technical Skills

**Languages**  
C, C++, Python

**Embedded Systems**  
STM32 HAL, PWM, Timers, GPIO, UART, CAN, Bootloaders, RTOS  

**Robotics & Frameworks**  
ROS2, Nav2, GStreamer  

**Other Tools**  
GDB, Black Magic Probe, CAN diagnostics, Linux, Git, Docker, KiCAD PCB Design, networking tools  

---
