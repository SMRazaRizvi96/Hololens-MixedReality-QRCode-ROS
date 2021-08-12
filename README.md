# Hololens-MixedReality-QRCode-ROS
This repository contains a Unity project that can be deployed on a Hololens 2.
This project has a Hologram cube which can be grabbed and placed anywhere in the environment. Moreover, this project can also detect QR codes, and you will also be able to receive the Pose of the hologram Cube, and the the QR Code detected, inside ROS through a TCP Connection.

## How to Run
- Clone the 'Hololens-MR-QR-CodeTracking-ROS' folder into you windows
- Clone the 'hololens_msgs' in your ROS Workspace in Ubuntu
- Clone the 'unity_robotics_demo' from [this link](https://github.com/Unity-Technologies/Unity-Robotics-Hub/tree/main/tutorials/ros_unity_integration/ros_packages) and run 'catkin_make'
- Open the 'Hololens-MR-QR-CodeTracking-ROS' project in Unity.
    - 
    - Build a Universal Windows Platform application.
    -  File -> Build Settings 
    -  Add Open Scenes
    -  Platform: Universal Windows Platform
    -  Target Device: HoloLens
    -  Build (This will open the folder of this project. Create a new folder 'Builds' and select this folder)

- After the build is completed, open the Visual Studio Solution file from the Build folder
- 

## Software Versions

- Unity Hub 2.4.3
- Unity Version 2020.3.12f1
- Mixed Reality Toolkit Foundation 2.7.0
- Mixed Reality Toolkit Tools 2.7.0
- Mixed Reality OpenXR Plugin Version 1.0.0
- Mixed Reality Toolkit Standard Assets Version 2.7.0
- NuGetForUnity 3.0.2
- Microsoft Mixed Reality QR Version 0.5.2112 (NuGet Package)
- Visual Studio 2019
- ROS TCP Connector Version 0.5.0-preview
- Ubuntu 18.04
- ROS Melodic
