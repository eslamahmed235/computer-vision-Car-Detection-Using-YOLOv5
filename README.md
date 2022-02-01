# computer-vision---Car-Detection-by-Using-YOLOv5
Our project focus on car detection from images of cars which is scraped from Google Images by using Beautiful Soup. We used YOLO v5 model for cars detection in the images and test servile models after changing the backbone of YOLO v5 Model for each one to reach the best results. <br/>
we analyzed the detection method by Yolov5 and compared them with other methods like RCNN, Fast RCNN, Faster RCNN, HOG and w We can say YOLOv5 is the state of the art because it is robust and used in real-time it became easier to deploy the product than other methods. 

## get data
Get Data collect data is our first mission to get data, we have some instruction in this project to don’t use benchmark dataset pre annotated before. So, we go throw write python script using “Beautifulsoup” library to send requests to scrap images from Google image website related to our topic “vehicle” and scripted up to 800 images. and annotate it manually.
## Algorithm
We chose YOLO V5 Algorithm to be our detection model in this project. YOLO algorithm based on convolutional neural networks (CNN) that detect objects in real time. To detect objects, the technique simply requires a single forward propagation through a neural network. We got throw 6 different experiments with different configurations and parameters to reach the best model
and best performance shown in following figure and table <br/>
![final result graph](https://github.com/eslamahmed235/computer-vision-Car-Detection-Using-YOLOv5/blob/main/data/final%20result%20graph.png) <br/>

![final result table](https://github.com/eslamahmed235/computer-vision-Car-Detection-Using-YOLOv5/blob/main/data/final%20result%20table%20.png)
