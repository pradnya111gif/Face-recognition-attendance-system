# Face-recognition-attendance-system

This repository has a code for facial recognition which has been built with OpenCV and Python. Tkinter has been used for GUI interface. This attendance system could be used in schools, colleges and for employees. 

The project has 3 parts-
1. Creation of dataset.
2. Traning of the dataset.
3. Tracking of images through the live camera.

First, we will try to detect the face and capture the images to create dataset. We will collect Enrollment no. and name of students along with images. In the second part, we will create trainer that will generate a trainner.yml file for the face recognition model. While training the images, we will load the training images from the TrainingImage folder, capture the faces and Id from training images. Next step is to track the image and detect the face and mark the attendance.

Working of the attendance system- 

1. Run the train.py file. Window will be opened, enter the enrollment no. and name. 
2. Then we have to click on the Take Images button. This will open the webcam and images will be captured.
3. After the completion the notification will appear with the instruction of images being saved.
4. AFter this, we have to click on Train image buttton.
5. It takes few seconds for machine to train the images. It creates trainner.yml file.
6. By clicking Track image button, the camera is opened again. The registered face is recognised.
7. We can quit the program after that and check csv files for details.
