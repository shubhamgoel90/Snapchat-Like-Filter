# Snapchat-Like-Filter

In this project we are creating the Snapchat like Filter model that will automatically place the Glasses and Mustache at their respective positions on the face in the live stream. 

For detecting the face we are using the pre-trained haarcascade_frontalface_default.xml that will detect the face and for placing the Glasses and Mustache we are detecting the eyes and nose and placing these images at their respective postions. As, these images have some background we have used the alpha function from OpenCV for the transparency of the image and only using the main part of the image.

### Libraries Used:-
1. OpenCV
2. Numpy
