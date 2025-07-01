# Advanced-Aerial-Drone-Detection-System

This project demonstrates real-time drone detection using YOLOv5 and OpenCV. It detects drones in real-time and displays a warning when a drone is detected inside or near a defined rectangle.

![proj_4](https://github.com/Ayushkumawat/Advanced-Aerial-Drone-Detection-System/assets/76219349/dd32fa52-d6e9-4967-ae02-57ee70070a66)

## Features

- Real-time drone detection using YOLOv5 with detection coordinates and confidence percentage.
- No Code: Interactive and dynamic detection boundary creation and adjustment.
- A warning message is displayed when a drone is detected inside or near the set boundary.

![1](https://github.com/user-attachments/assets/d74354c7-fe39-4c8e-9e4d-39a9ddec0c45)

## Installation

1. Clone the repository:
```
   - git clone https://github.com/Ayushkumawat/Advanced-Aerial-Drone-Detection-System
```
2. Inside your project directory, create a virtual environment
```
   - python -m venv venv
```
3. Activate the virtual environment
```
   - .\venv\Scripts\activate       
```
2. Install the required Python libraries:
```
   - pip install -m requirements.txt
```
3. Run the script:
```
   - python Advanced_Drone_Detection.py
```

## Benefits
1. Enhanced Security
Real-time detection of drones for improved security in airports, public events, and restricted areas.

2. Automated Monitoring
Reduce manual surveillance by automating the drone detection process using computer vision and machine learning.

3. Customizable and Interactive
Define and adjust the detection area using an interactive rectangle for accurate and adaptable detection.

4. Real-time Feedback
Instant detection and warning messages provide immediate responses to potential drone threats.

5. Open-source and Extendable
You can access the open-source codebase for customization and integration into existing security systems.

6. Scalable and Cost-effective
Efficient utilization of resources with a balance of accuracy and performance, resulting in cost savings.

## About the Dataset

![WhatsApp Image 2023-12-02 at 12 17 17 AM](https://github.com/user-attachments/assets/73397d90-b350-4b27-901d-8c902257df80)

The Drone Detection model was trained on a diverse dataset consisting of 1400 images of different types of drones. The dataset was carefully curated and labeled to ensure accurate annotations. It covers a wide range of drone variations, sizes, orientations, and backgrounds.

The dataset was prepared using the Roboflow platform and exported through its API. This streamlined the dataset preparation process and ensured high-quality data inputs for training the model.

The availability of this diverse and well-annotated dataset enables the Drone Detection model to learn from a wide range of drone images, resulting in improved accuracy and reliability in real-world detection scenarios.

The dataset used in this project can be downloaded from [here.](https://universe.roboflow.com/drone-detection-ehdcs/drone-dataset-by-ayushkumawat)

![df002233-cd13-44c0-b5f8-51623015146f](https://github.com/Ayushkumawat/Advanced-Aerial-Drone-Detection-System/assets/76219349/53c582dc-8a31-47a6-bf81-71bf8e7409f0)

![3c146082-7f6b-4c0c-8cc2-ad7728771c87](https://github.com/Ayushkumawat/Advanced-Aerial-Drone-Detection-System/assets/76219349/31d8ac4e-1753-44be-91b5-c801473fce93)

![d22ec15f-7f61-4053-b7cd-7402ece65116](https://github.com/Ayushkumawat/Advanced-Aerial-Drone-Detection-System/assets/76219349/85b413e1-67cd-4b89-bde7-70e6fe6ec8f5)

## Usage

The script will open a live video feed from the default camera.
   - To create a rectangle, click and drag the mouse on the video feed to define the four corners of the rectangle.
   - The rectangle can be adjusted by dragging the corners.
   - A warning message will be displayed whenever a drone is detected inside or near the rectangle.
   - Press 'q' to quit the program.

## Customization

- You can modify the `classes` list in the code to include or exclude specific classes of objects for detection.
- Adjust the confidence threshold (`conf`) to control the sensitivity of detection.
- Experiment with different YOLOv5 model sizes for performance and accuracy trade-offs.
