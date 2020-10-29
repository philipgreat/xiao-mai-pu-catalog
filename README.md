# 多媒体引擎 - 通过语义获得图片


* 通过这里访问地址用于测试：

https://demo.doublechaintech.com/demodata/imageManager/listOf2/drink/
https://demo.doublechaintech.com/demodata/imageManager/listOf2/truck/

* drink和truck都是目录的名字


### 增加图片
* 在pic/things下面加入一个目录，目录一定是一个有名的数据，假设foo
* 在目录下面加入图片
* 通过执行 ./sync-pic.sh 来把加入的图片放到生产服务器上

### 引用

* 在模型文件里面输入 image_path="foo.jpg"


