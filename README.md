Smart Street Light and Traffic Control System
----------------------------------------------------------
📖 About the Project
----------------------------------------------------------
This project was developed as part of Project-Based Learning (PBL) in the subject Embedded AI & IoT.

The Smart Street Light and Traffic Control System is an intelligent automation system built using Raspberry Pi. It combines:

🌙 Smart street lighting based on light intensity

🚗 Traffic light control system

🚶 Motion-based brightness control

🌐 IoT-based monitoring using a web interface

The system improves energy efficiency and enables smart traffic management.

🎯 Objectives
----------------------------------------------------------
🟢 To automate street light operation

🟢 To design a basic traffic signal control system

🟢 To reduce energy consumption

🟢To integrate IoT monitoring using Flask

🟢 To apply embedded intelligence in real-time systems

🛠️ Hardware Components
----------------------------------------------------------
🔷 Raspberry Pi

🔷 LDR (Light Dependent Resistor)

🔷 MCP3008 ADC

🔷 IR Sensor (Motion detection)

🔷 LEDs (White for street lights,Red & Green for traffic control)

🔷 Resistors

🔷 Breadboard

🔷 Jumper Wires

💻 Software & Technologies
----------------------------------------------------------
🟥 Python

🟥 Flask (Web Framework)

🟥 HTML/CSS


⚙️ System Working
----------------------------------------------------------
🌞 Street Light – Day Mode
----------------------------------------------------------

➜ LDR detects high light intensity

➜ Raspberry Pi turns OFF street lights

➜ Saves energy


🌙 Street Light – Night Mode
----------------------------------------------------------

➜ LDR detects low light intensity

➜ Street lights turn ON at 50% brightness

➜ Controlled using PWM


🚶 Motion Detection
----------------------------------------------------------

➜ IR sensor detects movement

➜ Brightness increases to 100%

➜ After delay, returns to 50%

🚦 Traffic Control System
----------------------------------------------------------
The traffic control system simulates a real traffic junction using LEDs.

🚥 Traffic Light Logic:
----------------------------------------------------------
  🔴 Red Light – Stop

  🟢 Green Light – Go

Timed switching between signals

Basic Logic:
----------------------------------------------------------
⟶ Red ON → Green OFF

⟶ Delay(30 sec)

⟶ Green ON → Red OFF

⟶ Delay (45 sec) & Repeat

🌐 IoT Integration
----------------------------------------------------------
Flask web server runs on Raspberry Pi

Displays:
----------------------------------------------------------
↔️ LDR sensor values

↔️ IR sensor reading

↔️ Current street light status

↔️ Traffic light status

  Accessible via browser in same network

🧠 Embedded AI Concept
----------------------------------------------------------
The system uses intelligent decision-based automation:

IF Day → Street Lights OFF

IF Night → Street Lights ON (Dim Mode)

IF Motion → Full Brightness

Traffic Lights → Automatic Signal Control

This demonstrates real-time decision-making in embedded systems.

🔋 Advantages
----------------------------------------------------------
⚡ Energy efficient

⚡ Automated lighting

⚡ Smart traffic management

⚡ Cost-effective

⚡ Scalable for Smart Cities

🔮 Future Enhancements
----------------------------------------------------------
🚀 AI-based vehicle detection  

☁️ Cloud database integration 

📲 Mobile app monitoring

🌞 Solar-powered street lights  

📊 Real-time analytics dashboard 

🏙️ Smart city integration

----------------------------------------------------------

🚀 This project is a fully hands-on system built using Raspberry Pi, LDR and IR sensors, along with interactive web pages. It was designed and implemented to demonstrate real-time Embedded AI & IoT concepts in a practical, real-world way.
