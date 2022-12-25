# Driver-Drowsiness-Detection-Alert-System-using-Python-
A tool to detect the driver face recognition and alert the driver with voice commands 

In this project i am used python as the running platform. The machine learning concepts are used in this project
by the frame work named 'dlib' which is efficient tool made from the c and c++ libraries for facerecognition and face 
land marks boundry maker(shape_predictor)(lower in process but high accurary) which takes the dat file as an label to predict the landmarks of the face
also we can use the xml file(faster in process but low accurary) to predict the faces motion by already trained model. The imutils is a image and frame
managing frame work by python to use the frames of the camera and process. The scipy is used to calculate the both
yawn and eye focus percentage by the ecludien formula(used to find the convex hull of the eye) and thershold for 
both. Opencv is a powerful python frame work using image and video it can predicition,detection,correction. using 
cv2 we can change the all pixels,size,quality,colour,lighting way etc...., argparse is used to suffisticate the user
by providing them a good running command in cmd or terminal with our any mess of running the file, by the argparse
we designed the running command for our convineince. This project hardware requirements are 2.0mp(at lease), audio speaker,
rassberypi or a system to connect the python and process the frames given by the camera. working is very simple to explain
the camera take every 10 frames persecond each frames or checked with the given yawn and eye focus size by the given threshold 
and give the alert by the speaker for eye alter sounds "open your eyes sir" for yawn alter sounds "take some fresh air sir".
for quit press q.

The most diffuclt process to me is statisfing the requirments of the system by installing dlib library
among most of the python version didnt supported to the dlib library and its wheel setup after the 
long checking and searching of the correct supporting version of python and the dlib both in same 
is python 3.8.2 with the version of dlib-19.19.0 even though we can use xml file but it is very low in 
accurary and detection.



Thanking you,
K. Gokulappadurai-B.E(CSE) going on ......


feel free to contact with me .....
phone: 9025421765
gmail: k.gokulappaduraikjgv@gmail.com

