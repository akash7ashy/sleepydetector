# Driver Drowsiness Detection Project
Driver drowsiness detection is a project built using Dlib and OpenCV with Python as a backend language.

Logic of project
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library. The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which we determine whether the eyes are open or they are closed.


## Project Description
This project aims to detect driver drowsiness in real-time using computer vision techniques. It can be used to alert drivers who are drowsy while driving, thereby helping to prevent accidents caused by drowsy driving.
The working of the project
As you can see the above screenshot where the landmarks aredetected using the detector.
Now we are taking the ratio which is described as 'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'.
Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.
## Getting Started
![image](https://github.com/akash7ashy/sleepydetector/assets/131885338/049a51a1-5fe7-4ec1-b123-1ca3b998d509)
![image](https://github.com/akash7ashy/sleepydetector/assets/131885338/36ab4895-7cf0-496e-b097-4cce9f4a80cd)
![image](https://github.com/akash7ashy/sleepydetector/assets/131885338/03fd0896-b4fe-4a73-ab5e-2d7568a37329)




### Prerequisites
- Python 3.7 or later
- OpenCV
- Dlib
- imutils
- playsound

### Installation
1. Clone the repo: `git clone https://github.com/akash7ashy/driver-drowsiness-detection.git`
2. Install the prerequisites: `pip install -r requirements.txt`

## Usage
Run the main script: `python driver_drowsiness_detection.py`

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


##demo of the project
https://drive.google.com/file/d/1nwKDMCwhsro8TBGQPQXx8Bin_gg1tc9F/view?usp=drive_link

