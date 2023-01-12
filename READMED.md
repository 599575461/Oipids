## 功能

### 目前已实现

- 文本加/解密
- 文件加/解密
- 目录递归加/解密
- 英语单词 **解释,音标,语态变化,英文解释,读音** 

### 待完成

- 设置系统
- 图像加密
- 优化代码
- 窗口优化
- 程序打包

## 框架

使用**PyQt5**进行开发

## 使用

### 英语学习

启动程序，会看到一个窗口框架

![image-20230112130010286](C:\Users\59957\AppData\Roaming\Typora\typora-user-images\image-20230112130010286.png)

这是需要等待程序初始化字典，弹出“词典初始化成功”的窗口即可开始使用

![image-20230112130103778](C:\Users\59957\AppData\Roaming\Typora\typora-user-images\image-20230112130103778.png)

此时会在弹出一个窗口

![image-20230112130155835](C:\Users\59957\AppData\Roaming\Typora\typora-user-images\image-20230112130155835.png)

右边的窗口为详细信息，左边为主窗口

详细信息窗口记录单词的语态变化,英文翻译,主窗口记录单词，音标，中文解释

如果想要切换单词，点击主窗口的“Next”

![image-20230112130416048](C:\Users\59957\AppData\Roaming\Typora\typora-user-images\image-20230112130416048.png)

如果想要去其他平台查看单词信息可点击详细信息下的“有道”和“爱词霸”

![image-20230112130525733](C:\Users\59957\AppData\Roaming\Typora\typora-user-images\image-20230112130525733.png)

如果想要获取单词的读音，点击“音乐”按钮，这是程序会自动播放单词读音

![image-20230112130700477](C:\Users\59957\AppData\Roaming\Typora\typora-user-images\image-20230112130700477.png)

想要自定义单词在下方输入然后点击“获取”即可

### 加密系统

点击“英语学习”旁边的“加密系统”会自动切换页面

![image-20230112132756417](C:\Users\59957\AppData\Roaming\Typora\typora-user-images\image-20230112132756417.png)

在加密框的输入 **文本**或**路径**或**目录**

输入后点击“**start**”按钮

在**文本浏览**框中查看结果，如果勾选**覆盖文件**指定的文件将会被替换，如果勾选写入日志，将会写入**log.log**(程序根目录)

点击右边的**文件图标**即可浏览文件

设置按钮暂时只会弹出设置窗口，设置**不会生效**
