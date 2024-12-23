# Virtual-Mouse-using-hand-Gesture-Recognition
 

The gesture-controlled virtual mouse is an innovative technology that allows people to interact with computers without the need for physical contact. The system employs modern machine learning and computer vision techniques to detect hand gestures, voice commands, and eye movements using internal and external cameras. The system consists of two modules: the first one involves hand detection using MediaPipe's technology, while the second employs a glove with a single color. Users can control the virtual keyboard and mouse by moving their fingers in the air, which is made possible through computer vision technology and artificial intelligence. The system uses modules such as Hand Tracking, CVzone Hand Detector, and the Controller imported from the Pynput keyboard to recognize hand gestures and control input and output processes.The system functions as a virtual keyboard and mouse without the need for any external devices, wires, or connections. It employs a Convolutional Neural Network(CNN)-like model implemented by MediaPipe running on top of pybind11. The system enables users to work in the air and access keyboard keys by maneuvering fingers, making it an ideal tool for people who are physically challenged or have mobility issues. The webcam is the only piece of hardware required in this system, which is used to record images, recognize hand gestures, eye movements, and receive voice instructions using the Pyttsx3 module. The suggested system can improve the quality of life for people with disabilities or mobility issues, as it allows them to interact with computers without the need for physical contact or external devices. Overall, the gesture-controlled virtual mouse is a remarkable advancement in computer technology that has the potential to revolutionize the way people interact with computers.


Note: Use Python version: 3.8.5
-Install Anaconda Distribution
# Install Necessary libraries using pip:

-Install PyAudio
-Install pywin32
-pyttsx3==2.71
-SpeechRecognition==3.8.1
-pynput==1.7.3
-pyautogui==0.9.53
-wikipedia==1.4.0
-opencv-python==4.5.3.56
-mediapipe==0.8.6.2
-comtypes==1.1.11
-pycaw==20181226
-screen-brightness-control==0.9.0
-eel==0.14.0

## Features

- VoiceBot 
  -  Current Date and Time                           
  -  Google Search
  -  Find Location
  -  Sleep/Wake-up

- KeyBoard
- Eye Movements
- Gesture Recognition:
    - Neutral Gesture
    - Move Cursor
    - Left Click
    - Right Click
    - Double Click
    - Scrolling
    - Drag and Drop
    - Multiple Item Selection
    - Volume Control
## Procedure
Step 1:
```bash
  conda create --name gest python=3.8.5
```
Step 2:
```bash
  conda activate gest
```
Step 3:
```bash
  pip install -r requirements.txt
```
Step 4:
```bash
  conda install PyAudio

  conda install pywin32
```
Step 5:
```bash
  cd to the GitHub Repo till src folder
```
Command may look like: cd C:\Users\.....\Gesture-Controlled-Virtual-Mouse\src

Step 6:
For running GUI:
```bash
  python main.py
```
Or to run only Gesture Recognition without the voice assisstant:

Uncomment last 2 lines of Code in the file Gesture_Controller.py
