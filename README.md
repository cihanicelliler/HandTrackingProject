# :computer:Set Computer Volume With Hand Tracking Project:computer:
![image](https://user-images.githubusercontent.com/55557233/143551219-74cf6ecb-6809-49d7-8119-5462f3b2c1ec.png)

## This project is an application made to adjust the sound of your computer with the help of hand tracking..

### Many tools and frameworks such as OpenCV, MediaPipe, Numpy, Math , PyCaw and similar are used in this project.

 ![image](https://user-images.githubusercontent.com/55557233/143552725-16757aef-11a3-4470-8a39-ba6b1302868f.png)

## :white_check_mark:**OpenCV:**
 - OpenCV is a cross-platform library using which we can develop real-time computer vision applications. It mainly focuses on image processing, video capture and analysis including features like face detection and object detection.
 
 ![image](https://user-images.githubusercontent.com/55557233/143553101-38aebf2b-363c-4321-a37e-ce843878fa4d.png)

## :white_check_mark:**MediaPipe:**
- MediaPipe is a cross-platform framework for building multimodal applied machine learning pipelines
MediaPipe is a framework for building multimodal (eg. video, audio, any time series data), cross platform (i.e Android, iOS, web, edge devices) applied ML pipelines. With MediaPipe, a perception pipeline can be built as a graph of modular components, including, for instance, inference models (e.g., TensorFlow, TFLite) and media processing functions.
```
self.mpHands = mp.solutions.hands
self.mpDraw = mp.solutions.drawing_utils
```
With this code block, you can do hand tracking and have it drawn on the screen..

![image](https://user-images.githubusercontent.com/55557233/143553382-407c9754-edba-456d-aa34-47daf385a14d.png)

## :white_check_mark:**Numpy:**
- NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.
```
vol = np.interp(length,[25,250],[minVol,maxVol])
        volBar = np.interp(length,[25,250],[400,150])
        volPer = np.interp(length,[25,250],[0,100])
```
With this code block, you can easily proportion 4 numbers to be directly proportional to each other.

## :white_check_mark:**PyCaw:**
- This module makes it possible for us to adjust the sound on the computer
- For author: https://github.com/AndreMiras/pycaw

## :white_check_mark:**Math:**
- This module provides access to the mathematical functions defined by the C standard.
```
length = math.hypot(x2-x1, y2-y1)
```
With this code block, The math.hypot() method returns the Euclidean norm.



Thank you for taking your time to read. You can contact me from my accounts below.<br>
<br>

<a href="https://github.com/cihanicelliler" target="_blank">

![alt text](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

</a>
<a href="https://www.linkedin.com/in/cihan-icelliler/" target="_blank">

![alt text](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)

</a>
