# Cartoonization-using-opencv-library
The libraries used in cartoonizing the images are *opencv* and *numpy*
# steps that we will perform:
1. Apply a bilateral filter to reduce the color palette of the image.
2. Convert the original color image to grayscale.
3. Apply a median blur to reduce image noise in the resultant grayscale image.
4. Create an edge mask from the grayscale image using adaptive thresholding.
5. Combine the color image from step 1 with the edge mask from step 4.
