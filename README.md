# SUACE
Speeded Up Adaptive Contrast Enhancement (SUACE); an OpenCV based implementation of a realtime adaptive contrast enhancement technique. 

SUACE is an image contrast enhancement algorithm which has been originally invented for enhancing infrared vein images. But SUACE can be used in any application which requires real-time contrast enhancement.

![A Retinal Fundus Image Enhanced by using SUACE](https://1.bp.blogspot.com/-2aBnZGTrQxw/XlW2EAcjsuI/AAAAAAAACbc/mkZyW6Rk9esxH_SoCCguM_RhTEs2AGaAQCLcBGAsYHQ/s1600/suace.png)
*image from: DRIVE dataset [http://www.isi.uu.nl/Research/Databases/DRIVE/]

## Features:
1. Real-time processing
2. Simultaneous Illumination normalization
3. Regulated boosting for details

## How to Use:
This implementation uses openCV 3.0 but can be used with openCV 2.x.x as well. Add the suace.cpp and suace.h to you project and compile with any c++ compiler. You may need to change the included openCV header files according to your version of openCV. 
An example code for using suace can be found in example.cpp. 

## More Details:
More details about SUACE algorithm can be found in the following documents. 

1.	[http://ieeexplore.ieee.org/document/8300426/] R. Bandara and M. P. Giragama, “A Retinal Image Enhancement Technique for Blood Vessel Segmentation Algorithm,” accepted to 2017 IEEE 12th International Conference on Industrial and Information Systems (ICIIS) (ICIIS’2017), Peradeniya, Sri Lanka, 2017.

2.	[http://ieeexplore.ieee.org/document/8300427/] R. Bandara, H. Kulathilake and M. P. Giragama, “Super-Efficient Spatially Adaptive Contrast Enhancement Algorithm for Superficial Vein Imaging,” accepted to 2017 IEEE 12th International Conference on Industrial and Information Systems (ICIIS) (ICIIS’2017), Peradeniya, Sri Lanka, 2017.
