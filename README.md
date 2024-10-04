# Human-Detection-By-Improved-YOLOv8-Model
This is the final project for Vision and Cognition

## Description:
We adopt model YOLOv8 which is the newest state-ofthe-art YOLO model that can be used for object detection,
image classification, and instance segmentation tasks as our
pre-trained model for human detection. To fine-tune the
model, we use Pascal VOC and Human Detection Dataset to
adapt the model to our specific domain. We also try to freeze
part of the basic structure, fine-tune the hyper-parameters
and increase the resolution of training set to achieve the
best performance of the model. We find the highest accuracy is achieved when we freeze the backbone, set epoch
to be 25 and use 1024*1024 input. Our improved models
also indicate better performance in crowd situation including detection of part of the human body. All the work done
by this task can also be extended to other classes of objects
detection .

## Language:
Python
