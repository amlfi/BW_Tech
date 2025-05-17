---
description: >-
  Core audio networking software for managing digital audio routing and device
  configuration throughout Bluey's World.
cover: >-
  https://images.unsplash.com/photo-1618609377864-68609b857e90?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw0fHxhdWRpb3xlbnwwfHx8fDE3NDU5OTQ1NDF8MA&ixlib=rb-4.0.3&q=85
coverY: 0
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 6.1.4.1 / Dante

**Dante (Digital Audio Network Through Ethernet)**\
Dante is an industry-standard audio-over-IP networking technology that transmits high-quality, uncompressed digital audio (and often control data) over standard Ethernet networks. It replaces traditional analog cabling with a flexible, scalable, and software-driven system.

**Key Features**:

* **Network-Based**: Uses Cat 5e/6 cables and network switches to route audio between devices (amplifiers, servers, etc.).
* **Software Control**: Configure and patch audio paths via **Dante Controller** (e.g., sending _Bluey_ audio from Max 8 to Yamaha amplifiers).
* **Low Latency**: Delays as low as 1ms, critical for live performances.
* **Plug-and-Play**: Devices self-identify on the network; no physical rewiring needed.

**How It Works at Buley World**

1. **Devices**: Yamaha amplifiers, MAC Audio Servers, and Max 8 (via _Dante Virtual Soundcard_) connect to the Dante network.
2. **Routing**: Audio from Max 8 is assigned to Dante channels and patched to amplifiers/speakers using Dante Controller.

