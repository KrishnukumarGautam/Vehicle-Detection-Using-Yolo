# Vehicle-Detection-Using-Yolo
🚦 Traffic Vehicle Detection & Counting using YOLOv8

This project implements real-time vehicle detection, tracking, and counting using YOLOv8
 in Google Colab. The system processes traffic videos, detects multiple vehicle classes (car, bus, truck, motorcycle, bicycle), tracks them with unique IDs, and maintains per-class counts across the video.

📌 Features

✅ YOLOv8-based detection (state-of-the-art object detection model).

✅ Custom lightweight tracker (centroid-based object matching).

✅ Unique vehicle counting (cars, buses, trucks, motorcycles, bicycles).

✅ Live overlay panel with per-class counts.

✅ Preview mode – processes first 5 seconds for quick testing.

✅ Final output video with bounding boxes, labels, IDs, and counts.

🛠️ Requirements

Python 3.8+

Google Colab / Jupyter Notebook

Libraries:

ultralytics

torch

opencv-python

matplotlib

sympy==1.13.3 (fixes YOLO bug)

📂 Project Structure
├── traffic_detection.ipynb   # Google Colab notebook
├── Trafficsmall.mp4          # Input traffic video
├── preview.mp4               # 5-sec preview output
├── output_Trafficsmall.mp4   # Final processed video
└── README.md                 # Project documentation

🚀 How to Run

Upload video to Colab / Google Drive
Place your input video (e.g., Trafficsmall.mp4) in Google Drive.

Open the Notebook in Google Colab
Run the provided code cells step by step.

Preview Output

A 5-second preview video (preview.mp4) will be generated for validation.

Full Processing

The entire video will be processed and saved as output_<filename>.mp4.

📊 Output Example

The final output video includes:

Bounding boxes around vehicles.

Labels with vehicle type & ID.

Live counter of unique detected vehicles per class.

Example:

🚗 Cars: 12
🚌 Buses: 3
🚛 Trucks: 5
🏍 Motorcycles: 4
🚲 Bicycles: 2

🎯 Use Cases

Smart traffic monitoring

Automated traffic surveys

Vehicle density analysis

Research on intelligent transport systems

🤝 Credits

Ultralytics YOLOv8
 for object detection.

OpenCV for video processing & visualization.

Custom implementation of centroid-based tracking.
