# Miniature-Uninterruptible-Power-Supply-UPS-
# Project Overview
This project presents the design and implementation of a Miniature Uninterruptible Power Supply (UPS) system, developed during my undergrad
The primary goal of this project is to ensure a continuous supply of AC power to connected loads without interruption, even during power failures, voltage fluctuations, or brownouts. The system integrates power electronics and circuit design concepts to provide a reliable backup solution.
The complete project report included in this repository covers the circuit design, working principles, simulation, and implementation details.
# Objectives
To design a compact and efficient UPS system
To provide uninterrupted power supply during outages
To implement automatic switching between main supply and backup
To analyze system performance through practical implementation
# Key Features
Automatic backup power during outages
Seamless switching between AC supply and battery
Inverter-based AC output generation
Use of IC CD4047 for oscillation control
Practical implementation with real components
# Working Principle
The system operates in four main stages:
Charging Circuit – Converts AC to DC using a transformer and rectifier, storing energy in the battery.
Oscillation Circuit – Generates square wave signals using IC CD4047 to drive the MOSFETs.
Power Conversion – MOSFETs convert DC from the battery into AC output.
Auto Switching – Relay ensures automatic transition between main supply and backup power.
