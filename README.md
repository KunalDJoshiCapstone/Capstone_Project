# Navigation Assistance using Outdoor Object Detections and Recognitions for People Who are Blind and Visually Impaired using Deep Learning.
## Installation steps 

Installation steps for running the program with the existing weight file named yolov4-custom_best.weights:- 
1) Upload all the files in the Capstone_Project repository to your Google Drive.
2) Open https://colab.research.google.com
3) Navigate to either Recent option or Google Drive option.
4) Open YOLOv4_Webcam_Live_Traffic-Lights_Stop-Signs_Detection.ipynb file.
5) Click on Connect button which is on the top right side of the Google Colab notebook in order to make the connection.
6) Then Edit -> Notebook Settings -> GPU -> Save. 
7) Then follow the exact steps 1) to 6) except step 4) which are given in the Google Colab notebook.
8) Then copy the yolov4-custom.cfg file to cfg folder which is on the path yolov4 -> darknet -> cfg.
9) Copy obj.data and obj.names files to data folder which is on the path yolov4 -> darknet -> data.
10) Copy yolov4-custom_best.weights file to training folder which on the path mydrive -> yolov4 -> training.
11) Run the program given in step 11) in the Google Colab notebook.
12) Click on Start Video button which will start webcam of the machine.
13) Click on Start Capture button which will start detection and recognition of traffic lights and stop signs.
14) Click on Stop Capture button which will stop detection and recognition of traffic lights and stop signs. 
15) Click on Stop Video button which will stop webcam of the machine. 

Installation steps for running the program with your own custom data set and weight file obtained after training a new model:-
1) Follow Steps 1) to 6) same as mentioned above.
2) Create obj.zip folder containing your custom image dataset and anntation files.
3) Follow steps 1) to 11) mentioned in the Google Colab notebook. 
