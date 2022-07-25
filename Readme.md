# Self Driving Car By Lane Detection
This project represents a self driving car that depends on the automatic lane detection and following, the car also has a manual mode for easier usability.
## Steps

* the camera on the car starts streaming images to the server.
* the flask server applies computer vision algorithms to detect the lane and the angle of the drift needed, such as color detection and lines detection.
* the server sends the angle to ESP through Wi-Fi.
* the ESP controls the motors in 3 directions right, left or forward.
* ultrasound sensor detect near objects and stops the car in that direction.
* RF ID is used to detect if the car passe a certain boundaries.
## components
* 4 wheeled car
* camera (mobile camera was used)
* ESP 
* ultrasonic sensor 
* RF ID 
## Manual mode steps
* using Flutter app send the direction to the server
* the Flask server sends it to the ESP and moves or stops the car.

```images of the app , car, lanes, detected lanes