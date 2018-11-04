# 测试工具
  
   本测试系统在macOS 10.3.6 ,  python env,  python 2.7.10  , opencv 3.4.3
   可以正常运行  

  服务器启动：
  python manage.py runserver
  
  会在  http://localhost:8000 端口启动对应的face detect API 服务

  测试客户端启动:
  ./apitest  sourceimage

  运行结果:
  输出JSON 格式的 面部识别方框数据，并产生一个新的图像文件，将结果写入。
  在图像展示窗口中，敲击键盘任意键，退出程序。


## 前置条件

  安装 python 2.x  , 
  
  python2 中用pip 安装 request  , opencv 
  
