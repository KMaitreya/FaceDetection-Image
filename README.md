# Face Detection
This is a face detection project from an image passed in as the input, images with multiple faces are also allowed to eb passed in as the input but in that case the accuracy of the algoritm decreases and errors may appear. Detected face is shown using a green square around the face.

Input - image, haarcascade file

Ouput - image with face/s detected

Libraries - cv2 and matplotlib

The CascadeClassifier() function from the opencv library has been used to help us detect the face/ in the given image.

example input-

![download](https://user-images.githubusercontent.com/47482433/121072249-92903400-c7ee-11eb-92f9-26feaecea342.jpg)

example output-

![output_person](https://user-images.githubusercontent.com/47482433/121078919-236b0d80-c7f7-11eb-80f8-d45aa925eb98.jpg)

This program will also work for images with multiple faces though in that case the accuracy may decrease as the number of faces increase and some errors might occur.

The input and output are included in the repository.
