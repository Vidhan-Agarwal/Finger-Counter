## Finger Counter with Hand Gestures

This project implements a finger counter using your webcam and OpenCV library. Raise your hand and the application will display the number of fingers you're holding up!

**Features:**

* **Hand Tracking:** Utilizes a [hand_tracking_module.py](hand_tracking_module.py) to detect and localize your hand and fingers in the webcam feed.
* **Finger Counting:** Detects open fingers based on hand posture and displays the count on the screen.
* **Visual Overlays:** Overlays images of hands displaying different finger counts for better visualization.
* **Frame Rate Display:** Shows the real-time frame rate of the application.

**Requirements:**

* Python 3.x
* OpenCV library (`pip install --upgrade opencv-python`)
* Mediapipe library(`python -m pip install mediapipe`)
* [hand_tracking_module.py](hand_tracking_module.py)
* A folder containing images representing different finger counts.[finger_counter](finger_counter)

**Instructions:**

1. Download or clone the repository.
2. Install the required libraries.
3. Make sure you have `hand_tracking_module.py` in the same directory or adjust the path in the code (if necessary).
4. Create a folder named "finger_counter" in the same directory as your Python script.
5. Place images representing different finger counts (e.g., hand with 1 finger up, hand with 2 fingers up, etc.) inside the "finger_counter" folder.
6. Run the application using `python finger_counter.py` (or the appropriate filename).

