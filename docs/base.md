# Python 基础学习

## Python 安装

进入 [Python 官网](www.Python.com)，点击 Downloads- Windows-Python2.7.16,因为我的电脑是Windows,所以下载Windows版本，还有其他的版本，请参照官网。
下载完毕，点击安装， Install for all users ,点击下一步，默认在 C 盘，你可以选择你自己想要存储的磁盘，我是存在 D 盘。
点击完成，安装结束。

## 运行命令提示符
可以从开始菜单点击程序-附件-命令提示符来启动 Python,我们直接输入 Python ,系统提示我们找不到 Python 的命令,这是怎么回事呢, Windows 会根据命令查找 Python ,如果找不到，系统会提示错误,所以我们需要在把Python的路径填写在命令提示符里,打开我的电脑-属性-高级-环境变量-在系统变量选择 Path - 编辑 -在当前系统加Python安装目录，例如：```;D:\soft\python27```

![](./image/运行成功.png)

## 运行第一个程序
在终端输入 print "Hello，World" 
系统会出现 Hello，World
exit（）
这样是算运行第一个程序
但是唯一的一个缺点就是我们没有保存下来，下次输入还得重新做。
我们可以在MarkDown里写下print "Hello，World"再把它命名为 hello.py
首先我们在git bash.exe找到我们hello.py保存的所在目录，然后我们输入python hello.py

![](./image/hello.png)


