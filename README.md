PycUI:Python console color
====
简介
----
	Python 终端控制台彩色输出模块
	适用于windows控制台以及linux等终端
用法
----
#### 导入模块
```py
from pycui import *
```
#### 初始化对象
```py
color = color()
cui = pycui()
```
#### 彩色输出示例
```py
color.p("这里是红色的文字", color.RED)
```
#### 彩色输出函数
```py
cui.warning("警告信息")
```
颜色表
-----
	color.RED	 红色
	color.GREY   灰色
	color.BLUE   蓝色
	color.CYAN   青色
	color.BLACK  黑色
	color.GREEN  绿色
	color.WHITE  白色
	color.PURPLE 紫色
	color.YELLOW 黄色
函数表
-----
	warning		警告信息		简写w
	info		提示信息		简写i
	error		错误信息		简写e
	success		成功信息		简写s
