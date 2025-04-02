# Driver Monitoring System Using Raspberry Pi 5

A real-time AI-powered Driver Monitoring System (DMS) built on Raspberry Pi 5 that uses a camera module and a YOLOv8 deep learning model to detect critical driver behaviors. The system monitors whether the driver is wearing a helmet, using a phone, yawning, or showing signs of fatigue through open/closed eye detection. Upon detecting unsafe behavior, it triggers real-time alerts using a buzzer and LED to ensure on-road safety.

---

## 🚗 Overview

This system uses a camera feed and an object detection model (YOLOv8) to monitor the driver's actions and detect:
- Absence of helmet
- Phone usage while driving
- Yawning (a sign of drowsiness)
- Open/closed eye state to detect fatigue

When an unsafe action is detected, the system immediately alerts the driver with sound and light signals.

---

## 🧠 Features

- Real-time face and eye detection
- Drowsiness detection using Eye Aspect Ratio (EAR)
- Yawn detection using Mouth Aspect Ratio (MAR)
- Head pose estimation using facial landmarks
- Audio and/or visual alerts
- Lightweight and optimized for edge devices

---
## Training and Testing codes with datasets used
https://drive.google.com/file/d/1-0mxiys81Iu5sQh1CzK2BcBjtG11fEK7/view?usp=sharing
---

## 🛠️ Tech Stack

### Hardware:
- Raspberry Pi 5
- Raspberry Pi Camera Module (compatible with PiCamera2)
- Buzzer
- LED
- Breadboard, jumpers, resistors (for connections)

### Software & Libraries:
- Python 3
- [Ultralytics YOLOv8](https://docs.ultralytics.com/)
- OpenCV (`cv2`)
- GPIO Zero (`gpiozero`)
- PiCamera2 (`picamera2`)
- time (standard library)
