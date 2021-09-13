# BaggageAI_CV
Task -
To cut the threat objects, scale it down, rotate with 45 degree and paste it
into the background images using image processing techniques in python.
Libraries Used
OpenCV is the huge open-source library for the computer vision, machine learning, and image processing and now it plays a major role in real-time operation which is very important in today's systems. By using it, one can process images and videos to identify objects, faces, or even handwriting of a human.
cv2.imread()- To load the image from specified file location.
cv2 imshow method is display the image.
Numpy - OpenCV-Python makes use of Numpy, which is a highly optimized library for numerical operations.
imutils - Imutils are a series of convenience functions to make basic image processing functions such as translation, rotation, resizing, skeletonization, and displaying Matplotlib images easier with OpenCV and both Python 2.7 and Python 3.Here we used for rotating the threat image.
cv2.addWeighted-The addWeighted function is a function that helps in adding two images and also blending those by passing the alpha, beta and gamma values. In order to analyse images, this helps in adjusting the gradients and in the processing of the image. The blending of the images depends on alpha and beta values which are passed as arguments to this function.
The generic syntax for this can be as below:
img = cv2.addWeighted(source1, alpha, source2, beta, gamma[, dst[, dtype]])
Here, source1 = Background image
source2 = Threat image
alpha and beta values ranges between 0 and 1 and helps in transformation of one image to another.
Here the images that we take into consideration say image one is given a weight of 0.6 and the second image has the weight of 0.4..
One can change this values according to need and see the variations.
