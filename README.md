# Facial Recognition

This is an implementation of a Facial Recognition based attendance system. Before usage training is required on the images of the sudents. On facing the camera, 
the model recognizes if the person in the image is in the database, if so it marks the attendance in an csv file, otherwise it adds the image to the unkown folder.
For facial detection Haar-Cascade frontal face detector is used. The recognition is based on LBPH algorithm.

#### Technology Stack
-openCV (Opensource Computer Vision)
-Python
-tkinter GUI interface

#### Execution

In order to start the program, run the following command (Linux):

``` python3 train.py```
