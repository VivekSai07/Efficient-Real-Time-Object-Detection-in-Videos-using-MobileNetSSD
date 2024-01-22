# Efficient-Real-Time-Object-Detection-in-Videos-using-MobileNetSSD

## Overview

This project implements a real-time object detection system in videos using the MobileNetSSD (MobileNet Single Shot Multibox Detector) model. The goal is to efficiently identify and locate objects in streaming video, making it suitable for applications such as video surveillance, smart cameras, and real-time analytics.

## Features

- **MobileNetSSD Model:** Utilizes the MobileNet architecture for efficient object detection without compromising accuracy, making it suitable for real-time applications.
- **Real-Time Processing:** Achieves low-latency object detection, allowing for seamless integration into applications requiring live video analysis.
- **Video Input Support:** Supports various video formats as input, enabling flexibility for different sources such as webcam feeds, recorded videos, or live streams.
- **Bounding Box Visualization:** Highlights detected objects in the video frames with bounding boxes, providing a clear visual representation of the detection results.
- **Configurability:** Allows users to fine-tune detection parameters, such as confidence thresholds, to adapt the system to specific requirements.

## Getting Started

### Prerequisites

- Python 3.x
- OpenCV

### Installation

Clone the repository:
 ```bash
 git clone https://github.com/your-username/real-time-object-detection.git
 cd real-time-object-detection
```

Usage (for real-time video):

```bash
python real_time_object_detection.py --prototxt .\model\MobileNetSSD_deploy.prototxt.txt --model .\model\MobileNetSSD_deploy.caffemodel
```

Usage (for sample images):

```bash
python deep_learning_object_detection.py --image .\images\example_03.jpg --prototxt .\model\MobileNetSSD_deploy.prototxt.txt --model .\model\MobileNetSSD_deploy.caffemodel
```
