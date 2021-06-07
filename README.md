# Face Detection
This is a face detection project. In this project face/s are detected from an image passed in as the input, images with multiple faces are also allowed to be passed in as the input. 
Detected face is shown using a green square around the face.

Input->image(path), haar_cascade file
Ouput->image with face/s detected
(The input and output files are included in the repository.)

Libraries utilized->opencv(cv2) and matplotlib

The CascadeClassifier() function from the opencv library has been used to help us detect the face/s in the given image.

Example input->

![person](https://user-images.githubusercontent.com/47482433/121080918-a7be9000-c7f9-11eb-8d93-ec05cfecc3df.jpg)

Example output->

![output_person](https://user-images.githubusercontent.com/47482433/121078919-236b0d80-c7f7-11eb-80f8-d45aa925eb98.jpg)

This program will also work for images with multiple faces though in that case the accuracy may decrease as the number of faces increase and some errors might occur. Accuracy and the number of faces in the image are inversely proportional i.e. as the number of faces in the input image increase, the accuracy of the program decreases due to increase in complexity. Some errors may also be found.

The haarcascade_frontalface.default.xml file has been included in the repository. This file is used to map the features of a face which helps us detect the face in the input image.
