# Autonomous Driving Stack using OpenCV

## Overview

This project implements the core components of a simple autonomous driving stack:

- Lane Detection
- Basic Perception
- Basic Control Simulation

The system processes dash-cam videos and estimates the steering direction based on detected lane boundaries.

## Features

- Grayscale conversion
- Gaussian Blur
- Canny Edge Detection
- Region of Interest (ROI)
- Hough Line Transform
- Lane Detection
- Lane Center Estimation
- Vehicle Offset Calculation
- Steering Simulation (LEFT, RIGHT, STRAIGHT)

## Technologies

- Python
- OpenCV
- NumPy
- Google Colab

## Input

Dash-cam video (.mp4)

## Output

Processed video with:

- Detected lane lines
- Offset information
- Steering decision

## Author

Shahul Hameed