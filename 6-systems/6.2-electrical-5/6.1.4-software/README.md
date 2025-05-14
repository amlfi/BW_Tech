---
description: >-
  Covers media server platforms and playback tools used for content delivery,
  cue triggering, and show integration.
icon: browsers
cover: >-
  https://images.unsplash.com/photo-1535016120720-40c646be5580?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHwxfHxwcm9qZWN0b3J8ZW58MHx8fHwxNzQ2NzY0MzY1fDA&ixlib=rb-4.1.0&q=85
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

# 6.7.4 / Software

## 💻 Video Software

_A reference guide to the key software systems supporting video playback and projection across Bluey's World._

***

<details>

<summary>🎛️ Resolume</summary>

**Function**\
Media playback and video output control.

**Used For**

* Driving content to projectors
* Managing looped or triggered playback sequences

**Location**

* Dome PC&#x20;
* Creek PC
* Y PC

**Operational Notes**

*

</details>

***

<details>

<summary>🧭 NestMap</summary>

**Function**\
Projection mapping tool for aligning visuals across custom surfaces.

**Used For**

* Calibrating and blending visuals across multiple projectors
* Displaying test patterns and mapped content

**Location**

* Dome PC&#x20;
* Creek PC

**Operational Notes**

* Only used if recalibration is needed
* Test pattern should be used to confirm projection accuracy pre-show
* Use in tandem with Resolume via Spout

</details>

***

<details>

<summary>🔄 Spout</summary>

**Function**\
Real-time video sharing between applications (e.g. Resolume ➝ NestMap).

**Used For**

* Routing live video feed from Resolume into NestMap for mapped display

**Location**

* Runs in the background on the PC

**Operational Notes**

* Requires both Resolume and NestMap to be running
* No user interface — verify feed is active by checking mapped projection output
* Restart apps if video fails to display across mapped surfaces

</details>

***

📝 **General Notes**

* Software must be started in the correct order: **Resolume → NestMap**
* Confirm projector power is ON before launching any applications

***
