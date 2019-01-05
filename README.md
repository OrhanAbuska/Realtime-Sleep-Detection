# Realtime-Sleep-Detection

Craeted by Orhan Abuşka - with OpenCV

# Usage-# 

Download files. In order to get the pre-trained shape-predictor file please contact www.orhanabuska.com. Without this file you will get Error while launching file.

Re-Locate shape_predictor_68_face_landmarks.dat into the project folder. 
Open a terminal, Go to the folder.
Enter commands

# Without Alarm Sound
  python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat
  
# With Alarm Sound
  python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat --alarm alarm.wav
