# cv-face_detect  web API 测试工具


## 运行环境

>本测试程序 在macOS 10.3.6 , python 2.7.10  , opencv 3.4.3  可以正常运行  

1. 确保python 环境中安装了  numpy  requests

```bash
$pip install numpy  requests 
```

2. 确保系统中安装了opencv   可以用 brew 安装 ，同时支持 python 的多个环境，(2.x, 3.x)



##使用方法

``` bash
 $./apitest  [sourceimage]
```

  运行结果:
1. boundbox 
2. 图像识别结果窗口
3. 在图像识别窗口敲击任意键盘后，退出程序，并保存识别结果到另外一张图片



