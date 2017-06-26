# **Finding Lane Lines on the Road** 

## Writeup

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps changing the lane_detector() function:

1) I converted the images to grayscale
2) Defined the kernel size and applied Gaussian smoothing
3) Defined the parameters for Canny
4) Create masked edges
5) And finally define the Hough transform parameters and detect lines using it

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...
