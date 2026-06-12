# FreeCAD-Projects

[![License: Apache](https://img.shields.io/badge/license-APACHE-brightgreen.svg?style=for-the-badge)](/LICENSE.md) [![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fsalindersidhu%2Ffreecad-projects&countColor=%23263759)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fsalindersidhu%2Ffreecad-projects)

## Overview

Repository of personal CAD models and mechanical designs created in FreeCAD. Includes 3D models, assemblies, and supporting macros for various projects ranging from prototypes to finalized designs.

## Prerequisite Software

| Software       | Version   |
| :------------- | :-------- |
| Git            | 2.20.1+   |
| FreeCAD        | 1.0+      |

## Projects

### Humidifier Enclosure
`projects/HumidifierEnclosure.FCStd`

This project is a custom-designed enclosure for a DC 5V ultrasonic humidifier module (atomizer-based). The enclosure is built to securely house the mist generator, allowing proper airflow while maintaining structural stability and water isolation considerations. It is designed with compact integration in mind for DIY humidifier builds and electronic enclosure prototyping.

The design takes into account module mounting, internal clearance for wiring, and real-world fitment of inexpensive ultrasonic atomizer units commonly found in DIY kits.

### Risophy Keyboard USB-C Adapter
`projects/RisophyKeyboardUSBCAdapter.FCStd`

A mechanical USB-C adapter housing designed for the Risophy Mechanical Gaming Keyboard RGB 104 Keys Ultra Slim LED Backlit USB Wired Keyboard Blue Switch. This adapter modifies or extends the keyboard’s connectivity to support a more robust USB-C interface while maintaining a clean physical integration.

The design focuses on tight tolerances for connector fitment, internal strain relief, and alignment within the keyboard chassis. It’s intended for improving durability and modernizing connectivity without altering the core functionality of the keyboard.

### Speaker Control Panel
`projects/SpeakerControlPanel.FCStd`

A custom control panel designed for integrating both a TDA2822-based amplifier PCB and a USB-C PD trigger module into a speaker enclosure. The design provides dedicated mounting platforms for each PCB using screw inserts, ensuring secure installation and easy servicing.

The panel includes precisely positioned cutouts for the USB-C power input, status LED, power switch, volume control knob, and AUX input, creating a clean and organized exterior appearance. The focus of the design is on component fitment, ease of assembly, and providing a professional looking interface for DIY speaker projects.

## Macros

### Batch STL Export 
`macros/Batch_STL_Export.FCMacro`

Automates exporting each body in a FreeCAD document as individual STL files. Useful for 3D printing workflows, modular design iteration, and separating multi-part assemblies into printable components.
