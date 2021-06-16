# Face-Emotion-Recognition
Created a CNN model for successfully recognizing emotions on a persons face, with an accuracy of around 61%

Complete code is divide into 2 parts i.e. training the model(Training.ipynb) and recognition(Driver.ipynb)

In Training.ipynb file, complete dataset is loaded, augmented and noramalized and then feeded to the model and the model trains..
After training, the weights of neurons is stored in the file named Face_Emotion.h5

In Driver.ipynb file, h5 file along with haarcascade_frontalface_default.xml file is used along with cv2 library for live emotion recognition.
To stop the camera, 'q' is pressed.

This concludes the project.
