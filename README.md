# Contour Detection and Shape Detection OpenCV
This project is Contour Detection and Shape Detection using C++ and OpenCV.

## Steps

1- Preprocessing(binary image): BGR2GRAY, Gaussian Blur, Canny Edge Detection, Dilation  
2- Find the contours using findContours() in binary Image  
3- Add threshold condition to get contour if the size of the contour is matched  
4- Calculate perimeter using arclenth() & approximate the contour with polygon  
5- Calculate the bounding rectangle for the polygon & determine the no. of corners of a polygon  
6- Classify the shape based on no. of corners & check the aspect ratio in order to differentiate between square & rectangle  
7- Draw the contour and bounding rectangle on the original image  

## Conclusion

<img width="960" alt="Ekran görüntüsü 2024-02-20 182256" src="https://github.com/serttasbugrahan/shape-detection-opencv/assets/140887398/b25598a6-bf9a-4019-a534-861a3f186abb">


## Installation
1- Download & Install OpenCV onto your computer from http://www.opencv.org/  
2- Git Clone this project onto your computer.  
3- Add the Environment Variable ' OPENCV_DIR ' into your System Environment Variables pointing to the OpenCV installation directory.  








