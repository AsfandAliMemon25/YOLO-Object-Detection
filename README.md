# YOLO-Object-Detection-Using-OpenCV

YOLO is a state-of-the-art, real-time object detection algorithm. In this notebook, we will apply the YOLO algorithm to detect objects in images.
darknet prints out the objects it detected, its confidence, and how long it took to find them. We didn't compile Darknet with OpenCV so it can't display the detections directly. Instead, it saves them in predictions.png. You can open it to see the detected objects. Since we are using Darknet on the CPU it takes around 6-12 seconds per image. If we use the GPU version it would be much faster.

 
# Detect objects in both images and video streams using , OpenCV, and Python.

The COCO dataset consists of 80 labels, including, but not limited to:

- People
- Bicycles
- Cars and trucks
- Airplanes
- Bananas
- Stop signs and fire hydrants
- Animals, cats, dogs, birds, horses, cows, and sheep, an other name
- Kitchen and dining objects, such as wine glasses, cups, forks, knives


## YOLO object detection in images

## Installation Packages 

- `pip install numpy`
- `pip install opencv-python`

## To Run the project

- `python yolo.py --image images/baggage_claim.jpg`

## Result 
![Image](https://github.com/yash42828/YOLO-object-detection-with-OpenCV/blob/master/Object%20dection%20using%20image/1.png)

Here you can see that YOLO has not only detected each person in the input image, but also the suitcases as well!

Furthermore, if you take a look at the right corner of the image you’ll see that YOLO has also detected the handbag on the lady’s shoulder.

<img src="https://github.com/yash42828/YOLO-object-detection-with-OpenCV/blob/master/Object%20dection%20using%20image/2.png">

YOLO is able to correctly detect each of the players on the pitch, including the soccer ball itself. Notice the person in the background who is detected despite the area being highly blurred and partially obscured.

## YOLO object detection in video streams

## Installation

- `pip install numpy`
- `pip install opencv-python`

## To Run the project

- `python yolo_video.py --input videos/airport.mp4 --output output/airport_output.avi --yolo yolo-coco`

## Result Real Time 

<img src="https://github.com/yash42828/YOLO-object-detection-with-OpenCV/blob/master/Object%20detection%20using%20video/car.gif">

In the video/GIF, you can see not only the vehicles being detected, but people, as well as the traffic lights, are detected too!

The YOLO object detector is performing quite well here. 


## Real-time object detection with deep learning and OpenCV

## Installation

- `pip install numpy`
- `pip install opencv-python`
- `pip install imutils`

## To Run the project

- `python real_time_object_detection.py`

## Result Real Time 
<img src="https://github.com/yash42828/YOLO-object-detection-with-OpenCV/blob/master/real-time-object-detection/real_time.gif">


follow me on Github https://github.com/AsfandAliMemon25