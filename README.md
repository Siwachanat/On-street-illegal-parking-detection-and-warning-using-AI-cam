This project aims to address the issue of illegal parking in school areas by utilizing an AI camera to detect and warn drivers. The system leverages the DFRobot Huskylens AI camera to identify vehicles parked in prohibited zones and employs an ESP32 microcontroller and Arduino Cloud to send alerts and notifications.

Components
Hardware:
DFRobot Hackster EEDU Kit
DFRobot FireBeetle ESP32-E IoT Microcontroller
LED, Super Bright
Software:
Arduino IoT Cloud
Arduino Web Editor
Autodesk Fusion 360
Tools:
Soldering iron
Project Goals
Detect illegal parking in designated areas.
Warn drivers of violations.
Improve traffic flow and safety in school environments.
System Architecture
The system consists of two main components:

Smart AI Camera Pole:

Detects vehicles in prohibited areas using the Huskylens AI camera.
Reports violations to the Arduino Cloud.
Utilizes a CCTV housing for protection.
Employs Arduino Cloud variables for command and detection status.
Smart Warning Sign Pole:

Receives commands from the Arduino Cloud.
Activates warning lights and sounds.
Features a custom-designed PCB and 3D-printed housing.
Workflow
Vehicle Detection: The AI camera identifies vehicles parked in restricted zones.
Violation Report: The system sends a violation report to the Arduino Cloud.
Warning Activation: The Arduino Cloud triggers the warning sign pole.
Alert: The warning sign pole emits a visual and audible alert.
Future Improvements
Enhanced Alert System: Implement a more powerful speaker and amplifier for louder warnings.
Solar Power Integration: Add solar panels for self-sufficiency.
Data Analysis: Analyze collected data to identify trends and improve parking management.
