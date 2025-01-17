# PAROL6-Desktop-robot-arm
[![License: MIT](https://img.shields.io/badge/license-GPLv3-blue)](https://opensource.org/license/gpl-3-0/)
<img src="Images/img3.png" alt="drawing" width="5000"/>

**Sign up and get notified when available: https://source-robotics.com**

Join [Discord](https://discord.com/invite/prjUvjmGpZ ) community!

PAROL6 is a high-performance 3D-printed desktop robotic arm. The design approach of PAROL6 was to be similar to industrial robots in terms of mechanical design, control software, and usability. Control software, GUI, and robots STL files are open-source. 

# How to build / Where to buy?

You can buy PAROL6 robotic arm on our website: https://source-robotics.com

If you want to Source all the parts yourself and build your own follow these steps:

* Source all the parts from the [BOM](https://github.com/PCrnjak/PAROL6-Desktop-robot-arm/tree/main/BOM)
* Follow [Building instructions](https://github.com/PCrnjak/PAROL6-Desktop-robot-arm/tree/main/Building%20instructions) to assemble your robot
* Follow [DOCS](https://source-robotics.github.io/PAROL-docs/) to get your robot up and running.

# Documentation:
- [Official website](https://source-robotics.com)
- [Commander software](https://github.com/PCrnjak/PAROL-commander-software)
- [Building instructions](https://github.com/PCrnjak/PAROL6-Desktop-robot-arm/tree/main/Building%20instructions)
- [BOM](https://github.com/PCrnjak/PAROL6-Desktop-robot-arm/tree/main/BOM)
- [DOCS](https://source-robotics.github.io/PAROL-docs/)

# More about PAROL6
- [Youtube](https://www.youtube.com/channel/UCp3sDRwVkbm7b2M-2qwf5aQ)
- [Hackaday](https://hackaday.io/project/191860-parol6-desktop-robotic-arm)
- [Instagram](https://www.instagram.com/5arcrnjak/)
- [DOCS](https://source-robotics.github.io/PAROL-docs/)
- [Twitter](https://twitter.com/SourceRobotics)

# 📢📢Contributing to the project 📢📢
Some features are still missing on the software and hardware side of the PAROL6.<br />
If you want to contribute to the project and don't know how you can help in the implementation of some of these features:

General features:
  - ROS2 support
  - Moveit example
  - ROBODK postprocessor
  - TODO -> Stepper driver stages need to go to short or all fets low when the power button is pressed
  - TODO ->Implement Swift simulator - https://github.com/jhavl/swift
  - TODO -> Create executable files for Windows and Linux

  PAROL6 commander software features:
  - Reading GCODE commands
  - Reading inputs
  - implementing flow control (IF, ELSE...)
  - Graphical simulator?
  - Saving programs to the Control board Flash
  - Offline execution of the code (from the flash)
  - Blending in trajectory planner

# Liability 
1. The software and hardware are still in development and may contain bugs, errors, or incomplete features.
2. Users are encouraged to use this software and hardware responsibly and at their own risk.

# Project is under GPLv3 Licence
