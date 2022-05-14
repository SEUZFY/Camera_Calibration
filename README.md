# Camera_Calibration

This is for camera calibration based on this open-source project:

https://github.com/LiangliangNan/Easy3D

<img width="478" alt="images" src="https://user-images.githubusercontent.com/72781910/168390581-25a1adce-4b04-4589-b655-a73455d3e2d6.PNG">

Copyright (C) 2015 Liangliang Nan <liangliang.nan@gmail.com>

https://3d.bk.tudelft.nl/liangliang/


**CITATION INFO**:
```
@article{easy3d2021,
  title = {Easy3{D}: a lightweight, easy-to-use, and efficient {C}++ library for processing and rendering 3{D} data},
  author = {Liangliang Nan},
  journal = {Journal of Open Source Software}，
  year = {2021},
  volume = {6},
  number = {64},
  pages = {3255},
  doi = {10.21105/joss.03255},
  url = {https://doi.org/10.21105/joss.03255}
}
```

# HOW TO USE

* Clone this project at: https://github.com/SEUZFY/Camera_Calibration.git

* Or download the code and open the [CMakeLists.txt](https://github.com/SEUZFY/Camera_Calibration/blob/master/CMakeLists.txt) file in an IDE.

Build and run this project, a viewer as shown above should pop up automatically, press `space` and select one of the `.txt` files to calibrate.

**Note**: `.txt` files are available in the [data](https://github.com/SEUZFY/Camera_Calibration/tree/master/resources/data) folder.

After calibration, press `t` to show the calibrated virtual camera (in blue frame), as shown below:

<img width="479" alt="images2" src="https://user-images.githubusercontent.com/72781910/168394397-b1c35e49-b508-46a3-b2fc-3f6a0450ee41.PNG">

Meanwhile some helpful information should be printed to the console.

# GOOD TO KNOW

The calibration method is [here](https://github.com/SEUZFY/Camera_Calibration/blob/master/Calibration/calibration_method.cpp), all the other files are kindly given by [Liang Liang](https://3d.bk.tudelft.nl/liangliang/).

The report is written in `LaTeX` and the source is available [here](https://github.com/SEUZFY/Camera_Calibration/tree/master/report/source). Feel free to use it if it helps you.

# COLLABORATORS

**Yitong**:
xiayitong0630@gmail.com
-> Her [GitHub](https://github.com/YitongXia/camera-calibration)

**Leo Kan**:
leo.kan01@gmail.com
-> His [GitHub](https://github.com/leowhk/A1_calibration).
 
 

