# Mobile-Network
Object Detection using Mobile Networks


Here I have used the pre-trained weights of the Mobile Network architecture for object detection.
To test the code
1. Extract the zip file mobileNet.zip
2. Open terminal and type python detection.py to see object detection in an included video file.
3. Open terminal and type python detect.py to see predictions on an image.

You can also use you webcam for object detection to do that just go to detection.py code and change the following

video = cv2.videoCapture("walking.avi") to video = cv2.videoCapture(0) and remove the video writing part!. Some results of object detection using my webcam!
![alt text](https://github.com/pks-97/Mobile-Network/blob/master/test.png)
