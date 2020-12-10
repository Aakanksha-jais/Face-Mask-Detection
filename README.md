# Face-Mask-Detection
Using Convolutional Neural Network


In this project, we have used a prebuilt cascade classifier from Open Source Computer Vision
Library, that detects faces from the input image and identifies the region of interest. The cascade
classifier falls a little short when it comes to accuracy, however it works well in real-time
because of it’s excellent frame rate of 15fps, which is pretty quick for real-time applications.
Also, since it is lightweight, it is easily deployable into modules of embedded systems. The
region of interest identified by the cascade classifier is then rescaled to 100*100 size, which is
then fed as input to the CNN. The CNN detects whether the person is wearing the mask or not.


If under any circumstance, the images taken by the camera module aren’t clear enough to
classify the system fails. Therefore, the proposed system has the following limitations:
● If the camera module is placed at a distance from the crowd, the model may not be able to
give accurate results.
● The model has been designed in a simple fashion, it has no way to classify whether the
person in front of the camera is wearing a mask properly or not.
● The model has not been trained by adversarial examples and is hence susceptible to bayesian
error.
