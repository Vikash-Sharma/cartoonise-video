# cartoonise-video
Project to cartoonise any video with Image processing and Machine Learning

Approaches used :
1.Using OpenCV image processing capabilities.

The cartoonise.py file contains the code for simple cartoonising the iamge with the use of Bilateral Filtering and edge detection using the openCV. Here first the image's edge are detected and then bilateral filter are applied to it for its smoothening. Finally both the images are merged into one by taking the inverse Binary mask of the edges.
2.Using the K-Means Clustering Algorithm from Machine Learning

The Cartoonise_Kmeans.py file contains the code for this implementation. In this approach the iamge is flattened to an array then it is put to the kmeans algorithm from which centres are found and finally these centres are used to segregate the different color regions in the image. This technique is basically used for Colour reduction in image processing .
System Requirements: Python 3 , OpenCV, Numpy installed.
How to use this project
1.Keep thepc wherever you want to cartoonise.
2.Run the python scripts given above acoording to preference.
3.Enjoy the effect.
Screenshots :
1.using Cartoonise.py script.
2.using Cartoonise_kmeans.py script.
