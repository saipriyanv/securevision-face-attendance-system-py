Project Overview:
  The Secure Vision Face Attendance System is an Computer Vision-driven application intended to streamline Attendance monitoring by utilizing real-time facial recognition along with improved security via anti-spoofing methods. The system identifies and verifies faces from live video feeds and logs attendance while blocking unauthorized access through phony images or videos.

  It utilizes computer vision and deep learning principles to guarantee precise identification and enhance reliability in practical settings like classrooms and workplaces.

  This project is adapted from an open-source repository and has been further modified and enhanced for learning and development purposes. Improvements include code customization, structural changes, and additional feature enhancements to better understand and apply computer vision concepts.

How it works:
  The system acquires real-time video feed via a webcam and analyzes every frame with computer vision methods. Faces are identified and encoded, then matched against stored facial data for recognition.

To improve security, anti-spoofing techniques are utilized to distinguish between authentic faces and spoofing attempts like photographs or screen displays. Upon recognizing a valid face, the system records attendance with pertinent information while preventing duplicate records.

Key Features:
1.Real-time face detection and recognition using OpenCV
2.Automated attendance recording with high accuracy
3.Anti-spoofing mechanism for secure authentication
4.Prevention of duplicate attendance entries
5.Efficient face encoding and matching process

How to Run:
1.Install required dependencies using requirements.txt
2.Run the main.py file
3.Ensure webcam access is enabled
4.The system will start detecting and recognizing faces in real time
5.After the recognition of the face in the frame, it will ask for Register and login and log out
If the person is new, then the person can register
If the person is already registered,then person need to log in or log out according to their requirements
If the person is real, then if will perform the given task
If the person is fake, then it will automatically states that the face captured by the system is fake and doesnot allow further operation
It even ensures by noting the date and time of the persons log in and log out for future purposes.
