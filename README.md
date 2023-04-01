## Duke Ignite Project
**The current Readme is generated by ChatGPT.**

This is a Flask web application that uses OpenCV and the cvzone library to track a user's hand movements on a live video feed from their webcam.

## Features
Uses the cvzone HandDetector class to detect and track the user's hand movements in real-time.
Displays the live video feed with the hand movements annotated on the screen.
Supports finger counting, with the number of fingers currently extended displayed on the screen.
Resizes the video feed to half the original size to improve performance.
Uses base64 encoding to efficiently transmit the video feed over HTTP.

## Installation
Clone the repository to your local machine.
Install the required Python packages listed in requirements.txt.
Run the application by executing python app.py.

## Usage
Open a web browser and navigate to http://localhost:5000.
Allow the application to access your webcam.
The live video feed should now appear in the browser window.
Move your hand in front of the webcam and observe the finger counting functionality.

## Future Improvements
Add support for detecting and tracking multiple hands at once.
Allow the user to choose whether to display the finger counting information on the screen.
Improve the performance of the video feed by using more efficient encoding methods.
Add support for more advanced hand tracking functionality, such as hand gestures.


