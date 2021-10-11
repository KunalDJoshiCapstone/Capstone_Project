# Navigation Assistance using Outdoor Object Detections and Recognitions for People Who are Blind and Visually Impaired using Deep Learning.
## Installation steps 

Installation steps for running the program with the existing weight file named yolov4-custom_best.weights:- 
1) Download weights file from https://drive.google.com/file/d/1lRRESxnroxFb2OohPtA6CSg6Xg-CZFDZ/view?usp=sharing
2) Upload all the files in the Capstone_Project repository to your Google Drive.
3) Open https://colab.research.google.com
4) Navigate to either Recent option or Google Drive option.
5) Open YOLOv4_Webcam_Live_Traffic-Lights_Stop-Signs_Detection.ipynb file.
6) Click on Connect button which is on the top right side of the Google Colab notebook in order to make the connection.
7) Then Edit -> Notebook Settings -> GPU -> Save. 
8) Then follow the exact steps 1) to 6) except step 4) which are given in the Google Colab notebook.
9) Then copy the yolov4-custom.cfg file to cfg folder which is on the path yolov4 -> darknet -> cfg.
10) Copy obj.data and obj.names files to data folder which is on the path yolov4 -> darknet -> data.
11) Copy yolov4-custom_best.weights file to training folder which on the path mydrive -> yolov4 -> training.
12) Run the program given in step 10) in the Google Colab notebook.
13) Click on Start Video button which will start webcam of the machine.
14) Click on Start Capture button which will start detection and recognition of traffic lights and stop signs.
15) Click on Stop Capture button which will stop detection and recognition of traffic lights and stop signs. 
16) Click on Stop Video button which will stop webcam of the machine. 

Installation steps for running the program with your own custom data set and weight file obtained after training a new model:-
1) Follow Steps 2) to 6) same as mentioned above.
2) Create obj.zip folder containing your custom image dataset and annotation files.
3) Follow steps 1) to 10) mentioned in the Google Colab notebook. 

URL for the image dataset and annotation files used in the project:-
https://drive.google.com/file/d/1diXniyci2ypySm4TwJTuLBUSFGjYGQfS/view?usp=sharing

URL for program explanation recording:-
https://rit.zoom.us/rec/share/fI4asM85Ik8DIBrJ-wjJ9TwDDihUr-ZI0KyOVBi35pOWAwvm5aO7yUN7OtTWWFgZ.LU6JFgXoj5R2d2Nz

URL for Demo recording:-
https://drive.google.com/file/d/1V-JQ4J8XBBtsO1fypD16y4HljlrSa2x8/view?usp=sharing
https://drive.google.com/file/d/1B90sgI3rUBuMrckG5LL0dwJte0ZmlnBp/view?usp=sharing
