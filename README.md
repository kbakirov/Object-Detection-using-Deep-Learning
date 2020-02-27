# Object-Detection-using-Deep-Learning
Object detection using deep learning with OpenCV and Python

## Popular object detection framework YOLO(You Only Look Once) used
## Install following:
- opencv
- numpy

```
pip install numpy opencv-python
```

## YOLO
Download the pre-trained YOLO v3 weights file from this link and place it in the current directory
```
$ wget https://pjreddie.com/media/files/yolov3.weights
```
Provided all the files are in the current directory, below command will apply object detection on the input image ``whatever.jpg``

```
$ python yolo_opencv.py --image whatever.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt
```

## Output
![Object_detection](object_detection.png)

## UPDATE
We can also implement this using webcam

Simply executing yolo_webcam.py file and removing --image whatever.jpg command

![Object_detection2](webcam.png)


## Source
https://github.com/arunponnusamy/object-detection-opencv


