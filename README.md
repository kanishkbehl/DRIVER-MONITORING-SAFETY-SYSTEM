# Driver Monitoring System Using Raspberry Pi 5

A real-time Driver Monitoring System (DMS) built using Raspberry Pi 5 designed to enhance road safety by detecting signs of driver drowsiness and distraction. This project uses computer vision and deep learning techniques to monitor driver alertness and provide alerts in case of unsafe driving behavior.

## 🚗 Overview

This system captures live video feed using a connected camera and analyzes the driver's facial features to detect:
- Eye closure and drowsiness
- Helmet wear
- Yawning
- Distraction or inattention

---

## 🧠 Features

- Real-time face and eye detection
- Drowsiness detection using Eye Aspect Ratio (EAR)
- Yawn detection using Mouth Aspect Ratio (MAR)
- Head pose estimation using facial landmarks
- Audio and/or visual alerts
- Lightweight and optimized for edge devices

---
TRAINING AND TESTING CODES WITH THE DATASET
https://drive.google.com/file/d/1-0mxiys81Iu5sQh1CzK2BcBjtG11fEK7/view?usp=sharing
---

## 🛠️ Tech Stack

### Hardware:
- Raspberry Pi 5
- Raspberry Pi Camera Module or USB Webcam
- Buzzer/Speaker for alert (optional)
- 5" or 7" touchscreen display (optional)

### Software & Libraries:
- Python 3
- OpenCV
- Dlib or MediaPipe
- NumPy
- imutils
- playsound / pygame (for audio alerts)
