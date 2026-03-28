Setup Instructions – Interior and Product Design Using AR

Project Overview
This project is an Augmented Reality (AR) application developed using Unity that allows users to visualize and place virtual furniture and products in real-world environments using a mobile device.

Technology Stack

Unity (2022.x or later)
AR Foundation
Google ARCore
C#
Android SDK / NDK
3D Models (FBX format)

Project Structure

Interior-And-Product-Designing-Using-AR/

|-- src/
| |-- Assets/
| |-- Packages/
| |-- ProjectSettings/

|-- docs/
|-- README.md
|-- requirements.txt
|-- architecture.png
|-- demo_video_link.txt
|-- setup_instructions.txt

Prerequisites

Before running the project, ensure you have:

Unity Hub installed
Unity Editor (2022.x or later)
Android Build Support (SDK, NDK, OpenJDK)
ARCore-supported Android device
USB Debugging enabled

Installation Steps

Clone the Repository

git clone https://github.com/PRJWL3/Interior-And-Product-Designing-Using-AR.git

Open Project in Unity
Open Unity Hub
Click Open Project
Select the project folder
Configure AR Settings
Go to Edit → Project Settings → XR Plug-in Management
Enable ARCore for Android
Open Package Manager
Ensure AR Foundation is installed
Connect Android Device
Enable Developer Options
Enable USB Debugging
Connect phone via USB
Build and Run
Go to File → Build Settings
Select Android Platform
Click Switch Platform
Click Build and Run

Application Usage

Move the camera to detect surfaces
Tap on screen to place objects
Use gestures to:
Move objects
Rotate objects
Scale objects

Important Notes

Ensure your device supports ARCore
Use proper lighting for better plane detection
Do not include Library, Temp, or Logs folders

Troubleshooting

Issue: AR not detecting surfaces

Ensure sufficient lighting
Move device slowly

Issue: Build failed

Reinstall Android Build Support via Unity Hub

Issue: Objects not visible

Check camera permissions
Ensure plane is detected

Future Enhancements

AI-based furniture recommendations
Multi-user AR collaboration
Improved lighting and realism
E-commerce integration
Cross-platform support (iOS + Android)
