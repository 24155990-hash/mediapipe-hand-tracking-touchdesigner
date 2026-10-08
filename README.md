# Real-Time Hand Tracking with MediaPipe & TouchDesigner

A real-time computer vision project using MediaPipe and OpenCV for hand landmark detection, integrated with TouchDesigner for interactive visual applications.

## Overview

The project captures live video input, detects and tracks hand landmarks using MediaPipe, and processes the tracking data in TouchDesigner for real-time interaction.

## Tech Stack

- Python
- MediaPipe
- OpenCV
- TouchDesigner
- Git & Git LFS

## Features

- Real-time hand detection and tracking
- 21-point hand landmark detection
- Real-time tracking of hand position and movement
- Gesture-based interaction with TouchDesigner
- TouchDesigner `.tox` components and project files

## How It Works

1. Live video is captured through the camera.
2. MediaPipe detects the hand and identifies its 21 landmarks.
3. Landmark coordinates are processed in real time.
4. The tracking data is integrated into TouchDesigner.
5. Hand movement is used for interactive visual behaviour.

## Project Structure

```text
Handtracking/
├── MediaPipe Handtracking.toe
└── toxes/
    ├── MediaPipe.tox
    ├── hand_tracking.tox
    ├── face_tracking.tox
    └── ...