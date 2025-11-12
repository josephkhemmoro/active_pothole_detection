# Pothole Detection using YOLOv8

This repository contains a real-time object detection model designed to identify potholes on road surfaces. The primary goal is to create a solution that could be used for automated road inspection, driver-assistance systems (ADAS), or municipal maintenance alerts.

This model is built using **YOLOv8** and trained on a custom dataset of road images.

## Features
* Real-time detection of potholes from video streams or static images.
* Draws bounding boxes around identified hazards.
* Built with Python, OpenCV, and the Ultralytics YOLOv8 library.

## Demo
`[A GIF or screenshot of your model finding potholes would be perfect here]`

## Installation
```bash
# Clone the repository
git clone [https://github.com/](https://github.com/)[YourUsername]/[Your-Repo-Name].git
cd [Your-Repo-Name]

# Install dependencies
pip install -r requirements.txt
```

## Usage
To run the model on a new image, video, or live webcam feed:
```bash
python detect.py --weights [path/to/your/pothole_model.pt] --source [path/to/video.mp4 or 0 for webcam]
```