Smart Street Light and Traffic Control System
Project-Based Learning (PBL) – Embedded AI & IoT
📖 About the Project

This project was developed as part of Project-Based Learning (PBL) in the subject Embedded AI & IoT.

The Smart Street Light and Traffic Control System is an intelligent automation system built using Raspberry Pi. It combines:

🌙 Smart street lighting based on light intensity

🚗 Traffic light control system

🚶 Motion-based brightness control

🌐 IoT-based monitoring using a web interface

The system improves energy efficiency and enables smart traffic management.

🎯 Objectives

To automate street light operation

To design a basic traffic signal control system

To reduce energy consumption

To integrate IoT monitoring using Flask

To apply embedded intelligence in real-time systems

🛠️ Hardware Components

Raspberry Pi

LDR (Light Dependent Resistor)

MCP3008 ADC

IR Sensor (Motion detection)

LEDs (Red & Green for traffic control)

Resistors

Breadboard

Jumper Wires

💻 Software & Technologies

Python

Flask (Web Framework)

HTML/CSS

RPi.GPIO Library

PWM (Pulse Width Modulation)

⚙️ System Working
🌞 Street Light – Day Mode

LDR detects high light intensity

Raspberry Pi turns OFF street lights

Saves energy

🌙 Street Light – Night Mode

LDR detects low light intensity

Street lights turn ON at 50% brightness

Controlled using PWM

🚶 Motion Detection

IR sensor detects movement

Brightness increases to 100%

After delay, returns to 50%
