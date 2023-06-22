<<<<<<< HEAD
# Face-Recognition-Attendance-System

A face recognition attendance management system is an application that can detect and recognize human faces from an image or video feed, and then use that information to track attendance. The system can be implemented using various computer vision modules such as OpenCV, numpy, and face_recognition.

OpenCV is an open-source computer vision library that provides tools for image and video processing, including face detection and recognition. Numpy is a Python library used for scientific computing that provides support for multi-dimensional arrays and matrices, which can be useful for image processing and manipulation.

The face_recognition module is built on top of OpenCV and provides pre-trained models for face detection and recognition. It also includes functions for face alignment, encoding, and comparison.

To implement the attendance management system, the following steps can be taken:

Capture images or video feed from a camera
Use OpenCV for face detection and alignment
Use face_recognition to encode and compare faces for recognition
Match recognized faces with a database of known faces to track attendance
Store attendance data in a database or file for future reference.
Overall, the system can be a useful tool for tracking attendance in various settings, such as schools, workplaces, or events.
=======
# Face_recognition_based_attendance_system
A python GUI integrated attendance system using face recognition to take attendance.

In this python project, I have made an attendance system which takes attendance by using face recognition technique. I have also intergrated it with GUI (Graphical user interface) so it can be easy to use by anyone. GUI for this project is also made on python using tkinter.

TECHNOLOGY USED:
1) tkinter for whole GUI
2) OpenCV for taking images and face recognition (cv2.face.LBPHFaceRecognizer_create())
3) CSV, Numpy, Pandas, datetime etc. for other purposes.

FEATURES:
1) Easy to use with interactive GUI support.
2) Password protection for new person registration.
3) Creates/Updates CSV file for deatils of students on registration.
4) Creates a new CSV file everyday for attendance and marks attendance with proper date and time.
5) Displays live attendance updates for the day on the main screen in tabular format with Id, name, date and time.

# SCREENSHOTS
MAIN SCREEN:
![Screenshot (9)](https://user-images.githubusercontent.com/37211676/58502148-97ec2a00-81a3-11e9-963e-674b9c3e05dc.png)

TAKING ATTENDANCE:
![Screenshot (10)](https://user-images.githubusercontent.com/37211676/58502149-97ec2a00-81a3-11e9-9658-8968da396c2e.png)

SHOWING ATTENDANCE TAKEN:
![Screenshot (11)](https://user-images.githubusercontent.com/37211676/58502151-9884c080-81a3-11e9-9a90-fec29940ee5a.png)

HELP OPTION IN MENUBAR:
![Screenshot (12)](https://user-images.githubusercontent.com/37211676/58502152-991d5700-81a3-11e9-861a-9115526010c2.png)

CHANGE PASSWORD OPTION:
![Screenshot (13)](https://user-images.githubusercontent.com/37211676/58502146-97539380-81a3-11e9-8536-0c68160ecc55.png)
>>>>>>> c89c4d9 (first commit)
