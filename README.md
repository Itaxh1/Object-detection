A python library built to empower developers to build applications and systems with self-contained Deep Learning and Computer Vision capabilities using simple and few lines of code. 


An AI Commons project https://aicommons.science Developed and Maintained by Moses Olafenwa and John Olafenwa, brothers, creators of TorchFusion and Authors of Introduction to Deep Computer Vision

Built with simplicity in mind, ImageAI supports a list of state-of-the-art Machine Learning algorithms for image prediction, custom image prediction, object detection, video detection, video object tracking and image predictions trainings. ImageAI currently supports image prediction and training using 4 different Machine Learning algorithms trained on the ImageNet-1000 dataset. ImageAI also supports object detection, video detection and object tracking using RetinaNet, YOLOv3 and TinyYOLOv3 trained on COCO dataset. 
Eventually, ImageAI will provide support for a wider and more specialized aspects of Computer Vision including and not limited to image recognition in special environments and special fields.




New Release : ImageAI 2.0.2 
What's new: 

Option to state image size during custom image prediction model trainings 
Object Detection and Video Object detection now returns bounding box coordinates ('box points') (x1,y1,x2, y2) for each object detected in addition to object's 'name' and 'percentage probability' 
Options to hide 'percentage probability' and/or object 'name' from being shown in detected image or video
Support for video object detection on video live stream from device camera, connected camera and IP camera 
Support for YOLOv3 and TinyYOLOv3 for all object detection and video object detection tasks.
Video object detection for all input types (video file and camera) now allows defining custom functions to execute after each frame, each second and each minute of the video is detected and processed. Also include option to specify custom function at once video is fully detected and processed 
For each custom function specified, ImageAI returns the frame/seconds/minute/full video analysis of the detections that include the objects' details ( name , percentage probability, box_points), number of instance of each unique object detected (counts) and overall average count of the number of instance of each unique object detected in the case of second / minute / full video analysis
Options to return detected frame at every frame, second or minute processed as a Numpy array. 
