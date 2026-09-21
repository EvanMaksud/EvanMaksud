# Vehicle Line Counter

Counts how many vehicles cross a line drawn on a video frame.

## Summary

This project combines object detection and object tracking for a practical traffic-analysis workflow. YOLO detects vehicles in each frame, ByteTrack keeps consistent IDs across frames, and the app counts a vehicle once when its tracked center crosses the counting line.

## Features

- Webcam or video-file input.
- Click two points to draw a counting line.
- Optional fixed-line coordinates for repeatable runs.
- Counts cars, motorcycles, buses, and trucks using common COCO classes.
- Optional speed estimate using a meters-per-pixel calibration value.
- Roboflow hosted inference helper for image-level predictions.

## Stack

- Python
- OpenCV
- YOLO
- ByteTrack
- Roboflow inference SDK

## What I Learned

- How to combine detection with tracking instead of counting raw detections.
- Why camera angle and calibration matter for speed estimation.
- How to design simple controls for a video-analysis workflow.

