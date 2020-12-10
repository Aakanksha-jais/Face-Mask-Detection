# Face-Mask-Detection
Using Convolutional Neural Network


In this project, we have used a prebuilt cascade classifier from Open Source Computer Vision
Library, that detects faces from the input image and identifies the region of interest. The cascade
classifier falls a little short when it comes to accuracy, however it works well in real-time
because of it’s excellent frame rate of 15fps, which is pretty quick for real-time applications.
Also, since it is lightweight, it is easily deployable into modules of embedded systems. The
region of interest identified by the cascade classifier is then rescaled to 100*100 size, which is
then fed as input to the CNN. The CNN detects whether the person is wearing the mask or not.
