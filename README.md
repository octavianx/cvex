## OpenCV 试验程序集


face_detect demo:  使用 opencv 的训练模型， python3 + django 的一个面部识别webapi
  可以识别多个脸，还不能识别侧面，部分能够识别部分遮挡的脸
  

### 系统运行条件

OS:   macOS 10.3.6 

客户端测试工具
python 2.7.10    /apitest

服务端
python 3.7.0     面部识别web API 
opencv 3.4.3 
django 2.10 

该程序基于 
https://www.pyimagesearch.com/2015/05/11/creating-a-face-detection-api-with-python-and-opencv-in-just-5-minutes/

的版本修改而成。
源程序在django和opencv较早期版本的基础上制作，所以会有一系列兼容性问题导致不可运行。
