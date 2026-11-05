# Visual Assistance for Visually Impaired Individuals Using IoT

An AI-powered Smart Blind Stick that helps visually impaired individuals by detecting obstacles, identifying objects, recognizing Indian currency, and reading printed text through voice feedback.

## About the Project

The **Visual Assistance for Visually Impaired Individuals Using IoT** is an assistive technology project developed to support visually impaired people in their daily activities.

The system integrates Artificial Intelligence, Computer Vision, and Internet of Things (IoT) technologies to provide information about the user's surroundings. It uses a camera, ultrasonic sensor, and Raspberry Pi to perform different tasks such as object detection, obstacle detection, currency recognition, and text recognition.

The detected information is converted into speech, allowing users to receive audio instructions through a speaker or earphones.

## Features

- **Object Detection:** Identifies objects in the surrounding environment using YOLO.
- **Obstacle Detection:** Detects nearby obstacles using an HC-SR04 ultrasonic sensor and provides alerts.
- **Currency Recognition:** Identifies Indian currency notes and their denominations using a trained detection model.
- **Text Recognition (OCR):** Extracts printed text from books, documents, labels, and signboards.
- **Text-to-Speech Conversion:** Converts recognized information into spoken words.
- **Audio Feedback:** Provides voice-based information through a speaker or earphones.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| YOLO | Object and currency detection |
| OpenCV | Image processing |
| OCR | Printed text recognition |
| Raspberry Pi 4 | Main processing unit |
| HC-SR04 | Ultrasonic obstacle detection |
| Raspberry Pi GPIO | Sensor interfacing |
| Text-to-Speech | Voice output |

## Hardware Requirements

- Raspberry Pi 4
- Camera module / USB camera
- HC-SR04 Ultrasonic Sensor
- Speaker or earphones
- Portable power supply / Power bank
- Jumper wires
- Supporting electronic components

## Software Requirements

- Python 3
- Raspberry Pi OS
- OpenCV
- YOLO and its required dependencies
- OCR library
- Raspberry Pi GPIO library
- Text-to-Speech library

## Working Principle

1. The camera captures images of the surrounding environment.
2. The YOLO model processes the images to identify objects.
3. The ultrasonic sensor measures the distance between the device and nearby obstacles.
4. The currency recognition module identifies Indian currency notes.
5. The OCR module extracts text from printed materials.
6. The Text-to-Speech module converts the recognized information into speech.
7. Audio feedback is delivered to the user through a speaker or earphones.

## Project Structure

```text
Visual-Assistance-using-IoT/
│
├── Currency-Detection/
│
├── Object-Detection/
│
├── image_to_voice/
│
├── ultracheck.py
│
└── README.md
```

## Installation and Execution

**1. Clone the repository**

```bash
git clone https://github.com/aishwaryas1234/Visual-Assistance-using-IoT.git
```

**2. Navigate to the project directory**

```bash
cd Visual-Assistance-using-IoT
```

**3. Install the required Python libraries**

Install the dependencies required by each module. For example:

```bash
pip install opencv-python numpy
```

Install any additional libraries required by the individual scripts and models.

**4. Connect the hardware**

Connect the camera, ultrasonic sensor, and audio output to the Raspberry Pi according to the hardware configuration.

**5. Run the required module**

Execute the respective Python scripts for object detection, currency recognition, text recognition, or obstacle detection.

*Note: Configure the model paths, camera settings, GPIO pins, and other dependencies before execution.*

## Applications

- Assisting visually impaired individuals in identifying everyday objects.
- Providing alerts about nearby obstacles.
- Recognizing Indian currency denominations.
- Reading printed text through voice output.
- Supporting independent movement and daily activities.

## Future Enhancements

- Support for multiple regional languages.
- Improved object and currency recognition accuracy.
- Faster image processing and response time.
- Improved battery life and portability.
- Integration of additional AI-based assistive features.

## Project Contributors

- Khushi S
- Pragathi Niranjan
- Shashank Bhavani Shankar

Acknowledgement

We sincerely thank our project guide and faculty members for their guidance and support throughout the development of this project.

---

**Project:** Visual Assistance for Visually Impaired Individuals Using IoT

**Domain:** Artificial Intelligence | Internet of Things | Computer Vision | Assistive Technology
