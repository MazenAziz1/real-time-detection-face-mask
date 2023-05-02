# real-time-detection-face-mask
Detecting face mask in real-time with training&validation accuracies exceeding 98%. This learning journey helped me a lot to look more closely at some common concepts while working on most of image classification projects like Data preprocessing, Data augmentation and Model training.
# Required libraries
+ Numpy
+ Tensorflow
+ Matplotlib
+ Imutils
+ OpenCV
+ Sklearn
# About the dataset
You can find in the repository huge folder contains two smaller folder, each of them contains all the PNG images that are mapped to their label(with mask/without mask)
# How to run the project?
+ open command prompt
+ change the working directory to be the folder of the unzipped and cloned repository
+ install requirements by running file "requirements.txt"
  * pip install -r reuirements.txt
+ run open webcam code
  * python detect_mask_video.py
# project implementation
+ import necessary libraries
+ load data&labels
+ normalize data
+ augment data
+ split data into training and testing ratios
+ train MobileNetV2 model
+ fit model
+ save model
+ plot accuracy and loss
# Why this project is noteworthy?
Implementation of this project applying, whatever neural network model whether it's pretrained or not, could be the stepping stone to the world of image classification especially in real-time. Besides, the size of this dataset will derive high testing accuracy and really motivate you to explore more challenges later.
# You can findout more
[OpenCV](https://opencv.org/)
