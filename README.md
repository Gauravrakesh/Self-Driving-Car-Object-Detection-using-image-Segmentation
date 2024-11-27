# Object detection on a self driving car dataset using YOLO model and UNet architecture

## Overview

This project implements an **object detection system** for self-driving cars using the **YOLO (You Only Look Once)** model. The primary goal is to detect cars from images captured by a camera mounted on the vehicle. This notebook is based on the methodologies described in the YOLO papers by Redmon et al. (2016) and Redmon and Farhadi (2016).

### Objectives

By the end of this project,  we will learn how to:
- Detect objects in a car detection dataset.
- Implement **non-max suppression** to enhance detection accuracy.
- Calculate **intersection over union (IoU)** for bounding box evaluation.



# README for Autonomous Driving - Car Detection

## Overview

This project implements an **object detection system** for self-driving cars using the **YOLO (You Only Look Once)** model. The primary goal is to detect cars from images captured by a camera mounted on the vehicle. This notebook is based on the methodologies described in the YOLO papers by Redmon et al. (2016) and Redmon and Farhadi (2016).

### Objectives

By the end of this assignment, you will gain knowledge and working experience in:
- Detecting objects in a car detection dataset.
- Implementing **non-max suppression** to increase accuracy.
- Calculating **intersection over union (IoU)** for bounding box evaluation.
- Handling **bounding boxes**, a type of image annotation popular in deep learning.

## Problem Statement

You are working on a self-driving car. As a critical component of this project, you'd like to first build a car detection system. To collect data, you've mounted a camera to the hood of the car, which takes pictures of the road ahead every few seconds as you drive around.

## Implementation Steps

1. **Data Collection**: Images are captured by a camera mounted on the car.
2. **Model Setup**: Utilize the YOLO model for real-time object detection.
3. **Image Processing**: Preprocess images to make them suitable for the model.
4. **Object Detection**: Implement YOLO to detect cars in the images.
5. **Bounding Box Handling**: Use non-max suppression to filter overlapping bounding boxes.
6. **Evaluation**: Calculate intersection over union (IoU) to assess detection performance.

## Example Output

The notebook includes visualizations of detected objects with bounding boxes and confidence scores. For instance:

- Detected cars with confidence scores:
  - Car at coordinates (x1, y1) to (x2, y2) with a score of 0.89
  - Bus at coordinates (x1, y1) to (x2, y2) with a score of 0.67

## Conclusion

This project provides a foundational understanding of object detection in autonomous driving applications using deep learning techniques. Further enhancements may include training on larger datasets or integrating additional sensors for improved accuracy.

For further details or contributions, please refer to the code comments and documentation within the notebook.
