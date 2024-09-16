# Motion Detection Alert System

## 📄 Overview
The Motion Detection Alert System is a smart security solution designed to detect motion in real-time without the need for any physical sensors! 🌟 This system uses advanced computer vision techniques to monitor an area through a camera feed, and if any suspicious movement is detected, an alert email is automatically sent to the concerned authority. 🚨📧

With this project, you can enhance your security by detecting any motion in real-time and receiving instant notifications, making it ideal for home security, office surveillance, or monitoring sensitive areas. 🏠🏢

## 💡 Project Features
- Real-Time Motion Detection: Detects movement in real-time using computer vision algorithms. 📹⚡
- No Physical Sensors Required: Works entirely through video feed; no need for additional hardware. 💻📷
- Alert Email: Automatically sends an alert email to the concerned authority when motion is detected. 📧🚨
- Customizable Detection Sensitivity: Adjust the sensitivity of motion detection to reduce false alerts. 🎛️🔍
- Simple and Lightweight: Built using lightweight tools that ensure fast and efficient detection. 🏃‍♂️

## 🛠️ Tech Stack
- Python 🐍
- OpenCV 👁️
- smtplib for sending email notifications ✉️
- NumPy 🔢

## ⚙️ How it Works
- Capture Video Feed: The system captures a live video stream through the webcam or any connected camera device. 🎥
- Motion Detection: It continuously monitors the video feed and compares each frame to detect changes in movement.
- Send Alert: If any motion is detected, the system sends an alert email to the predefined recipient. 🚨📧
- Real-Time Monitoring: The system continues to monitor for further movement and can send multiple alerts if necessary.

## 🚀 How to Run the Project

1. Clone the Repository:
```
git clone https://github.com/Vedant3000/Motion-Detection-Alert-System.git

```
2. Install the requirements from requirements.txt
```
pip install -r requirements.txt
```
3. Install ipcam application in your mobile phone. Make sure that your PC and mobile must be connected to same network. Insert your mobile phone camera IP Address in the code, which can be extracted from ipcam.
4. Update Email Settings: Open the config.py file and add your SMTP server details and recipient email address.
5. Run the application
```
python motion-det2.py
```

## Screenshots
![Motion Detection Screenshot](images/results.png)


