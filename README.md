
![face mesh](https://github.com/user-attachments/assets/57526f6a-61a0-4223-9522-febf9d38c096)
![face mesh](https://github.com/user-attachments/assets/57526f6a-61a0-4223-9522-febf9d38c096)
📷 Python Camera Capture using OpenCV

This project demonstrates how to access and display live video from your system’s webcam using Python and OpenCV.

📌 Features

Opens the default webcam

Displays live camera feed in a window

Safely releases the camera when closed

Press q to exit the camera window

🛠️ Requirements

Make sure you have the following installed:

Python 3.x
🎮 Controls

q → Quit the camera window and stop the program

📄 Code Explanation (Simple)

cv2.VideoCapture(0) → Opens the default camera

cap.isOpened() → Checks if the camera opened successfully

cap.read() → Reads frames from the camera

cv2.imshow() → Displays the video frame

cv2.waitKey(1) → Waits for key input (checks for q)

cap.release() → Releases the camera

cv2.destroyAllWindows() → Closes all OpenCV windows

⚠️ Common Issues

Camera not opening?

Make sure no other app is using the camera

Try changing VideoCapture(0) to VideoCapture(1)

Check camera permissions in your OS

📚 Use Cases
Beginner computer vision projects

Face detection

Motion detection

Video recording applications

👤 Author

Pranay Jadhao

![camera](https://github.com/user-attachments/assets/348e004c-6a4b-4772-98dc-8d95b19ffee7)
