# Fire & Smoke Detection Using YOLO on Raspberry Pi

## Description
This project implements fire and smoke detection using YOLO (You Only Look Once) on a Raspberry Pi with IoT-enabled smart cameras. Images are captured and processed to detect fire or smoke, then alerts are sent to local authorities.

## Dataset & Training

Datasets of fire and smoke images annotated with bounding boxes

Trained using Roboflow

Training involved 180 epochs, with careful parameter tuning for confidence and accuracy

## Modeling & Implementation

Algorithm: YOLO for real-time object detection

Deployment: Raspberry Pi with WiFi-enabled smart cameras

## Detection metrics:

Fire: 90.2% accuracy, 92.8% confidence

Smoke: 85.7% accuracy, 85.1% confidence

Real-time detection time for fire: 17.9–31.9 seconds with highest confidence 93.8%

## Key Takeaways

IoT-enabled cameras can detect hazards in both indoor and outdoor environments

Small hyperparameter changes significantly affect model performance

Demonstrates the versatility of ML + IoT for real-world automation

## Usage

Use a Raspberry Pi with camera module

Train the YOLO model on a custom fire/smoke dataset

Deploy with IoT integration to send alerts when hazards are detected
