---
title: "Architecture"
layout: "single"
url: "/architecture/"
---

## The Distributed Soma

The organism's body is a Distributed Robotics LAN. Individual nodes handle specific biological functions via the Mosquitto MQTT protocol.

| Organ | Hardware | Responsibility | Protocol |
| --- | --- | --- | --- |
| **The Brain** | Mac Mini | Primary Agent: Python AI, Manifold API, & DAO Treasury logic | MQTT Broker |
| **The Nerves** | Raspberry Pi 5 | Sensory Input: Real-time proximity (Lidar, Ultrasonic, PIR) | Publisher |
| **The Larynx** | Raspberry Pi 5 | Audio Scape: Generative sound reacting to "stress" | Subscriber |
| **The Muscle** | Raspberry Pi 4 | Kinetic Motion: Stepper motor and servo control | Subscriber |
| **The Skin** | Raspberry Pi 4 | Luminescence: DMX/LED arrays reflecting "Mood" | Subscriber |
