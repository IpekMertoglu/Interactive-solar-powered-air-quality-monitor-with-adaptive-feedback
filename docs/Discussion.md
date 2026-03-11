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
##Cost##
```
The total material cost for a single device is estimated to be approximately 40–60 EUR.
This estimate reflects that several components were reused from existing stock in university laboratories, while the remaining parts were sourced through the Living the Forest Lab. The design explicitly supports the reuse of available components and does not rely on specialized or hard-to-source parts.
As a result, actual costs may vary depending on existing inventories and access to shared lab resources.
```
## Validation

```
The system was validated through functional testing of individual subsystems, including:
• Sensor readings under varying environmental conditions
• Power supply and charging behavior during solar operation
• Correct triggering of feedback mechanisms based on sensor thresholds
Validation focused on robustness and understandability rather than measurement accuracy or calibration against certified reference instruments. The device is intended as a learning and research prototype, not as a calibrated measurement system.

```
##Education resources

```
This project serves as an educational and research-based learning resource developed within the context of a bachelor’s thesis in electrical engineering.
The documentation supports learning and teaching through:
• Detailed build instructions and circuit schematics
• Annotated firmware code and explanations
• Conceptual descriptions of solar power management, sensor systems, and feedback
mechanisms

```
##Roadmap

```
The project was developed as part of a bachelor’s thesis in electrical engineering and followed an iterative, prototype-driven process.
Past and current stages
• Concept development and definition of educational and design goals
• Selection and testing of environmental sensors and power components
• Development of a solar-powered energy supply and low-power firmware
• Integration of sensors, actuators, and adaptive feedback mechanisms
• Fabrication of enclosure and mechanical elements
• Documentation and validation of the functional prototype
```
##Future milestones

```
• Refinement of hardware robustness and enclosure design
• Improved modularization of hardware and firmware components
• Expansion of educational materials and workshop-ready documentation
• Optional evaluation in teaching or workshop settings

```
