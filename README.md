# Driver-Drowsiness-Detection-using-OpenCV-and-Keras
- The “haar cascade files” folder consists of the xml files that are needed to detect objects from the image. In our case, we are detecting the face and eyes of the person.<br>
- The models folder contains our model file “cnnCat2.h5” which was trained on convolutional neural networks.<br>
- We have an audio clip “alarm.wav” which is played when the person is feeling drowsy.<br>
- “Model.py” file contains the program through which we built our classification model by training on our dataset. You could see the implementation of convolutional neural network in this file.<br>
- “Drowsiness detection.py” is the main file of our project. To start the detection procedure, we have to run this file.<br>

## Explanation of Project
1.  Take Image as Input from a Camera
2.  Detect Face in the Image and Create a Region of Interest (ROI)
3.  Detect the eyes from ROI and feed it to the classifier
4.  Classifier will Categorize whether Eyes are Open or Closed
5.  Calculate Score to Check whether Person is Drowsy
