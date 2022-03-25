# tensorflow-object-detection

this project is focus on object detection model from tensorflow using opencv for the model inference. 
In this state, I use mobilenet_v2 with COCO dataset from this link >> http://download.tensorflow.org/models/object_detection/ssd_mobilenet_v2_coco_2018_03_29.tar.gz

## How to use?
1. clone this project
2. install nessessary dependency modules for requirements.txt. I tested this project on Macbook air M1. So, please check importance dependency modules for your system.  
3. run python3 video_object_detection.py


# Custom-object-detection
this project is focus on object detection model using Yolov5 for custom object detection. This project aim to the model to recognize my face but you can perform the same procedure with other project. In my case, I use the the Notebook from Yolov5 github for custom training. My dataset is quite small (200 samples). I use transfer learning to got the good result (base model is yolov5s).

## How to use?
1. clone this project
2. install nessessary dependency modules for requirements.txt. I tested this project on Macbook air M1. So, please check importance dependency modules for your system.  
3. use roboflow to label the dataset. I would recommend 250 samples as minimum for transfer learninf method. For full training, Robust YOLOv5 model, it is recommended to train with over 1500 images per class, and more then 10,000 instances per class. It is also recommended to add up to 10% background images.
4. Follow procedure in YOLOv5-Custom-Training.ipynb. Adjust training parameters to fit with your case.
5. export model from notebook and place the model in application location.
6. run python3 custom_detection.py


# Next step?
I would like to further explore in the area of OCR technique and license plate recognition. I would start with Public dataset then I would adapt it with with Thai license plate. Other interested projects are:

1. Document OCR
2.  Custom pose recognition
3.  Custom face recognition
