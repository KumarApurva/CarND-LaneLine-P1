# **Finding Lane Lines on the Road** 

---

**Finding Lane Lines on the Road**

The goals/steps of this project is following:
* Make a pipeline that finds relevant lane lines on the road
* The pipeline can be used for both images and video inputs

[image1]: ./Images/GrayImage.jpg "GrayscaleImage"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

The pipeline consists of 6 steps identified below:
1. Transformed image to 'Gray Scale' for efficient computing
2. Applied 'Gaussian Blur' for removing the noise from the image
3. Identified of edges based on pixel intensity gradients 
4. Selected area of interest in the image
5. Found the line segments from edges based on Hough Transformation and drew lines on a blank image
6. Used the above output and applied on the original image
 
A sample output image is attached below: 

![alt text][./Images/whiteCarLaneSwitch.jpg]


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...

