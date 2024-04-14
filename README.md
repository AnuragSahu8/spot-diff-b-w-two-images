I used opencv for finding the diff b/w two images 

following steps are performed during the process:
1. Read the Images. 
2. Resize it to the same shape.
3. converted it to gray scale image to facilitate better detection of features.
4. find the diff b/w two image using cv.absdiff() function.
5. Apply thresholding techniques to enhance spot detection.
6. use cv.dilate() function to expand the area of an object by enlarging the white region surrounding it.
7. calculate the similarity score using cv.matchTemplate() function. 
8. find the contours and create a rectangle around it having area > 100.  