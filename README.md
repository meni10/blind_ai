# Blind Object Detection – AI Assistant for the Visually Impaired 🚀

An AI-powered assistive application that helps visually impaired people identify objects in their surroundings through real-time object detection and voice feedback.

The application uses a live webcam and a pre-trained YOLOv5 model to detect common objects and announces their names using text-to-speech.

## ⚙️ Key Features

- **Real-Time Object Detection:** Detects common objects using a pre-trained YOLOv5 model.
- **Voice Feedback:** Announces detected object names using text-to-speech.
- **Live Camera Support:** Captures surroundings through a webcam.
- **Indoor & Outdoor Modes:** Provides separate modes for different environments.
- **GUI Interface:** Provides a simple graphical interface using PyQt5.

## 🧰 Technologies Used

- **Programming Language:** Python
- **Object Detection:** YOLOv5
- **Computer Vision:** OpenCV
- **Deep Learning:** PyTorch
- **GUI:** PyQt5
- **Text-to-Speech:** pyttsx3
- **Image Processing:** NumPy, Pillow

## 🧠 How It Works

1. Launch the application using the PyQt5 interface.
2. Select Indoor or Outdoor mode.
3. The webcam captures live video frames.
4. OpenCV processes the captured frames.
5. The pre-trained YOLOv5 model detects and identifies objects.
6. The detected object names are passed to the pyttsx3 library.
7. The application announces the detected objects through voice output.

## 🎯 Project Impact

- Helps visually impaired users identify surrounding objects.
- Provides audio feedback without requiring users to read a screen.
- Supports better environmental awareness.
- Aims to improve independence in everyday activities.

## ▶️ How to Run

**Prerequisites:**
- Python 3.8+
- Webcam
- Required Python libraries

**1. Clone the repository
