
# A prototype of cnn forward and backward computtions for classification problem and coding in C++.
Qinwu Xu (Jan 2023) https://github.com/qinwuxutexas/cnn_forward_backward_cplus

Notes:
1) the methodology is referred to Andrew NG., Deep Learning Specilization, Coursera, which provided the backbone and framework of incomplete Python code.
2) the major contribution of this prototype convers:
  a) it complete the full procedure of CNN for classification and object detection, including the additonal layers of flatten-> fully-connected layers -> classification -> location detection, and data in and results out with the main function; 
  b) it wrotes in C++ and with parallism option for CPUs. It is designed in object oriented with three classes and one main function: 
     (1) class: math operation; 
     (2) class: forward computation;
     (3) Class: backward computation;
     (4) main: read data in, train the model and output prediction results.

![image](https://user-images.githubusercontent.com/78186650/214994593-c41856f5-1714-4ea5-a288-2ba68a8218ee.png)

**Forward and backward computation formulates step by step**
![image](https://user-images.githubusercontent.com/78186650/214994307-706e989b-873b-47db-9a2e-977ca04d119e.png)
**Architecture and software design**
![image](https://user-images.githubusercontent.com/78186650/213967240-3339238f-82d4-4f31-b886-27040910c5e9.png)




