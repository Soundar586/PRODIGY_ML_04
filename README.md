# PRODIGY_ML_04
Hand Gesture Recognition
---
 
1. Hand Gesture Recognition using MediaPipe and OpenCV

This project implements a **real-time hand gesture recognition system** using Python, OpenCV, and MediaPipe. It detects hand landmarks from a webcam feed, identifies finger positions, and classifies gestures for single and both hands.

2. Features

* Detects **single-hand and dual-hand gestures**.
* Real-time video feed analysis using **OpenCV**.
* **MediaPipe Hands** for precise landmark detection.
* Predicts predefined signs such as **pointing, open palm, closed fist**, etc.
* Works with both **left** and **right hands** simultaneously.

3. Tech Stack

* **Python**
* **OpenCV**
* **MediaPipe**
* **Time** (for tracking gestures)

4. Installation

```bash
# Clone the repository
git clone https://github.com/Soundar586/PRODIGY_ML_04.git
cd PRODIGY_ML_04

# Install dependencies
pip install opencv-python mediapipe
```

5. Usage

```bash
python gesture_recognition.py
```

* Ensure your webcam is connected.
* The system will display a real-time video feed with gesture labels in **black text** at the bottom of the screen.

5. Example Gestures

| Gesture   | Description                    |
| --------- | ------------------------------ |
| Open Palm | All fingers extended           |
| Fist      | All fingers folded             |
| Pointing  | Index finger extended          |
| Peace     | Index & middle finger extended |
| Peace     |middle three finger extended    |

6. Folder Structure

```
PRODIGY_ML_04/
│
├── gesture_recognition.py   # Main script
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies
```

## License

This project is open-source and available under the [MIT License](LICENSE).

---

If you confirm the exact ML task for **PRODIGY\_ML\_04**, I can tweak this README to match perfectly.
Do you want me to make this **specific to your exact code and gestures**? That way it’s 100% accurate for your repo.
