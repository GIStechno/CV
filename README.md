# CV
Computer Vision - Object Detection

# script for detecting object and processing their bounding boxes as follows:

>## 1st step: finding corners of the objects: 
    - Detect the corners of each object
    - Output the coordinates of the bounding boxes for each object (*.txt)
    - Create a mask image where each object card is a filled rectangle (*.png)
    - Draw the rectangles and corners on the mask image (*.png)
>## 2nd step: Rotating the found rectangles to make them straight:
    - Calculate the center of the rectangle and the angle of rotation (teta)
    - Rotate the image (Affine Tranformation)
    - Crop the rectangle
    - Save the cropped image
    - Draw the rectangle on the original image (*.png)
