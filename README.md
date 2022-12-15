# Custom-Object-Detection-Using-YOLO
In this project I am trying to identify and localise autos in an image. This is an object detection problem. For each test image, we will be predicting a bounding box and ‘Auto’ as a class for all findings. 

YOLO requires supervised data for training with annotations only in a certain format. Since our dataset was not annotated, annotating the data in the training set was required. Label Image was used to annotate the images in the training set. Since we only want to detect one class i.e. is Auto a single label ‘Auto’ was used for the given purpose.

With the help of Label Image bounding boxes was drawn around autos in each image and the labelling was done. The annotations were stored in YOLO format in a separate directory train in the label’s directory. A classes.txt file stores Auto as label with index 0. 0 is used as class label while annotating data in the directory.
