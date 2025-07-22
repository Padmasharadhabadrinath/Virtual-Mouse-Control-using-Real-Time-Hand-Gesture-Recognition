**🖱️ Virtual Mouse Control using Real-Time Hand Gesture Recognition**

This project uses a webcam to track hand gestures and control the mouse pointer in real time using computer vision and hand tracking libraries like MediaPipe, OpenCV, and PyAutoGUI.

**1.📌 Features**

🖐️ Tracks hand landmarks using MediaPipe

👆 Moves mouse cursor using index fingertip position

🖱️ Detects click gesture when thumb and index finger come close

🔴 Real-time video capture and drawing of hand landmarks

💻 Fully functional virtual mouse controlled by hand gestures

**2.🛠️ Technologies Used**

Library

cv2 (OpenCV)

mediapipe

pyautogui

**Purpose**

cv2 (OpenCV)-Capture video and display frames

mediapipe-Hand detection and landmarks

pyautogui-Move and click mouse

**3.📁 Project Structure**

📁 Virtual-Mouse-Control-using-Real-Time-Hand-Gesture-Recognition

mousehandgesture.py        # Main script for virtual mouse control

README.md                  # Project documentation

**4.⚙️ How It Works**

Captures webcam video using OpenCV.

Detects hand landmarks using MediaPipe Hands.

Tracks the index fingertip (id 8) to move the mouse cursor.

Tracks the thumb tip (id 4) to detect clicking gesture.

If the vertical distance between index and thumb is below a threshold → Click!

**5.▶️ How to Run**

Install required libraries (preferably in a virtual environment):

pip install opencv-python mediapipe pyautogui

Run the script:

python mousehandgesture.py

Control:

Move your index finger to control the mouse.

Pinch your index and thumb together to perform a click.

Press ESC key to quit.

**6.🖼️ Sample Output**

👁️ The live webcam feed will show hand tracking in action with cursor movement and clicking feedback printed in console.



