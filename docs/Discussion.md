## Problem description
```
In many educational contexts, electrical engineering is taught in a highly theoretical and abstract way, making it difficult for beginners to connect concepts to real-world applications. Practical, integrative learning artifacts are often missing, while existing devices are frequently proprietary or insufficiently documented.
This project addresses the lack of accessible and transparent hardware systems that allow learners to explore core electrical engineering concepts; such as energy supply, sensing, and feedback through hands-on interaction and open documentation.
```

## Standard compliance
```
This project does not implement or claim compliance with specific industrial or regulatory standards. As a research and educational prototype, the hardware is not intended for certified environmental monitoring, safety-critical applications, or commercial deployment.
Where applicable, commonly accepted conventions for open hardware documentation, electronic schematics, and sensor usage are followed to support transparency, reproducibility, and comparability.
```
## Outputs: Products and data
```
Products
• A functional, solar-powered air quality monitoring device
• Open-source hardware documentation, including schematics, wiring diagrams, and build
instructions
• Firmware for sensor data acquisition and adaptive feedback control
Data
• Environmental sensor readings (e.g. temperature, humidity, air quality indicators)
• Derived internal states used for adaptive feedback (non-personal, local-only)
All data is processed locally on the device.

```
## Dependencies
```
The hardware is based on commonly available, off-the-shelf electronic components.  
It depends on:
• A microcontroller platform compatible with the Arduino ecosystem
• Standard sensor libraries and open-source firmware tools
• No proprietary software, cloud services, or external infrastructure
All dependencies are openly documented and replaceable with comparable components.
```
