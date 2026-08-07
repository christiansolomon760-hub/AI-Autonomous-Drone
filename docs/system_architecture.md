# System Architecture

## Overview

This project aims to create an autonomous drone system capable of using artificial intelligence to perceive its environment, make decisions, and navigate independently.

## High-Level Components

### 1. Perception System
Responsible for understanding the environment.

Possible technologies:
- Computer vision
- Object detection
- Camera processing
- AI models (YOLO)

### 2. Decision-Making System
Responsible for deciding what actions the drone should take.

Responsibilities:
- Analyse sensor/camera information
- Choose navigation actions
- Avoid obstacles
- Plan movement

### 3. Navigation System
Responsible for guiding the drone.

Responsibilities:
- Path planning
- Position estimation
- Route optimisation

### 4. Control Interface
Responsible for communicating decisions to the drone hardware.

Responsibilities:
- Send movement commands
- Receive sensor information
- Interface with flight controller

## Software Stack (Initial Ideas)

Programming Languages:
- Python
- C++

AI/ML:
- Computer Vision
- Neural Networks
- Object Detection Models

Simulation:
- To be researched

## Current Role

My focus is the AI and software development side of the project, while hardware development is being explored separately.
