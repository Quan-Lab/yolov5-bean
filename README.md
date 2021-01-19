# yolov5-bean
This code mainly refers to the official yolov5 module, and uses its own soybean seed data set for training. There are five kinds of soybean seeds for training, a total of 500 pieces. Although the data set is small, the detection effect is good, and the test accuracy can reach 95.26%, which can meet the needs of daily operation.
#Inference
detect.py runs inference on a variety of sources, downloading models automatically from the latest YOLOv5 release and saving results to runs/detect.
$ python detect.py --source 0  # webcam
                            file.jpg  # image 
                            file.mp4  # video
