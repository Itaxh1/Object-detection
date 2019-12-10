A python library built to empower developers to build applications and systems with self-contained Deep Learning and Computer Vision capabilities using simple and few lines of code. 


Option to state image size during custom image prediction model trainings 
Object Detection and Video Object detection now returns bounding box coordinates ('box points') (x1,y1,x2, y2) for each object detected in addition to object's 'name' and 'percentage probability' 
Options to hide 'percentage probability' and/or object 'name' from being shown in detected image or video
For each custom function specified, ImageAI returns the frame/seconds/minute/full video analysis of the detections that include the objects' details ( name , percentage probability, box_points), number of instance of each unique object detected (counts) and overall average count of the number of instance of each unique object detected in the case of second / minute / full video analysis
Options to return detected frame at every frame, second or minute processed as a Numpy array. 
