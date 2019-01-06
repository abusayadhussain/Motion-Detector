# Motion-Detector
Python based app where  how many times a object is in the scenario and when it go away is calculated and save it to a csv file. The python library
used here is OpenCV. First of all the actual image is converted to gray image if there is none in the first frame. Then there are two more
frame is used 1.Delta frame 2.thresh frame and the differnce between first frame  and gray image. The status is stored as a flag. And the time
is stored when the object is there and go away according to the status.
