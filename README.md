# Pothole Detection using YOLOv8

This repository contains a real-time object detection model designed to identify potholes on road surfaces. The primary goal is to create a solution that could be used for automated road inspection, driver-assistance systems (ADAS), or municipal maintenance alerts.

This model is built using **YOLOv8** and trained on a custom dataset of road images.

## Features

* Real-time detection of potholes from video streams or static images.
* Draws bounding boxes around identified hazards.
* Built with Python, OpenCV, and the Ultralytics YOLOv8 library.

## Demo

[Live Demo](pothole_detection.gif)

## Installation

```bash
# Clone the repository
git clone https://github.com/josephkhemmoro/active_pothole_detection.git
cd active_pothole_detection

# Install dependencies
pip install ultralytics opencv-python