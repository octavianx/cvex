# cv-face_detect  web API 测试工具


## 运行环境

>本测试程序 在macOS 10.3.6 , python 2.7.10 或者  python3.7.0   , opencv 3.4.3  可以正常运行  

1. 确保python 环境中安装了  numpy  requests

```bash
$pip install numpy  requests 
```

2. 确保系统中安装了opencv   可以用 brew 安装 ，同时支持 python 的多个环境，(2.x, 3.x)



## 使用方法
  服务器启动：
```bash
python manage.py runserver
```  
  会在  http://localhost:8000 端口启动对应的face detect API 服务

  测试客户端启动:
``` bash
 $./apitest.py  [sourceimage]
```

## 运行结果:
1. boundbox 
  输出JSON 格式的 面部识别方框数据，并产生一个新的图像文件，将结果写入。
2. 图像识别结果窗口
3. 在图像识别窗口敲击任意键盘后，退出程序，并保存识别结果到另外一张图片
