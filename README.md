# Santosh Bala N
Distributed Systems | Backend | Embedded | Robotics

### Hey there!

Most of my nights are spent either debugging a rover that's crawling at 0.2 m/s because the timer ARR was wrong, or debugging a Kafka consumer that's crawling for entirely more boring reasons. I like working across the whole stack from an ISR to a distributed consensus protocol. I've made peace with the fact that on one side of my work a bug is a stack trace and on the other it's occasionally on fire. (Me vs over volted capacitors is a never-ending saga.)

<p align="center">
  <img src="https://github.com/user-attachments/assets/994618b2-3ff9-462e-943c-9fc4d104af6c" width="30%" />
</p>

---

## Currently

- 🔭 Writing firmware for an Open Source lab instrument in **PSLab Project**, as part of **Google Summer of Code 2026**
- 🚀 Leading software for **Team Vyadh**, VIT's Mars Rover team
- 🛠️ Building out backend/distributed-systems projects on the side 

---

## Google Summer of Code 2026
Open-source contributor for **PSLab Project**

- Writing modular firmware in **C** using a 3-layer platform / system / application architecture, with a hardware abstraction layer kept cleanly separate from application logic
- Implementing a **200 MSPS logic analyzer** and **80 MSPS oscilloscope** using DMA-driven, interrupt-based sampling for high-throughput real-time capture
- Built an industry-standard **SCPI** command interface over USB, plus wireless **UDP**-based streaming for untethered operation
- Validating end-to-end integration across PSLab firmware, the Python library, and desktop/mobile applications

---

## Mars Rover Work (Team Vyadh, VIT)
Software Lead on a highly interdisciplinary team building a fully autonomous Mars rover.

<p align="center">
<img width="320" height="180" alt="image" src="https://github.com/user-attachments/assets/1a4e3517-174f-4661-9f0a-f53858da0b52" />
</p>

**Control architecture**
- Redesigned a fragmented multi-MCU, multi-protocol setup into a unified, deterministic **STM32 + CAN** architecture
- Built interrupt-driven firmware handling PWM, encoders, timers, and GPIO
- Implemented closed-loop velocity control, ramping, and slew-rate limiting for stability
- Added heartbeat-based supervision and fault detection across nodes

**Autonomous navigation**
- Architected and deployed a **ROS 2 / Nav2** stack: Smac Hybrid-A* as global planner, MPPI as local controller
- Wrote a custom **C++ costmap plugin** for dynamic polygon based keep-out zones
- Integrated an **Intel RealSense** depth camera, tuned for outdoor terrain

**Telemetry & video**
- Designed a real-time ground control station telemetry pipeline over **MQTT** including GPS/odometry, battery, environmental and multi spectral science sensor data, with fault tolerance and auto-reconnect
- Built a 6 channel HD camera streaming pipeline in **GStreamer** with hardware accelerated encoding, dynamic resolution scaling, hot plug/unplug support, and watchdog monitored auto-reconnect with 100% streaming uptime across competition

*Note: code is part of a private team repository.*

---

## Featured Projects

### [Hermes](https://github.com/IM-TechieScientist/hermes)
`Go` `Redis Streams` `Prometheus` `Grafana` `Docker`

Pub-sub middleware inspired by ROS 2/DDS internals — broker-managed topics, reliable TCP and best-effort UDP transports, Redis Streams durability with offset-based replay, schema enforcement, and full Prometheus/Grafana observability.

Sustained **256,000/256,000** reliable deliveries across **512 subscribers** at **48ms p99 latency** with zero drops, through a 2,048-node simulated warehouse load test.

### Multi-Node Telemetry Pipeline
`Go` `Kafka` `Kubernetes` `Terraform` `Prometheus` `Grafana`

Distributed telemetry ingestion pipeline simulating multiple nodes, with Kafka-based ingestion across partitioned, horizontally-scalable consumers and real-time anomaly detection on sensor streams. Deployed on Kubernetes via Terraform-provisioned infrastructure, with Prometheus/Grafana dashboards for ingestion and system health.

### Distributed Job Scheduler
`Go` `Raft` `gRPC` `etcd` `Kubernetes`

Fault-tolerant distributed task scheduler implementing Raft consensus for leader election and coordinator failover, with idempotent execution and dead-letter handling for failing jobs. gRPC API for job submission and status; autoscaled workers on Kubernetes based on queue depth.

### [Custom ST-Link Compatible Debugger & Flasher](https://github.com/IM-TechieScientist/custom-stlink)
- Designed an STM32F103-based debugging tool in KiCAD
- Supports SWD flashing and debugging via Black Magic Probe
- Validated full debugging workflows on real hardware
  
---

## Technical Skills

**Languages**: C, C++, Python, Go, JavaScript

**Systems & Distributed**: Redis Streams, Kafka, MQTT, Prometheus, Grafana, REST, TCP/UDP

**Cloud & Infra**: Kubernetes, Terraform, gRPC, Raft/etcd, Docker, GitHub Actions

**Robotics & Perception**: ROS 2, Nav2, GStreamer, FoundationPose, SAM3, ArUco

**Embedded**: STM32, ESP32, RP2350, PWM, Timers, GPIO, UART, CAN, DMA, RTOS, Bootloaders

**Tools**: Git, Linux, CMake, GDB, Black Magic Probe, KiCAD, Docker

**AI Tools**: Claude, OpenAI Codex, GitHub Copilot

---

<p align="center">
  <em>Bugs here aren't just logical — some of them are on fire.</em>
</p>
