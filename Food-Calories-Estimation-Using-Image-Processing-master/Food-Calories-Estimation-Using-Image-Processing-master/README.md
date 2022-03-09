
# Food Calories Estimation Using Image Processing
<img src="1.jpg" alt="python" width="150" height="190" align="right">


+ ###  Problem
 The problem can be simply stated as, given a set of food images with calibration object thumb with the food name and an unlabeled set of food images from the same group of food, identify food and estimate food volume and calories intake.
+ ### Objectives
 1.	To detect food type by using Convolutional Neural Network (CNN)
 2.	To estimate food weight and calories of food
 

### Estimation Method:
+ #### Image Segmentation:
A mixture of methods including canny edge detection, watershed segmentation, morphological operators and Otsu’s method were used to segment the food item to obtain the contour of the fruit and the contour of the thumb. We use the thumb finger for calibration purposes. The thumb is placed next to the dish while clicking the photo and this thumb gives us the estimate of the real-life size of the food item and helps estimate volume accurately.
> *all this done ```image_segment.py``` and ```calorie.py```*



## Result

 | Fruits  | Calorie | Estimated Calories|
 | ------- | ------- | -----------------| 
 | Apple   |  53.96  |   40.42          |
 | Banana  |  170.88 |   188.81         |  
 | Carrot  |  31.16  |   26.28          |
 | Cucumber|  29.44  |   37.65          |
 | Onion   |  44.88  |   37.13          |  
 | Orange  |  69.09  |   71.92          |
 | Tomato  |  17.46  |   13.82          |

