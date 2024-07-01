# Drowsiness-detection
DROWSINESS DETECTION SYSTEM

Overview:
---------
This Drowsiness Detection System is designed to monitor drivers for signs of drowsiness and alert them to take necessary actions to prevent accidents. The system uses a combination of computer vision and machine learning techniques to detect early signs of fatigue and drowsiness in real-time.

Features:
---------
- Real-Time Detection: Continuously monitors the driver’s face and eyes to detect signs of drowsiness.
- Eye Blink Detection: Measures the blink rate and duration to determine the level of alertness.
- Yawning Detection: Detects yawns by analyzing mouth movements.
- Alarm System: Alerts the driver with an audible alarm if drowsiness is detected.
- User-Friendly Interface: Simple and intuitive interface for easy use.

Technologies Used:
------------------
- OpenCV: For real-time video processing and facial feature detection.
- Dlib: For accurate facial landmark detection.
- Machine Learning: Classifiers to determine drowsiness levels based on eye and mouth movements.
- Python: Core programming language for implementing the system.

Installation:
-------------
1. Clone the Repository
    ```bash
    git clone https://github.com/your-username/drowsiness-detection-system.git
    cd drowsiness-detection-system
    ```

2. Install Dependencies
    ```bash
    pip install -r requirements.txt
    ```

3. Run the System
    ```bash
    python main.py
    ```

Usage:
------
1. Ensure your webcam is connected.
2. Run the system using the command provided above.
3. The system will start monitoring for signs of drowsiness.
4. If drowsiness is detected, an alarm will sound to alert the driver.

Contributing:
-------------
Contributions are welcome! Please feel free to submit a Pull Request.

License:
--------
This project is licensed under the MIT License.
