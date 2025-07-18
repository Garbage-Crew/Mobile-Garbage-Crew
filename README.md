# AI Trash Detection and Mapping Project

## Project Overview
This project is a proof-of-concept AI system that detects trash, classifies the type of trash, and logs the location of each detection on a map. The long-term goal is to deploy this system on an RC car, to autonomously navigate areas, identify trash in real time, and map its location for cleanup and data analysis purposes.

## Note on Hardware
Due to time and budget constraints, we did not deploy this project on an RC car. However, the code should be compatible with RC cars equipped with onboard compute (e.g., NVIDIA Jetson Nano or equivalent), camera modules, and GPS sensors. The purpose of this project is to serve as a prototype that can be easily adapted to an RC car platform in the future. If the script doesn't work directly, feel free to change the script to fit your specific scenario.

A link to an RC car we thought looked good (Not proven to work): https://www.waveshare.com/jetracer-pro-ai-kit.htm

## Current Setup
This script was developed for the following theoretical hardware setup:
- NVIDIA Jetson Nano (or a device capable of running AI scripts)
- USB or CSI camera module for live video feed
- USB GPS module for real-time location tracking
- Wi-Fi for data transmission or local logging

## Project Structure

...to be completed...



## How It Works
1. The AI model runs real time inference on the camera feed to detect and classify trash.
2. When trash is detected, the system records the trash type, timestamp, and GPS coordinates.
3. Detection data is logged into a CSV file and can optionally be visualized on a live map.
4. The system can run locally on the device or stream data to a remote dashboard for data analysis.

## Future Expansion Goals
- Deploy the system on an RC car for full autonomy
- Implement real time trash mapping with heatmaps and location clustering
- Add autonomous navigation and route planning features
- Integrate cloud-based analytics and dashboard visualization
- Reacts to humans or animals in a way that wont harm it or the opposite party

## Project Status
- Proof-of-concept completed with static setup
- RC car deployment planned for future iterations depending on resource availability


## !! ALL FEATURES MENTIONED MAY NOT BE FULLY OPTIMIZED NOR IMPLEMENTED, THIS IS ESSENTIALLY A THEORETICAL SCRIPT !!
